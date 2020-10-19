# filtfilt

This repository is used to implement a functional zero-phase digital filter known as the 'filtfilt' function (MATLAB, SciPy, Ardour etc.) in structured text for an application in a industrial PLC.

Following steps are planned:
1) Use open source code (C++) of the audio tool Ardour from Linux Audio Systems to understand a basic implementation of the filtfilt function. [done]
2) Implement the filtfilt function in python. [done]
3) Verify implementation by comparing the filtering results of artifical data (noisy ECG Wave and noisy sine wave) with MATLAB and SciPy filtfilt() results [done]
4) Implement verified python code in structured text as a function block [pending]

