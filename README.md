# filtfilt

This repository is used to implement a functional zero-phase digital filter known as the 'filtfilt' function (MATLAB, SciPy, Ardour etc.) in structured text for an application in a industrial PLC.

Following steps are planned:
1) Use open source code (C++) of the audio tool Ardour from Linux Audio Systems to understand a basic implementation of the filtfilt function. [done]
2) Implement the filtfilt function in python. [done]
3) Verify implementation by comparing the filtering results of artifical data (noisy ECG Wave and noisy sine wave) with MATLAB and SciPy filtfilt() results [done]
4) Implement verified python code in structured text as a function block [done]
5) Upload PLC project from CODESYS as an projectarchive [done]

You can download and extract the CODESYS projectarchive to see the implementation of filter and filtfilt function in CODESYS.
The example project contains three types of signals (ECG Signal, Sine Wave and Real Sensor Data) which are filtered using the filtfilt function. The filter coefficients were calculated using MATLAB.


