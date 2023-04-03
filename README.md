# flukereader
Little Python script for talking to Fluke ScopeMeters

Fork from https://github.com/eddic/flukereader/blob/master/flukereader.py

https://eddie.isatec.ca/2015/12/29/talking-to-my-scopemeter.html

As i couldn't get the makefile to to generate the plots working correctly my goal is to improve the file export and add an plot function with matplotlib

Image of a Plot generated with this tool : 

[Plot.pdf](https://github.com/simpre/flukereader/files/11138805/Plot.pdf)

The best option currently is to run it with the -k option, thats the one i develop curently. 

It's possible to save the measured data as pickle to restore and plot them later. Furthermore a small measurement protocol is saved with the results.


# ToDo  
- Save measuremnts and plot data in human readable format

