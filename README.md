## Pima Indian Women Diabetes Data

# Table of contents

- [📝 Problem Statement](#Problem-Statement)
- [💡 Project Objectives](#Project-Objective)
- [🔬 Analysis Summary and Discussion](#Analysis-Summary-and-Discussion)
- [😎 Reach Out To Me](#about-me)

### 📝 Problem Statement <a name= "Problem-Statement"></a>
Diabetes is one of the ailments that takes lives if not detected early and treated. 
Knowing and confirming the variables that contribute to this disease is one of the aims of this project. 



### 💡 Project Objectives <a name= "Project-Objective"></a>:
1. Knowing the factors most responsible for diabetes in Women
2. Building a model that predicts a diabetes prognosis.
3. Hypertuning the model to reduce the risk of predicting that a patient isn't diabetic when the patient infact is diabetic

### 🔬 Analysis Summary and Discussion<a name= "Analysis-Summary-and-Discussion"></a>
1. Which factors are most responsible for diabetes in women?
    - Age
        - Women above 28 years are at more risk to diabetes than younger women.
    -Glucose
        - Women with glucose level greater than 127mg/dL are more liable to be diagnosed as diabetic
    -BMI
        - Women with BMI greater than 30 are more liable to be diabetic. BMI above 30 shows obesity.
    -Insulin

2. What were the machine learning algorithms that was tested in order to build the model?
    -Decision tree
    -Random Forest
    -Gradient Boosting
3. What metric was used to determine the best model?
    - The metric that was optimized during the process of building the model was the RECALL score.
    - The higher the recall score,the lower the false negatives.
    - False negatives means that the model predicts that a person is not diabetic when the person actually is.

4. The machine learning algorithms listed above went through hypertuning in order to reduce overfitting and to increase the recall score.
5. The best model has a recall score of 0.82. Also, Of the 98 people that were diabetic,the model was able to correctly classify 87 as diabetic and incorrectly classified 11 as diabetic. This shows that the model predicts with low chance of misclassifying a diabetic patient as non-diabetic.

### 😎 Reach Out To Me <a name= "about-me"></a>
My name is Oketunji Oludolapo and you can reach out to me on Linkedin by clicking [HERE](https://www.linkedin.com/in/oludolapo-oketunji/)


