# INFO 7374 Algorithmic Digital-Marketing Assignment 2 Team 7

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

* Filtering: Since the large dataset is divided into different columns, filtering a laptop on the basis of different parameters gets very simple and gives the customer a wide range of filtering options like on the basis of CPU brand, GPU brand, Display resolution, Screen Size, RAM and Operating System.

* Missing Value Handling: The missing values on the given datasets have been handled by using trifacta by filling the numerical values by taking the mean of the rest of the values. We encountered one missing value on the column "Price_in_USD" and that was resolved by doing the "replace missing" transformation.

* Deriving additional columns from existing datasets: In the initial dataset, we had column called "nama_produk" which had the detailed specification of the laptops. We turned that column into 7 different columns using Pandas, namely:


1. Model_Name
2. CPU
3. Display_Size
4. Operating_System
5. RAM
6. GPU
7. Screen_Resolution

* Cleaning: To remove special Characters like ' " ' and blank spaces, "Replace text or pattern" transformation on Trifacta has been employed.
