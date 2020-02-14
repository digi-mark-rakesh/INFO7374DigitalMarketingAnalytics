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

Promotion:

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
