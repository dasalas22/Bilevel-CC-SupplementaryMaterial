This file contains the description of the supplementary material for the numerical experiments.


********INPUTS**********
Matrix_alpha.csv -> Matrix whose rows represent each of the experimentation cases (50 cases) and columns represent each one of the facilities. The components of this matrix (alpha_{js}) represent the inconvenience due to congestion in facility s, for case j. 

Matrix_preference/Matrix_preference_case_$j$.csv -> Matrix whose rows represent each of the drivers and columns represent each of the facilities. The components of this matrix (p_{is}) represent the preference of driver i regarding charging their car at facility s, at case j.


********OUTPUTS********
Folders:
Results_MixedConfigguration 
Results_UpperConfiguration

********

Results_MixedConfigguration  --> Folder with the results found for the Mixed-Configuration problem, which have been divided as follows:

*Facilities_Mixed.csv -> Matrix whose rows represent each of the experimentation cases (50 cases) and columns represent the facilities under consideration. Each component of this matrix represents whether a facility was built; that is, if a facility was built, its value will be 1, and otherwise, it will be 0.

*Drivers_per_facility_Mixed.csv -> Matrix whose rows represent each of the experimentation cases (50 cases) and columns represent the facilities under consideration. Each component of this matrix represents the number of drivers using facility s (s=1,...,10) to charge their car.

*Performance_Mixed.csv -> Matrix whose rows represent each of the experimentation cases (50 cases) and contains two columns, Optimality Gap and Time Execution. This matrix shows the gap and time execution for each experimentation case.

*Values_Mixed.csv -> Matrix whose rows represent each of the experimentation cases (50 cases) and contains three columns, Profit of the Suppliers, Benefit of the Followers, and Social Welfare. Therefore, for each case, the separated value of maximizing Social Welfare  is shown ("Benefit of the Followers" + "Benefit of the Followers" = "Social Welfare").


*****************************
The same file description above applies for the Upper-Configuration problem, whose files are in the Results_UpperConfiguration folder