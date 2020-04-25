<!--
 * @Author: your name
 * @Date: 2020-04-16 19:40:22
 * @LastEditTime: 2020-04-25 21:05:46
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \models\README. md
 -->
Some pretrained models of project [PHBS_MLF_2019_Project
](https://github.com/oyrx/PHBS_MLF_2019_Project). 

## Models available

* **Logistic Regession**
    - [LogisticRegression_04161442.model](https://github.com/oyrx/PHBS_MLF_2019_Project_Models/blob/master/LogisticRegression_04161442.model)

* **Random Forest** (*only parameters uploaded due to file size*)
    - [RandomForest_04160226_88.74%.txt](https://github.com/oyrx/PHBS_MLF_2019_Project_Models/blob/master/RandomForest_04160226_88.74%25.txt)

* **GBDT / DART in LightGBM**
    - [LightGBM_04160053.model](https://github.com/oyrx/PHBS_MLF_2019_Project_Models/blob/master/LightGBM_04160053.model)
    - [LightGBM_04161347.model](https://github.com/oyrx/PHBS_MLF_2019_Project_Models/blob/master/LightGBM_04161347.model)  

* **GBDT in XGBoost**
    - [XGBoost_04152029.model](https://github.com/oyrx/PHBS_MLF_2019_Project_Models/blob/master/XGBoost_04152029.model)

* **ANN** (*only parameters uploaded due to file size*)
    - [final_ann_model_mod.pt](https://github.com/oyrx/PHBS_MLF_2019_Project_Models/blob/master/final_ann_model_mod.pt)  

## Filename explained

|Type |Filename |
|---|--- |--- |--- |--- |--- |  
|**Model dumped**| `{model}` _ `{datetime}` . model 
| |*e. g. LogisticRegression_04161442. model*| 
|**Confusion matrix**| `{model}` _ `{datetime}.` png |
 ||*e. g. LogisticRegression_04161442. png* |
|**Parameter**| `{model}` \_ `{datetime}` \_ `{accuracy}` %. txt 
|| *e. g. LogisticRegression_04161442_89. 04%. txt* |

For ANN parameters: `final_ann_model_mod.pt` . 

---
This project is under MIT license. 
