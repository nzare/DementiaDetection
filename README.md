## Detection of Dementia using Machine Learning techniques

### What is Dementia ?
A general term for loss of memory, language, problem-solving and other thinking abilities that are severe enough to interfere with daily life. 
**Alzheimer’s** is the most common cause of dementia.

### Detection of Dementia
Patients suffering from Dementia have shrinkage of brain tissues and change in their speech patterns. 
Thus dementia can be detected in two major ways:
- Speech Patterns
- MRI Images

The current treatment cannot stop the disease but rather slow down the damage caused.
Detecting at early stage can reduce damage to large extent.


### Using MRI Images
MRI images of Alzheimer Disease(AD) patients show both local and generalized shrinkage of brain tissues. There are various other factors like age,education and socioeconomic status that determines the course of the disease.
We use Machine Learning techniques to detect dementia even at mild damage so that immediate treatment can be given.


### Dataset
- We used MRI related dataset from Open Access Series of Imaging Studies (OASIS)
- It is longitudinal MRI data consisting of 150 people aged between 60 to 96.
- Everyone is right handed.
- Some patients were under NonDemented category at first visit but later on were found Demented. These fall under category Converted.

#### Column Description

| Column Name | Description |
| --- | ----------- |
| EDUC | Years of education |
| SES | Socioeconomic Status |
| MMSE | Mini Mental State Examination |
| CDR | Clinical Dementia Rating |
| eTIV | Estimated Total Intracranial Volume |
| nWBV | Normalized Whole Brain Volume |
| ASF | Atlas Scaling Factor

