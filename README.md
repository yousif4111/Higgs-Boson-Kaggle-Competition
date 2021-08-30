# Higgs-Boson-Kaggle-Competition
## Background
The Discovery of Higgs Boson, which is an elementary particle of particle physics, was recently claimed by the ATLAS experiment and the CMS experiment. This discovery was acknowledged by the 2013 Nobel prize in physics given to Francois Englert and Peter Higgs. The related experiments are running at the Large Hadron Collider which is commonly known as LHC at CERN (the European Organization for Nuclear Research), Geneva, Switzerland; which began operating in 2009 after about 20 years of design and construction.
![image](https://user-images.githubusercontent.com/46527978/131399408-59cbbf7d-a07e-4316-a11d-b2200198d824.png)
## The objective of the project
a) To improve the Higgs Boson decaying by predicting performance of binary classification for the targeted class using supervised machine learning techniques.

b) To make a comparison and identify which supervised machine learning can perform better using this dataset in generating the highest accuracy level.

C) To measure the effect of the outliers in data set on different supervised machine learning techniques and identify which one can handle outliers better.
## Dataset Description
For this project, we are using a Higgs Boson dataset downloaded from OpenML website. This dataset has been produced using Morte Carlo simulations that consists of 28 features or attributes and one class pertaining to physics particle measurement.
 The first column is referring to the class label or the target that use to differentiate and labelled the instances (rows) based on the features that suit it. For the class target, the value 1 denote as Signal and value 0 denote as Noise (which represent the background noise produce as the particle collide with each other).
 Twenty one (21) low features/attributes that represent the independent variables of X are refers to kinematic properties (lepton pT, lepton eta, lepton phi, missing energy magnitude, missing energy phi, jet 1 pt, jet 1 eta, jet 1 phi, jet 1 b-tag, jet 2 pt, jet 2 eta, jet 2 phi, jet 2 b-tag, jet 3 pt, jet 3 eta, jet 3 phi, jet 3 b-tag, jet 4 pt, jet 4 eta, jet 4 phi, jet 4 b-tag ). Seven (7) high label features derived by physicists (m_jj, m_jjj, m_lv, m_jlv, m_bb, m_wbb, m_wwbb). The total of instances are 98050 rows and the 28 of the attributes contain numerical value.
## Methodology
### Data Pre-Processing
### Naive Bayes
### Logistic Regression
### Random Forest
### Extreme Gradient Boosting (XGBoost)
