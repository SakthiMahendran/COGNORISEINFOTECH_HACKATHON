"# COGNORISEINFOTECH_HACKATHON" 

Developed in MLOps structure
    - DataAnalysis
    - DataPreProcessing
    - ModelSelection
    - ModelTraining

Selected Model - "RandomForest"

**Justification:**
    The top performing Models are 
        - RandomForest
        - DecisionTree
        - GradientBoostingClassifier

**RandomForest vs DecisionTree** 
    At the end of the "RandomForest" is just a stack of "DecisionTree".... So it makes sense to use RandomForest over DecisionTree
    
**RandomForest vs GradientBoostingClassifier**
    Even though GradientBoostingClassifier is a good performing it is not good as RandomForest
    
**Possibility of overfitting**
    The RandomForest gave %100 accuracy on which is a sign of overfitting... though it is though to say check whether the 
    model is overfitted or not without a validation dataset I considered the below factors to choose RandomForest

        - Ensemble methods are generally resistant to overfitting
        - I tried by splitting the train data for both training and testing... Where the RandomForest didn't give 100% accuracy
        but though it performed better than other models 
