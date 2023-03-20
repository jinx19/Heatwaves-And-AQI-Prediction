# AQI and Heatwaves Prediction
This project aims to predict the Air Quality Prediction (AQI) and Heat waves for 4 cities:  
🌇 Warangal  
🌆 Nizamabad   
🌃 Khammam  
🌅 Karimnagar   
  
  The project utilizes data from NASA MERRA-2, WHO Population Dataset and TS-NPDCL datsets.  
    
### Code Folder  
The **Code** folder contains all the codes used in this project. There are 3 sub-folders here:  
#### 📊 Data Cleaning  
* The 'Data Cleaning' folder contains another folder **MERRA-2 Dataset**.  
* It contains all the data from NASA MERRA-2 Dataset for the four cities.  
* **MERRA-2.ipynb** file is present in the Data Cleaning folder.  
* It is a Jupyter Notebook containing Data Cleaning and Data Analysis Python Code for MERRA-2 Dataset.  
* This .ipynb file gives the **MERRA-2.csv** file as output and is stored in the Data Cleaning folder.  

####  📈 Interpolation  
The **Interpolation** folder contains 2 sub-folders:  
* **AQI**: Contains 7 .csv files which contain AQI information of Telangana.  
* **Energy**: Contains 48 files from January 2019 to January 2022 monthly Energy Data from TS-NPDCL.  
* **Interpolation.mlx** file is present in the Interpolation folder.  
* This file is a **MATLAB** file which contains all the MATLAB code in .mlx format. 
* It produces two files **AQI.csv** and **Heatwaves.csv** as output.  
* These files are used as input to the ML models.  
* **Interpolation.pdf** file is also here, which is a .pdf format of the .mlx file, incase if MATLAB is not available.  
* The Interpolation.mlx file deals with **Interpolation**, **Data Handling** and **Smoothening**.  

#### 🧠 Models  
The **Models** folder contains two sub-folders:  
* **AQI Prediction Model.ipynb**: Jupyter Notebook containing python code for AQI ML Model.  
* **Heatwaves Prediction Model.ipynb**: File containing python code for Heatwaves Prediction ML Model.  
* The **AQI.csv** and **Heatwaves Dataset.csv** files are the outputs from **Interpolation.mlx** file and are used to train the models.  

#### d95db3a3-7ed5-4f06-b700-86dfdab7d05a  
https://sonarcloud.io/summary/overall?id=examly-test_d95db3a3-7ed5-4f06-b700-86dfdab7d05a  
