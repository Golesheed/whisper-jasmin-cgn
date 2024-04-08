# A Pilot Study on the JASMIN-CGN Corpus Using the Whisper Model
## Description
We test and study the variation in speech recognition of fine-tuned versions of Whisper on children, elderly and non-native Dutch speech from the JASMIN-CGN corpus. 
## Requirements
Make sure you have JASMIN-CGN downloaded (download from here: [https://taalmaterialen.ivdnt.org/download/tstc-jasmin-spraakcorpus/])
## How to use the files:
-  First you will remove the silences of the data (use https://github.com/Golesheed/whisper-jasmin-cgn/blob/main/silnece__remover.ipynb)
-  Then you need to make the data into 30 second chunks (use https://github.com/Golesheed/whisper-jasmin-cgn/blob/main/split%20split.ipynb)
-  You need to make a csv from the ort files! (https://github.com/Golesheed/whisper-jasmin-cgn/blob/main/addsentencetocsv.ipynb) and convert to UTF-8 (https://github.com/Golesheed/whisper-jasmin-cgn/blob/main/utf8er.ipynb)
-  divide your datasets (https://github.com/Golesheed/whisper-jasmin-cgn/blob/main/datasetpp.ipynb)
