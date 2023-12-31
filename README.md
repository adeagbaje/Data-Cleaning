# Data-Cleaning

Data is omnipresent, yet in its raw form, it often lacks suitability for extracting insights to address business challenges. Consequently, upon data collection, it becomes crucial to undergo a cleaning process. Ensuring data cleanliness enhances overall productivity and facilitates the highest quality of information for decision-making. I embarked on a Data Cleaning Project using Power Query. Key tasks in this project encompassed organizing it into a table with a minimum of 7 columns, identifying the top 5 prevalent ages, determining the bank with the largest transaction share, and visualizing the distribution of transaction channels.

The overall goal is to have clean data that is fit for further analysis, which will aid us in drawing accurate and meaningful insights from it.

Below is the data in its raw form. The raw data is quite messy, making it Ideal for a data-cleaning project. The data is in a CSV file format that consists of 127 rows and 3 Columns.

# About the dataset
The dataset is bank transaction data in CSV https://drive.google.com/file/d/16hQw9cd3M3blLVUcziDwlccWMMzP2-lv/view

![The data in it's raw form](https://github.com/adeagbaje/Data-Cleaning/assets/65424574/7414ac3a-2d0a-40c3-9152-e9a7e1d5a98b)


# Data Cleaning
To begin the cleaning process, the dataset was imported into Microsoft Power BI. Having imported the data, the transformed and various techniques were used to organize it into a table with a minimum of 7 columns. The formulas and methods used to clean the data:

- =Text.Select([Text String],{"A".."z", "0".."9"}.
- Replaced the blank cells with null
- Ensured that each column has the correct data type and name
- I split most columns with a delimiter,
- and I also used the transform tab with the replace values functions.

Below is the data after cleaning
![After Cleaning the data](https://github.com/adeagbaje/Data-Cleaning/assets/65424574/e841a240-5c81-4ba1-8ae8-a1483502110f)

# Data Visualization

The process ended with a clean dataset having 127 rows and 10 Columns. I identified the top 5 prevalent ages, determined the bank with the largest transaction share, and visualized the distribution of transaction channels.

Below is the Power BI report published to the Power BI service https://app.powerbi.com/reportEmbed?reportId=2075787e-b3fe-4967-a1b2-823d4b5169ee&autoAuth=true&ctid=a779535f-7869-42f5-ab18-44eb4d83e02c

![Report](https://github.com/adeagbaje/Data-Cleaning/assets/65424574/22ca153f-9864-486f-b691-423ca4fde46b)




