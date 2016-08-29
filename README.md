# tlrestaurant

#Summary

Data has been extracted and imported into Excel for further parsing and statistical analysis per week number (from "$date).
Then, a logarithm model (again, via Excel) was created for "Average Ticket" and "Attendees Count" based on week number.
The extrapolated values for the next week were used to calculate the sales forecast.



#Artefacts used to analyse TL restaurant data

filter.cmd:  data extracter 
date.txt: intermediate file
valorTotal.txt: intermediate file
TL.xls: analysis workspace
  worksheet .ExtractedData: constains data parsed via Excel and basic statistical info
  worksheet .Calculus: analysis and model
Step by Step: A detailed description of the solution.
