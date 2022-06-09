# Personal-MachineLearning-Classification-AstralClassification


Results:
- 100% = Random Forest Classifier
- 94% = Logistic Regression Classifier
- 92% = SVM Classifier


Kaggle Description:
Dataset found on Kaggle: https://www.kaggle.com/datasets/deepu1109/star-dataset

Features:
Absolute Temperature (in K)
Relative Luminosity (L/Lo)
Relative Radius (R/Ro)
Absolute Magnitude (Mv)
Star Color (white,Red,Blue,Yellow,yellow-orange etc)
Spectral Class (O,B,A,F,G,K,,M)
Star Type (Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence , SuperGiants, HyperGiants)

Purpose:
The purpose of making the dataset is to prove that the stars follows a certain graph in the celestial Space ,
specifically called Hertzsprung-Russell Diagram or simply HR-Diagram
so that we can classify stars by plotting its features based on that graph.

Data Preparation:
The dataset is created based on several equations in astrophysics. They are given below:
- Stefan-Boltzmann's law of Black body radiation (To find the luminosity of a star)
- Wienn's Displacement law (for finding surface temperature of a star using wavelength)
- Absolute magnitude relation
- Radius of a star using parallax .
The dataset took 3 weeks to collect for 240 stars which are mostly collected from web.
The missing data were manually calculated using those equations of astrophysics given above.
