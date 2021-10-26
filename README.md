# challenge-core-methods

In an effort to demonstrate the ability to develop signal processing software and methods,
we'd like you to address the following scenario:

The Assay team needs a tool that parses a json file derived from the output of a qPCR 
instrument. This file contains the well name, well index, and six channels by 55 cycle of 
timeseries signal data. The tool shall calculate the 
first and second derivatives of the timeseries signals in every channel, identifying
the cycles corresponding to the maximum first and maximum second derivative with 
floatpoint accuracy. 

The well name, well index, maximum first derivative cycle and maximum 
second derivative cycles should be output in a flat csv format, with one line
corresponding to every well/channel pair, and a header identifying the columns. 

It is expected that this tool use Python3 with a virtual environment. No dependencies
are required. 

The input json file is provided as plate.json in the repo. 
