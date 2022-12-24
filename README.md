#### 1. Statement of the Problem
We need to build classification models to predict and classify the dataset is about the users' learning 
activities and knowledge levels on subjects of DC Electrical Machines and predict User Knowledge Level 
(UNS) based on five features which are [Study Time Score for Target Object Material (STG), User 
Repetition Count Score for Target Object Material (STR), the user's study time score for objects related 
to the target body (SCG), User Test Performance of Target Body Relevant Objects (LPR), Performance 
user testing of target objects (PEG)]. Using Support vector machine (SVM) and perceptron algorithms.

#### 2. Executive Summary
2.1 Import our Data User Modeling Dataset (DUMD) training and test set provided in CSV file format.

2.2 Preprocessing of the Data:

  a) Feature Selection on data to select the most important two features in the dataset using 3 methods.

   b) Convert the target (UNS) from categorical to numerical.

 2.3 Building the classification models:
  • SVM

  • Perceptron

  • SVM_OVR

  • SVM_OVO
