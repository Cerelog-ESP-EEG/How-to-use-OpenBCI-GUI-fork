# How-to-use-OpenBCI-GUI-fork




Installing OpenBCI
==================

This section covers installing and running the Lab Streaming Layer branch of the custom fork of
`OpenBCI_GUI <https://github.com/Cerelog-ESP-EEG/OpenBCI_GUI-Fork>`__
We can't use the regular released version of OpenBCI because its now been modified of the OpenBCI GUI to take
`Lab Streaming Layer <https://github.com/sccn/labstreaminglayer>`__ input, 
and these changes haven't made it back into the main released version.

# Download ONLY VERSION 3.5.4 of  

`Processing <https://processing.org/releases>`__ app

# Using git, clone the custom fork of 

`OpenBCI_GUI <https://github.com/Cerelog-ESP-EEG/OpenBCI_GUI-Fork>`__

    .. code-block:: bash

       $ git clone https://github.com/Cerelog-ESP-EEG/OpenBCI_GUI-Fork.git

# (This should be default branch but if not) Switch to the 

``feature/lsl-input-and-clinical-eeg-bandpass-filter`` branch

    .. code-block:: bash

       $ git checkout feature/lsl-input-and-clinical-eeg-bandpass-filter
# Copy and paste all libraries from the repo located in OpenBCI_GUI-Fork/OpenBCI_GUI/libraries to the application Processing's /documents/processing/libraries folder


# Using Processing, open the ``OpenBCI_GUI`` directory that you cloned in the step 2 (File > Open on a Mac, for instance).


# Click the Run button


# OpenBCI should start up
