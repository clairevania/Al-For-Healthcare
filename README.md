# Projects Overview
## [Project 1: Pneumonia Detection from Chest X-Ray](https://github.com/clairevania/Al-For-Healthcare/tree/main/Pneumonia%20Detection%20From%20Chest%20X-Ray)
Chest X-ray exams are one of the most frequent and cost-effective
types of medical imaging examinations. Deriving clinical diagnoses
from chest X-rays can be challenging, however, even by skilled
radiologists. When it comes to pneumonia, chest X-rays are the best 
available method for point-of-care diagnosis. More than 1 million
adults are hospitalized with pneumonia and around 50,000 die
from the disease every year in the US alone. The high prevalence
of pneumonia makes it a good candidate for the development of a
deep learning application for two reasons: 1) Data availability in a
high enough quantity for training deep learning models for image
classification 2) Opportunity for clinical aid by providing higher
accuracy image reads of a difficult-to-diagnose disease and/or reduce
clinical burnout by performing automated reads of very common
scans. In this project, you will analyze data from the NIH Chest
X-ray dataset and train a CNN to classify a given chest X-ray for the
presence or absence of pneumonia. First, we’ll curate training and
testing sets that are appropriate for the clinical question at hand from
a large collection of medical images. Then, we will create a pipeline
to extract images from DICOM files that can be fed into the CNN for
model training. Lastly, we’ll write an FDA 501(k) validation plan that
formally describes the model, the data that it was trained on, and a
validation plan that meets FDA criteria in order to obtain clearance of
the software being used as a medical device.

## Project 2: Patient Selection for Diabetes Drug Testing
EHR data is becoming a key source of real-world evidence (RWE)
for the pharmaceutical industry and regulators to make decisions
on clinical trials. In this project, we will act as a data scientist
for an exciting unicorn healthcare startup that has created a
groundbreaking diabetes drug that is ready for clinical trial testing.
Task will be to build a regression model to predict the estimated
hospitalization time for a patient in order to help select/filter
patients for your study. First, we will perform exploratory data
analysis in order to identify the dataset level and perform feature
selection. Next, we will build necessary categorical and numerical
feature transformations with Tensorflow. Lastly, we will build a
model and apply various analysis frameworks, including Tensorflow
Probability and Aequitas, to evaluate model bias and uncertainty

## Project 3: Motion Compensated Pulse Rate Estimation
Wearable devices have multiple sensors all collecting information
about the same person at the same time. Combining these
data streams allows us to accomplish many tasks that would be
impossible from a single sensor. In this project, we will build an
algorithm which combines information from two of the sensors
 -- the IMU and PPG sensors -- that
can estimate the wearer’s pulse rate in the presence of motion.
First, we’ll create and evaluate an activity classification algorithm
by building signal processing features and a random forest model.
Then, we will build a pulse rate algorithm that uses the activity
classifier and frequency domain techniques, and also produces
an associated confidence metric that estimates the accuracy
of the pulse rate estimate. Lastly, we will evaluate algorithm
performance and iterate on design until the desired accuracy is
achieved.

## Project 4: Hippocampal Volume Quantification in Alzheimer’s Progression
Hippocampus is one of the major structures of the human brain
with functions that are primarily connected to learning and memory.
The volume of the hippocampus may change over time, with age,
or as a result of disease. In order to measure hippocampal volume,
a 3D imaging technique with good soft tissue contrast is required.
MRI provides such imaging characteristics, but manual volume
measurement still requires careful and time consuming delineation
of the hippocampal boundary. In this project, we will go through
the steps that will have us create an algorithm that will help
clinicians assess hippocampal volume in an automated way and
integrate this algorithm into a clinician’s working environment. First,
we’ll prepare a hippocampal image dataset to train the U-net based
segmentation model, and capture performance on the test data.
Then, we will connect the machine learning execution code into a
clinical network, create code that will generate reports based on
the algorithm output, and inspect results in a medical image viewer.
Lastly, we’ll write up a validation plan that would help collect clinical
evidence of the algorithm performance, similar to that required by
regulatory authorities.
