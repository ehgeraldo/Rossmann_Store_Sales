# Business Understanding

## What is the company?

# Rossmann.
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




#  Step 01. Data Extraction:

For the available data, check files and data fields description. Then load data from CSV files and merge different tables.
#  Step 02. Data Description:

Rename columns and check the number of rows in the table (does it requires big data tools?). Convert data types for some columns and fill out NA (not-available) values. Then use statistics metrics to identify data outside the scope of business.
#  Step 03. Feature Engineering:

Create a hypothesis list to check on the fifth step (EDA). Then apply data transformations on the required columns.
#  Step 04. Data Filtering:

Filter rows and select columns that do not contain information for modelling or do not match the scope of the business, such as predict sales for a closed store.
