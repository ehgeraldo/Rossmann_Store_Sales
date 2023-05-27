![104977231-ca344600-59dd-11eb-94c4-26f431bc2802](https://github.com/ehgeraldo/Rossmann_Store_Sales/assets/58346288/27599405-61d6-425c-bd55-d2dfc960b20c)


# Business Understanding

## What is the company?

# Rossmann Drug Store.
## What is its business model?

Rossmann operates over 3,000 drug stores in 7 European countries. Its products range includes up to 21,700 items and can vary depending on the size of the shop and the location. In addition to drugstore goods with a focus on skin, hair, body, baby and health, Rossmann also offers promotional items ("World of Ideas"), pet food, a photo service and a wide range of natural foods and wines. What is the business problem the company is facing?

Rossmann store managers need daily sales predictions for up to six weeks in advance so as to plan infrastructure investments in their stores (will next six weeks sales be high enough to balance infrastructure investment?). What is the business solution that this project has to deliver?

For each store, the daily sales predictions for the next six weeks.
Business assumptions
Hypothesis

In order to make predictions for the next six weeks, Rossmann company has to provide data about its stores for this time interval. Such data, for each store, must include: store model, store assortment level and if the given store will be on continuous promotion.

## References:

https://www.kaggle.com/c/rossmann-store-sales https://en.wikipedia.org/wiki/Rossmann_(company)

"Europe: top personal care retailers' store numbers 2019". Statista. Retrieved 2020-12-07.

"Personal Care Retailers in Europe". www.retail-index.com. Retrieved 2020-12-07.

"Annual report 2019" (PDF).

"Dirk Rossmann". Forbes. Retrieved 9 June 2015.

"Deshalb hat Rossmann so ein ungewöhnliches Logo gewählt". Business Insider (in German). 2016-08-19. Retrieved 2020-12-07.

"Wusstest du es? Das ist das Geheimnis hinter dem Rossmann-Logo!". BRIGITTE (in German). Retrieved 2020-12-07.

"Markengeschichte". ROSSMANN Unternehmen. Retrieved 2020-12-07.

"Nachhaltig zum Erfolg | Markant Magazin". www.markant-magazin.com. Retrieved 2021-06-14.

"ROSSMANN-Nachhaltigkeitsbericht". ROSSMANN-Nachhaltigkeitsbericht. Retrieved 2021-06-14.

# Solution strategy method
![image](https://user-images.githubusercontent.com/58346288/224571421-ee98ac7f-5ce8-4300-95d0-a60b8bd8b995.png)




##  Step 01. Data Extraction:
For the available data, check files and data fields description process. Then load data from CSV files and merge different tables.

##  Step 02. Data Description:
Rename columns and check the number of rows in the table. Convert data types for some columns and fill out NA (not-available) values. Then use statistics metrics to identify data outside the scope of business.

##  Step 03. Feature Engineering:
Create a hypothesis list to check on the fifth step (EDA). Then apply data transformations on the required columns.

##  Step 04. Data Filtering:
Filter rows and select columns that make sense to modeling or do not match the scope of the business, such as predict sales for a closed store.

## Step 05. EDA Exploration Data Analysis:
Analysis of each variable separately and, and the relationship with the response variable. And validation of hypotheses created at the beginning of the project to gain insights.

##  Step 06. Data Preparation:
Split data into train and validation. Then, prepare data so that the Machine Learning models can more easily learn and perform more accurately.

##  Step 07. Feature Selection:
Using Boruta algorithms to select the most signiﬁcant attributes for training the model.

##  Step 08. Machine Learning Modelling:
Test different Machine Learning models (Linear and Non-Linear) and select the one with the best performance in prediction sales according to the selected attributes.

##  Step 09. Hyperparameter Fine Tuning
Try to figure out the best values parameters selected on Machine Learning.

## Step 10. Deployment
Creating APIs to make sales prediction from each store on internet requests.

# TOP 03 INSIGHTS
## H1. The kind of assortment store influence differently sales
#### H1 checked: Extra assortment has higher sales than other standard stores.
![Captura de tela de 2023-05-27 15-56-55](https://github.com/ehgeraldo/Rossmann_Store_Sales/assets/58346288/c6f11150-ef2f-4532-966b-4991a56b27aa)
## H1 checked: basic and extended looks like similar and extra assortment are totally back to other class.
![Captura de tela de 2023-05-27 15-59-10](https://github.com/ehgeraldo/Rossmann_Store_Sales/assets/58346288/61e3a1af-0190-4766-bbda-2df495997e92)






