# Bitly User Activity Data Transformation
Transforming Bitly User activity dataset into readable tabular data from `json` file to a `DataFrame` to a `CSV` eventually.

### Objective:
-  Data Transformation
-  Data Cleansing

### Tech Stack:
- Python
- Pandas ***Library***
- json ***Library***

### Dataset:
- `usa.gov_click_data_1.json`

***To download the dataset make sure to check the `dataset` folder in the `repository`***

### Dataset Description:

|key| description |
|---|-----------|
| a|Denotes information about the web browser and operating system|
| tz | time zone |
| r | URL the user come from |
| u | URL where the user headed to |
| t | Timestamp when the user start using the website in UNIX format |
| hc | Timestamp when user exit the website in UNIX format |
| cy | City from which the request intiated |
| ll | Longitude and Latitude |


**To check full project** either check `Bitly_Data_Transformation_Pandas.ipynb` in the `repository` or [Bitly_Data_Transformation_Pandas.ipynb](https://github.com/mustafaa7med/Bitly-User-Activity-Data-Transformation-Pandas/blob/main/Bitly_Data_Transformation_Pandas.ipynb)
