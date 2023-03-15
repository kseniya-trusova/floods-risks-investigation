# Description
This repository is the contribution to the Reducing Flood Risks in Belgrade Area through AI Solutions challenge organized by Omdena Serbia Chapter.

General project link: https://github.com/OmdenaAI/belgrade-serbia-reducing-floods

The repository contains the EDA notebook.
# Challenge details
The task was to provide an AI predictive system, which can give a possibility for floods, based on the current levels of the water, precipitation, and other parameters. For the training, planned to use the historical hydrometeorology data of the Belgrade area, focusing on time fragments of recent floods in the last 100 years.

4-week project goals were the following:
1. Collect Datasets with historical hydrological data.
2. Data Processing
3. Machine learning process
4. API for a predictive service for floods

As a result, the data 2000-2022 was collected by the team. 

The Belgrade area includes three water stations on two rivers Danube and Sava. They are Zemun, Belgrade and Pancevo. Belgrade Sava checkpoint is in the center of Belgrade, Danube Zemun checkpoint is upstream while Danube Pancevo is downstream, all three taking results at the same time.
# EDA
The file includes the exploratory data analysis of the whole collected dataset and two huge floods in the Belgrad area.

General findings:
1. Water level increases from February and decreases from July. The water level remains high between these two months.
2. Zemun station weekly water level seems to have periodical water consumers.
3. Water levels do not depend on environmental features such as precipitation, pressure, temperature, humidity and wind speed. Water levels have relatively strong correlation between each other and flood alerts (levels are provided by the Republic Hydrometeorological Service of Serbia).
4. The investigations of particular floods gave different results than general feature investigation. The temperature has some significant correlations with the water levels. The combination of dramatic feature changes results in water level increasing.

Some assumptions could be made here. Probably, the water consumption on the Zemun station has some impact on the Belgrad and Pancevo stations water levels. Water extraction happens at the beginning of a month. The flood in May 2014 happened in the middle of the month while the flood in June 2019 happened in the beginning of the month. In the second case, the water level decreased faster.

Therefore, building the water extraction infrastructure could be more efficient than just flood prediction, because floods damage the economics anyway. The project results could be used to construct effective water extraction infrastructure.  
