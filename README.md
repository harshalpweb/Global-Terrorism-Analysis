# Book-Recommendation-System
## In this project, we present the analytical results obtained from digging the data from Global Terrorism Database. The main purpose is to visualize terrorist activities and make it available to users in an easy-to-understand way. This document is designed to contain a collection of various analytical and visual interpretations, patterns and trends in it.
#### Tags: Exploratory Data Analysis, Data Science, Machine Learning

#### Co-created by [Ayush Jain](https://github.com/ayushjn1995), [Sarvesh Kumar](https://github.com/sky309), [Prahat Dixit](https://github.com/prapcode) and [Harshal Pawar](https://github.com/HarshalPawar88)
#### Links:   
Project Presentation: [Slideshow](https://docs.google.com/presentation/d/19mIPH-6ZdG2zmJsIstJ6-Tz3Z23K7I-2dMFYBfkSnQk/edit?usp=sharing)   Dataset: [GlobalTerrorism](https://drive.google.com/file/d/1WDsKsC8pNNB6EcGsLXTEEb5lh4oelHgs/view?usp=sharing) 
Project File: [Colab Notebook](https://github.com/HarshalPawar88/Global-Terrorism-Analysis/blob/main/CH_%7BFinal_Notebook%7D%7BTeam_Time%7D_%7BGlobal_Terrorism_Analysis%7D_Capstone_Project.ipynb) 
## Project Summary:
Terrorism is a major obstacle to world peace. Terrorism is very commonly ignored by people who are not directly affected by accidents and the damages. Reducing terrorism is the major pain point for the governments in the every country of the world and hence, it’s very important to do a deep analysis on the datasets of the global database to provide valuable insights for the prevention of the terrorism in the World. In the report we have visualized some important trends adopted by the big terrorist groups in the world and India, most affected countries and the cities of India and many other observations. 

<h2><b>Our Approach Towards This Project</b></h2>
<h3><b>Data Preprocessing:</b></h3>  Data preprocessing is the first step to be done after collecting the data. Data preprocessing methodology helps in converting this raw data into a more meaningful, focused, interpretable and readable format. The following are the steps used in this project as a part of data preprocessing methodology:

<h4><b>o Data Cleaning:</b></h4> Process of handling inconsistencies in data. In terrorism dataset, there are numerous fields like motives or responsible organizations which are missing either due to information not available or that field was not relevant for that specific event. Fields like summary, claim_mode, claimmode_txt, guncertain, 'nperps' etc. are removed since they are not relevant to the analysis of this project. Fields like weapsubtype2, and weaptype3_txt have more missing values than valid entries. Hence such fields are also removed to reduce complexity.

<h4><b>o	Data Integration:</b></h4> In this step, conflicts among data are resolved. Different representations of the same data such as multiple subcategories of weapon type (weapsubtype1, weapsubtype2, weapsubtype3) are put together to avoid confusion and duplications. Fields with one-to-one correspondence like country_code and country_txt are mapped to avoid any conflicts.
<h4><b>o	Data transformation:</b></h4> Here data aggregation, generalization, and normalization are performed. Dataset has nkill and nwounds which can be shown as a single attribute by the name of the Damage in the analysis. This technique reduces the total number of attributes in the dataset and hence reducing the variability in the data.


## <b>Conclusion</b>
1. Maximum number of attacks are 16903 across the world in the year 2014. 
2. Taliban group has executed the maximum number of attacks i.e 7360 in the last two decades. 
3. Asia is the most affected region by terrorist attacks with Iraq having maximum number of attacks.
4. Bombing/ Explosion are the most preferred attack type and the same did the maximum damage too. 
5. 2016 has seen the maximum number of attacks in India but the maximum number of people were killed in 1992. 
6. In India, J&K has been the most affected state and Srinagar having the highest number of attacks i.e 749



