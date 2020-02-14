# INFO 7374 Algorithmic Digital-Marketing Assignment 2 Team 7

Claat doc link: https://docs.google.com/document/d/1OA6tF0K02O28d9GoZB0An2jVZyrtToUK8hSOmgfV_gI/edit#

We were given datasets from Kaggle from an Indonesian E-Commerce Website called jd.id which sells Laptops online.

## Dataset Description

The initial Dataset had the following columns:

* page
* Merek_Laptop
* Nama_Laptop
* Harga
* Link_Produk


## Case Study

1. As an Algorithmic Marketing Analyst working for Maketa Analytics, following is the analysis of the sample dataset one the basis of different themes:

Pricing: jd.id has laptops that are being sold at prices as low as $270 all the way up to $3000, thus indicating that have entry level and budget laptops as well as high-end gaming laptops.

Promotion: The website has brands with as many as 600 different laptops being sold whereas some brands have hardly 3 models available. Because of this, a customer will automatically be driven towards the more popular brand.

2. We have used tools such as Pandas, XSV and Trifacta for cleaning as well as transformation of the dataset. Below is a brief description of the tools and how have they been used.

* To join the datasets, Trifacta was used by performing the transformation called "Union Datasets". This allows us to add as many datasets as we want.

* Filtering: Since the large dataset is divided into different columns, filtering a laptop on the basis of different parameters gets very simple and gives the customer a wide range of filtering options like on the basis of CPU brand, GPU brand, Display resolution, Screen Size, RAM, ROM and Operating System.

* Missing Value Handling: The missing values on the given datasets have been handled by using

* Filtering: Since the large dataset is divided into different columns, filtering a laptop on the basis of different parameters gets very simple and gives the customer a wide range of filtering options like on the basis of CPU brand, GPU brand, Display resolution, Screen Size, RAM, ROM and Operating System.

* Missing Value Handling: The missing values on the given datasets have been handled by using Trifacta using the transformation "Replace Missing", there in by entering custom value. We solved a problem of having to add a missing value in the column "Price_in_USD".

* Deriving additional Columns from existing datasets: We used Pandas to split the column "Nama_Produk" of the initial dataset in the following 7 columns:

1. Model_Name
2. CPU
3. Display_Size
4. GPU
5. Screen_Resolution
6. Operating_System
7. RAM

* Cleaning Datasets: "Replace Text or Pattern" transformation using Trifacta was used to free the data from white spaces and special characters like ' " ', hence cleaning the dataset. Also all the string were converted to Uppercase again using trifacta.

## Dashboads

Once the Data is clean with all the Exploratory Data Analysis done using Pandas, XSV and Trifacta, following steps are performed on Salesforce Einstein Analytics:

1. Create a new app

2. Create a new dataset inside the app and upload the .csv file after changing the column "Price_in_USD" to Measure

3. Create a dashboards inside the same app


* For our dataset, all the columns except "Price_in_USD" are dimensions.

* The dashboard will most likely be used by the E-Commerce website to look at the various ranges of products being sold by them to create new business strategies. Also the manufacturers of the laptops can also look into this to get an estimate of where they stand in the competition.

* There are various values that are being generated, such as:

1. The visualisation shows the number of laptops on sale in the eCommerce Site by a distinct company.
2. The dashboard can be used to infer which CPU + GPU brand is the most popular combination chosen by the brands.
3. The range of price of laptops offered by different brands of laptops
