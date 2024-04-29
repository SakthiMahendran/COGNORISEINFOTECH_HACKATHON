# COGNORISEINFOTECH_HACKATHON

## Developed in MLOps Structure

- DataAnalysis
- DataPreProcessing
- ModelSelection
- ModelTraining

**Selected Model - "RandomForest"**

### Justification:

The top-performing Models are:

- RandomForest
- DecisionTree
- GradientBoostingClassifier

#### RandomForest vs DecisionTree

At the end of the day, RandomForest is just a stack of DecisionTree models. Therefore, it makes sense to use RandomForest over DecisionTree.

#### RandomForest vs GradientBoostingClassifier

Even though GradientBoostingClassifier performs well, it is not as good as RandomForest.

#### Possibility of Overfitting

The RandomForest achieved 100% accuracy, which could indicate overfitting. It is challenging to confirm without a validation dataset. Considered factors for choosing RandomForest:

- Ensemble methods are generally resistant to overfitting.
- Experimented with splitting the training data for both training and testing. RandomForest didn't achieve 100% accuracy but performed better than other models.
