# GNSS_SDR
A software-defined receiver for GPS L1 C/A signal using Matlab, mostly based on the files in the DVD files of "A Software-Defined GPS and Galileo Receiver: A Single-Frequency Approach".
We have added support for IQ data on top of it, so that the current version supports both single-channel signals and IQ data.
# Running the GNSS SDR software
1. In Matlab open the folder
2. Run the M-script init. Press 0 and then press Enter if you want to select a different data file (signal record) or if the default path is incorrect. If the default path to the data file is correct, press 1 at the MATLAB command prompt, then press Enter and then continue at step 4.
3. Modify the initSettings.m file to adapt to the signal file you provide.
4. Now the signal processing will start. It may take a few hours, depending on the speed of the computer, to process the data record. At the end results will be plotted
