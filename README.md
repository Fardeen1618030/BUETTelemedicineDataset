# BUET-Telemedicine-Dataset
In-house BUET telemedicine speech dataset consisting of conversational speech recordings from healthy volunteers and respiratory distress patients obtained from a telehealth provider. 
The audio clips in this dataset were divided from speech recordings of 88 patients collaborating with Digital Healthcare Solutions (DHS), a telemedicine service provider in Bangladesh that operates through direct phone calls between the patient and physicians. The collected speech recordings can be categorized as containing (i) severe respiratory distress, (ii) mild respiratory distress, and (iii) no respiratory distress (healthy subject), as reported by the subjects.
The folds are different samples of the same data pool, divided into the train and test set to ensure that every patient’s speech recordings are in the test set at least once. The train-test split ratio for each fold is approximately 3 : 1, and we ensure that no patient’s speech data is present in both sets for a fold. Only the audio files longer than 3 seconds are used here. Maintaining a minimum audio length of 3s ensures a sufficient presence of the long-term features of conversational speech. 
Examples of the labelling method of the files: 
Example 1: C01_1
C: Control (Considered as 0 for binary detection of respiratory distress)
01_1: Patient No._ Audio Clipp No.

Example 2: M01_2
M: Mild Respiratory Distress (Considered as 1 for binary detection of respiratory distress)
01_2: Patient No.1 _ Audio Clip No.2

Example 3: S01_2
S: Severe Respiratory Distress (Considered as 1 for binary detection of respiratory distress)
01_2: Patient No.1 _ Audio Clip No.2

Example 4: A01_2
A: Asthma (Considered as 1 for binary detection of respiratory distress)
01_2: Patient No.1 _ Audio Clip No.2


