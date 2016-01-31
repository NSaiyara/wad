# TREC Evaluator Application

The purpose of this application is to provide a tool that lets researchers evaluate how good their search system is and how it compares to other systems (already submitted).

The application needs to engage the service of an external programme, called *trec_eval*: 
  - http://trec.nist.gov/trec_eval/

A TREC track/task consists of a title, url to track, year, description of the track, task type, a judgements file (qrels), a list of official measures, and notes.

Example tracks:
  - http://trec.nist.gov/data/robust.html
  - http://trec.nist.gov/data/webmain.html

## Code

In *data* directory, there is example data from three different tracks (i.e. news, robust, web).

In *participants*, there is the data from 5 test participants (i.e. AS, CK, HK, ICT, RIM) along with a number of runs that they have submitted to the robust track. 

The legacy application that you need to interface with is called *trec_eval*. It is written in C and needs to be compiled. Unzip/untar and then *make* the application.
