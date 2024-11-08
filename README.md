# winblows_snort

snort conf for your windows labs and envt, since its a betch to trace &amp; setup every time..

# Requirements
snort rules files, snort rules are all over the hub.  

# Concerns

ERROR: OpenAlertFile() => fopen() alert file log/alert.ids: No such file or directory 
DO: run the snort in logging mode

Concern: Path issues, added the following

dynamicpreprocessor directory C:\snort\lib\snort_dynamicpreprocessor

dynamicengine C:\snort\lib\snort_dynamicengine\sf_engine.dll

#dynamicdetection directory C:\snort\lib\snort_dynamicrules dont uncomment this.

include C:\snort\etc\threshold.conf
