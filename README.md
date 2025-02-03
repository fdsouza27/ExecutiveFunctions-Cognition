## Spatio-Cognitive Abilities and its association with Executive Functions in Young Adults - A Preliminary Study using Virtual Reality

![Poster](https://github.com/user-attachments/assets/27deb8c8-a2f7-4500-8041-23492b994e86)

### Aim
To understand how healthy young adults perform in VR environments with simple and complex levels of visuals.
 
### Objectives
 • Assess the association between spatio cognitive abilities and executive functioning in young adults.
 • Evaluate the capability of predicting WAIS Block Design scores based on executive function performance in VR tasks

### Approach
A realistic VR kitchen environment was set up, where participants completed two recipes: baking a pie and preparing a stew. Spatio-cognitive abilities were measured using the WAIS Block Design Score. Features representing executive functioning were engineered from  the data recorded from the participants’ activity in the VR environment. 

Data: Data was gathered from 32 participants, each completing recipes designed to represent simple and complex levels of visual complexity.
Feature engineering: A total of 186 features were extracted from the participant performing pie recipes, and 128 features from the stew recipes. For each of the recipe, there were 2 levels of visual complexity. Spearman’s correlation was used to measure the association between the engineered features and WAIS block design score.
Feature Selection: Both raw and normalized values were evaluated using ReliefF and Correlation-Based Feature Selection to identify the most significant features.
Supervised Modeling: Machine learning models, including linear regression, SMO regression, and random forest were used to predict Block Design Scores using selected features. Model performance was evaluated using correlation coefficients, MAE & RMSE





