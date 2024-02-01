# A Fresh Kitchen way to combat the diabetes burden in Mexico

## Abstract

Noncommunicable diseases are the leading causes of disability in Mexico, specifically, diabetes. Creating change in the diabetic culture will take time, however, targeting the restaurant capital market can be a way to start. [Fresh Kitchen](https://www.eatfreshkitchen.com/) is an amazingly delicious and nutritious healthy fast-food chain in Florida that delivers hormone free, fresh food “as quick as you can point”. By identifying the density of diabetes and population in Mexico, Fresh Kitchen will have strategic locations of where to build their restaurants to help counter the rising diabetes rates. After obtaining an understanding of the demographics and health conditions of the 31 federal states of Mexico using Google Sheets and Tableau, 5 states that had the highest density of obesity prevalence and diabetes deaths per capita were identified: Campeche, Durango, Chihuahua, Jalisco, Nayarit.

To dig deeper into this project, please see the data and presentation slides within this repository.

### Design  
By identifying the density of diabetes and obesity in Mexico, Fresh Kitchen will have strategic locations of where to build their restaurants to counter the rising diabetes rates. 

### Data  
Firstly, demographic data of each Mexican state will be explored from 2020 National Institute of Statistics, Geography and Informatics (INEGI) Population and Housing Census data. [Variables such as gender, age, poverty level, and average years of schooling for 15+ year olds of each Mexican state](https://www.inegi.org.mx/app/tabulados/interactivos/?pxq=Poblacion_Poblacion_01_e60cd8cf-927f-4b94-823e-972457a12d4b&idrt=123&opc=t). Secondly, we will use [Mexico’s National Survey of Health and Nutrition (ENSANUT)](https://en.www.inegi.org.mx/programas/ensanut/2018/#Tabular_data) 2018 data to quantify the frequency and trend of a variety of health and nutrition conditions, such as currently living with diabetes, overweight and obesity prevalence, physical activity, dietary patterns. This national survey was conducted from Jul 2018 - Jun 2019 by the Mexican government and is performed every six years. Data gleaned from this survey data will exclude pregnant women and those <18 years of age. Thirdly, the mortality rates due to diabetes in the year 2020 were obtained from the [INEGI Mortality Statistics](https://en.www.inegi.org.mx/app/tabulados/interactivos/?pxq=Mortalidad_Mortalidad_04_aa50eec5-79fe-45a7-aee2-a2d7ec0feeba&idrt=127&opc=t).

### Algorithms  
A variety of data cleaning methods were employed to accomplish the above tasks. Additionally, many features were engineered such as diabetes death rate per 100,000 individuals aged >= 20 years of age for each of the 31 Mexican states. Percentage of male and females were engineered. Longitude and latitude data had to be completely restructured for suitable geographic analysis in Tableau.

### Tools  
Google Sheets and Tableau were used for this entire project.

### Communication  
I completed a 5-minute presentation of my findings; slides and visuals for this project are included in this repository. A dashboard of [demographics](https://public.tableau.com/views/MexicoDiabetesBurdenI/Demos?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) and [obesity and diabetes density](https://public.tableau.com/views/MexicoDiabetesBurdenII/Diabetes?:language=en-US&:display_count=n&:origin=viz_share_link) by county were created.

<img width="656" alt="Screenshot demographics" src="https://user-images.githubusercontent.com/80511410/196418948-da5707f1-ada5-4fc8-b968-5bbf59e2d559.png">


<img width="937" alt="Screenshot density locations" src="https://user-images.githubusercontent.com/80511410/196419534-2f35cff2-5dbe-4072-8b46-c17f4d559510.png">

