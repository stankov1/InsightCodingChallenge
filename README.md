Libraries used for python source code:
os, sys, getopt, numpy, datetime, collections

Instructions:

Two seperate scripts (in src folder) are ran by run.sh:
1) search_by_zip.py creates medianvals_by_date.txt
2) search_by_day.py creates medianvals_by_zip.txt

They can be run seperately depending on what output is needed. 

To run.sh enter this command into a terminal:
$ sh run.sh  

run.sh runs both src scripts with their appropriate path inputs:

$ python ./src/search_by_zip.py ./input/itcont.txt ./output/medianvals_by_zip.txt 
$ python ./src/search_by_date.py ./input/itcont.txt ./output/medianvals_by_date.txt

My input file (930.3MB, also named itcont.txt) is from the 2017-2018 files (indiv18.zip from http://classic.fec.gov/finance/disclosure/ftpdet.shtml).

