# Eye state detection project
This project compares different machine learning models. This is the preparation for own data set and its processing.

The complete documentation is attached as a pdf file.

## Dataset
https://www.kaggle.com/markwallbang/eeg-eye-state

* All data is from one continuous EEG measurement with the Emotiv EEG Neuroheadset - https://www.emotiv.com/.
* There are 14 channels.
* The duration of the measurement was 117 seconds. 
* All values are in chronological order. 
* The eye state is the last column 
  * eeg_eye.arff - '1' indicates the eye-closed and '0' the eye-open state
  * eeg_eye_state.arff - updated file - state is 'open' or 'close'
