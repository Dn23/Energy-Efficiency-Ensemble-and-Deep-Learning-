# Energy-Efficiency-Ensemble-and-Deep-Learning-
Data Set Information:
We perform energy analysis using 12 different building shapes simulated in Ecotect. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. We simulate various settings as functions of the afore-mentioned characteristics to obtain 768 building shapes. The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is rounded to the nearest integer.

Attribute Information:
The dataset contains eight attributes (or features, denoted by X1...X8) and two responses (or outcomes, denoted by y1 and y2). The aim is to use the eight features to predict each of the two responses. 

Specifically: 
	X1	Relative Compactness 
	X2	Surface Area 
	X3	Wall Area 
	X4	Roof Area 
	X5	Overall Height 
	X6	Orientation 
	X7	Glazing Area 
	X8	Glazing Area Distribution 
	y1	Heating Load 
	y2	Cooling Load
For this project I used some base Regression models and ensemble and compare r2_score of y1 and y2. 
Adding cooling load and heating load can define the overall load of the apartment. I Studied the trend of overall load and divided it into three classes, low efficient, high efficient and average efficient,then trained a deep learning model to predict the label. 
