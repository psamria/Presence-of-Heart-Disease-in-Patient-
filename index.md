## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/psamria/Supervised-Machine-Learning-Project--Presence-of-Heart-Disease-in-Patient-/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/psamria/Supervised-Machine-Learning-Project--Presence-of-Heart-Disease-in-Patient-/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

# CASE STUDY REPORT 

##### Group No.: Group-11 (Section-2)
##### Student Names: Prerit Samria and Seungyeon Ko

## Executive Summary 

The goal of the case study is to find the best model to predict whether a patient has heart disease or not based on their medical records. There are thousands of deaths every year around the world due to heart diseases. Thus, a model to predict the presence of heart disease would be beneficial to save many lives. Similar methods could be employed to predict other prevalent diseases in the world. The data ‘Heart Disease Data Set’ has been taken from the University of California Irvine. After preprocessing the data, 5 models, namely k-NN, Naïve Bayes Classifier, Classification Trees, Logistic Regression, and Neural Network, were used. The best performance in terms of accuracy on validation data is achieved by Neural Network.

## Background and Introduction

The cardiovascular (or heart) disease is a prevalent disease that causes thousands of deaths every year around the world. In general, cardiovascular disease results from the narrowed or blocked blood vessels that can lead to a heart attack, chest pain or stroke. Other heart conditions, such as those that affect your heart's muscle, valves or rhythm, also are considered forms of heart disease. However, many causes of death are still not identified. The goal of this case study is to find the best method to predict whether a patient has heart disease or not based on their medical records. Similarly, different methods could be employed to predict other prevalent diseases in the world. 

## Data Exploration and Visualization

_Table-1: Classifying the predictors_
| **Predictor** | **Numerical (N)/Categorical (C)** |
| :-- | :--: |
| Age (in years) | N |
| Sex (male:1, female:0) | C |
| Chest Pain Type (CP) (0,1,2,3) | C |
| Resting blood pressure (trestbps) | N |
| Serum cholesterol in mg/dl (chol) | N |
| Fasting blood sugar(fbs) (fbs>120: 1, else:0) | C |
| Resting electrocardiographic (restecg) (hyp: 0, norm: 1, abn: 2) | C |
| Maximum heart rate achieved (thalach) | N |
| Exercise-induced angina (exang) (true:1, else:0) | C |
| ST depression (oldpeak) | N |
| Slope of the peak exercise ST segment (up: 2, flat:1, down: 0) | C |
| Ca number of major vessels (0-3) | C |
| Thal (2:normal, 1:fixed defect, 3:reversable defect) | C |
| Output: Target (buff: 0: not having heart disease, sick: 1: having heart disease) | C |

The dataset comprises of ***13 predictors*** and ***1 outcome variable***. The outcome target is a binary variable: 0 means a person who does not have heart disease, and 1 means a person who has heart disease. Figure-1 and table-1 give basic information about the dataset.

	
