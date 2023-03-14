# Electric-Car-Population
Electric automobiles have grown in popularity over the last decade as more people appreciate the need to lower carbon emissions and battle climate change. Electric vehicles are a more environmentally friendly and sustainable alternative to typical gasoline-powered automobiles, and their popularity has been aided by government incentives and technological breakthroughs. Consequently, the number of electric vehicles on the road worldwide has continuously increased, and this trend is projected to continue in the coming years.

**About the dataset**

According to the Electric Vehicle Population Data - Catalog dataset from Kaggle(https://www.kaggle.com/datasets/ssarkar445/electric-vehicle-population),there are presently Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered via the Washington State Department of Licensing (DOL). Furthermore, the open data source includes a dataset that categorizes cars as Clean Alternative Fuel Vehicles (CAFVs) or electric-only vehicles depending on the fuel need.
The dataset has several columns:
- Vehicle Identification Number (VIN); is a unique code assigned to every vehicle manufactured since 1981.
- Country, City, State, Postal code; the registered owner resides
- Model Year, Make, and Model; determined by decoding the Vehicle Identification Number (VIN).
- Electric Vehicle Type; This distinguishes the vehicle as a battery or a plug-in hybrid.
- Clean Alternative Fuel Vehicle; This categorizes vehicles as Clean Alternative Fuel Vehicles (CAFVs) based on the fuel requirement and electric-only range
- Electric Range; Describes how far a vehicle can travel purely on its electric charge.
- Base MSRP; This is the lowest Manufacturer's Suggested Retail Price (MSRP) for any trim level of the model in question.
- Legislative District; The specific section of Washington State that the vehicle's owner resides in, as represented in the state legislature.
- DOL Vehicle ID; Unique number assigned to each vehicle by the Department of Licensing for identification purposes.
- Vehicle Location; The center of the ZIP Code for the registered vehicle.
- Electric Utility; This is the electric power retail service territory serving the address of the registered vehicle. All ownership types for areas
- 2020 Census Tract; The census tract identifier is a combination of the state, county, and census tract codes as assigned by the United States.


**ESSENTIALS OF DATA CLEANING**

Businesses that desire to dominate their markets must understand where to obtain the data they want and how it all relates. However, they must ensure that their data sets are clean before beginning to analyze data. Data cleansing is undoubtedly essential, and smart businesses are aware of this. Large amounts of data, sometimes stored in hard-to-use forms, are typically included in datasets. Data analysts must first ensure that the data is adequately equipped and follows the established set of criteria. The greatest problems are data scarcity and inconsistent formatting, and data cleaning addresses these issues. Data cleaning is the process of locating faulty, incomplete, inaccurate, or irrelevant data, fixing the flaws, and ensuring that any future instances of these problems will be automatically corrected. Data analysts spend 60% of their time organizing and cleaning up data, according to Appen!


Here are a few of the most popular stages and techniques for data cleaning: • Dealing with missing data • Standardizing the process • Validating data accuracy • Removing duplicate data • Handling structural errors • Getting rid of unwanted observations
I took some steps to clean this dataset Firstly, I alighted all using Ctrl+A and converted the dataset to a table format using Ctrl+T and formatting the table.

![image](https://user-images.githubusercontent.com/124578882/225068061-6c43899e-ffeb-417f-84b6-d80336f906c9.png)

Dataset in excel

**Data Visualization**
The are over 2000 Electric vehicles in population across 47 different countries, amongst 30 manufacturers.

![image](https://user-images.githubusercontent.com/124578882/225068350-083404f0-d183-4bca-b8ae-3790f461d731.png)


**Count by Maker**
Tesla a top leading technological company also takes the lead in producing the highest number of Electric Vehicles. Other top Electric Car Makers (Manufacturers) include; Nissan, Chevrolet, Ford, and Toyota.

![image](https://user-images.githubusercontent.com/124578882/225068386-2cef574c-4e98-4dde-a111-b0a6be6eed78.png)


**Vehicles by Country**
Out of over Forty (40) countries where registered owners reside; King, Snohomish, Pierce, Clark, and Thurston are the top five countries where registered electric vehicles owner resides.

![image](https://user-images.githubusercontent.com/124578882/225068414-bb37aeae-0c05-4d4e-b446-454ffe5a05c8.png)


**Most popular city by electric car:** Different cities among over 200 cities where the registered owner resides. Seattle, Bellevue, and others take the lead with about 18%, 5%, and 77% respectively of the total cities in over 47 countries.

![image](https://user-images.githubusercontent.com/124578882/225068458-0dc8cb7b-c7d0-46bc-a023-f44889822505.png)


**Electric Vehicle Type by Maker:** Electric Vehicles are majorly categorized into two. Tesla, Nissan, Chevrolet, Ford, and Toyota produced about 200k, 6000, 5000, 3000, and 2000 respectively for both vehicle types.

![image](https://user-images.githubusercontent.com/124578882/225068531-23aa03ca-5cbf-4006-9189-7c267ee29740.png)


**Electric Vehicle Type:** Electric Vehicles are majorly categorized into battery and Plug-in Hybrid. Due to gradual technological 
advancement battery electric vehicles are 77.06% off while Plug-in Hybrid Vehicles which are just been introduced take 22.94%.

![image](https://user-images.githubusercontent.com/124578882/225068574-9e6a2bbd-aee7-42ab-84e6-c56347f90925.png)


**Maker by Model Year and Model:** Different manufacturers produce various types of vehicle models during the years under review. In 2020,2021,2022 had two most produced different models (Model 3 and Model Y).

![image](https://user-images.githubusercontent.com/124578882/225068620-b8c3f2fe-68a9-408f-92f3-26fc6524d95e.png)


**Recommendation:** More electric vehicles should be manufactured across the globe, so as to reduce air pollution caused by exhaust from diesel and gasoline vehicles used earlier before the invention of electric cars.


![image](https://user-images.githubusercontent.com/124578882/225068660-8fc0ba00-082b-4c58-8624-7c48bd3d10d8.png)


**In conclusion:** Tesla, an America based takes about 60% in the production of different types of electric vehicles i.e Battery and Plug-in Hybrid.
