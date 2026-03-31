# How-to-use-OpenBCI-GUI-fork


## NEW (Under testing)

# [Method A] - EASY - way to connect to MODERN OpenBCI GUI Fork: 

Install forked version of program here: 
and
You must have the LSL test script running with python before you turn on the gui: [Read This](https://github.com/Cerelog-ESP-EEG/Lab-Stream-Layer-LSL-Compatability)**

or 

# [Method B] - For developers - or if you run into issues you can run the below linked gui in the processing application

Download processing version 4.2. You must have the LSL test script running: [Read This](https://github.com/Cerelog-ESP-EEG/Lab-Stream-Layer-LSL-Compatability)**

And run this in processing
https://github.com/Cerelog-ESP-EEG/OpenBCI_Fork_New


--------------------------------------


# [Method C] (Old gui but verified) Working Method:  Installing OpenBCI

This section covers installing and running the Lab Streaming Layer branch of the custom fork of [OpenBCI_GUI](https://github.com/Cerelog-ESP-EEG/OpenBCI_GUI-Fork)

We can't use the regular released version of OpenBCI because its now been modified of the OpenBCI GUI to take [Lab Streaming Layer](https://github.com/sccn/labstreaminglayer) input, and these changes haven't made it back into the main released version.

1. **Download ONLY VERSION 3.5.4 of [Processing](https://processing.org/releases) app (CAREFUL!!! Other versions do NOT work)**

2. **Using git, clone the custom fork of [OpenBCI_GUI](https://github.com/Cerelog-ESP-EEG/OpenBCI_GUI-Fork)**

   ```bash
   $ git clone https://github.com/Cerelog-ESP-EEG/OpenBCI_GUI-Fork.git
   ```

3. **(This should be default branch but if not) Switch to the `feature/lsl-input-and-clinical-eeg-bandpass-filter` branch**

   ```bash
   $ git checkout feature/lsl-input-and-clinical-eeg-bandpass-filter
   ```

4. **Copy and paste all libraries from the repo located in OpenBCI_GUI-Fork/OpenBCI_GUI/libraries to the application Processing's /documents/processing/libraries folder**

5. **Using Processing, open the `OpenBCI_GUI` directory that you cloned in the step 2 (File > Open on a Mac, for instance).**

6. **Ensure the board is using LSL for streaming data; you must have the LSL test script running: [Read This](https://github.com/Cerelog-ESP-EEG/Lab-Stream-Layer-LSL-Compatability)**

7. **Click the Run button w processing**

8. **OpenBCI should start up; Select stream with Lab Stream Layer 8 CH and then Start Stream**
```
