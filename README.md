# Matplotlib_challenge


Pymaceuticals


	Using the Matplotlib and Pandas python libraries, I manipulated data related to the animal testing of cancer medicines and created several visualizations. 
	The data set consisted of rows containing the weights and tumor volumes of mice at specific timepoints throughout testing. As a result, there were many rows for each mouse tested, and this had to be overcome in order to perform certain analyses. I limited the data set to a specific mouse or drug in order to create visualizations specific to that mouse or drug. Often iterating through the entire data set using the ‘.loc’ function would also allow me to limit the data presented. 
	The data was often asymmetrical across the different tests, as some drugs had smaller samples than others, and some mice did not live through the entire duration of testing and could not be accounted for at the later time intervals. A visualization of the mortality rate of mice would be a good addition to this file. 
	The Capomulin treatment appeared to be the most effective, as the tumor volume of mouse s185 decreased drastically over the time period, and the tumor volume of mice tested with Capomulin clustered around 32-40 cubic millimeters, much lower than those of other drugs in the experiment. Weight also positively correlated with tumor volume, with a correlation coefficient of .84, so it is likely the two are dependent.
