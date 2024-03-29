# PUMML_MXene_Synthesize
 <div align="justify">
   
Prediction of Synthesis of 2D Metal Carbides and Nitrides (MXenes) and Their Precursors with Positive and Unlabeled Machine Learning.
This is a course project completed as part of my PhD program.

## Abstract
This project uses open source dataset and positive and unlabelled machine learning technique to predict synthesizability of MXene and MAX precursor. Detailed hyperparameter tuning is carried out to generate a model with true positive rate greater than 0.9. The finalized model is then used to predict that 155 unlabelled MAX and 19 unlabelled MXene could be synthesized. Analysis of the model output suggests unique result regarding synthesizability of MXene that is not reported in literature. A further analysis to match MXene with respective precursor suggest that only 11 MXene could be synthesized due to the lack of synthesizable MAX precursor. Overall, this project could push forward the discovery of new generation of MXene, which would greatly expand material selection freedom for high performance applica- tions.

## Dataset
The dataset is obtained from pumml. Pumml is an open source Python library that performs positive and unlabeled material machine learning (hence the name pumml) to classify materials when data is either incomplete or when examples of positive data is insufficient. Pumml offers a test dataset consisting of 66 entries of MXene phase and 792 entries of MAX phase. Only single M element is considered in order to reduce computational complexity. Of these entries, 10 entries of MXene and 63 entries of MAX phase are labeled positive (already successfully synthesized). Therefore, a fraction over 10 % of overall data are labelled positive, and the rest are unlabelled, making this pumml work a semi-supervised machine learning approach.

The dataset used for this project only consist of 4 features as shown below. These features represent four of the highest importance as confirmed by feature selection result from Frey et al. Using only the most important feature for model prediction can to some extent avoid over fitting as well as reduce computational time, which is highly desirable for this project.

 </div>

