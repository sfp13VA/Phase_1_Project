# Business Understanding
Our company is expanding into the shipping industry, necessitating purchasing and operating airplanes for shipping cargo purposes. Since we are unfamiliar with the potential risks of different types of aircraft, here we are looking to determine which aircraft present the lowest risk in order to begin the new shipping endeavor.

# Data Understanding
Here we are working with a dataset provided by the National Transportation Safety Board which includes aviation accident data from 1962 through 2003 about civil aviation accidents and selected incidents in the United States and international waters. Every incident has a unique event ID, and the data files provide the dates and types of each event, as well as other pertinent safety information (e.g. aircraft make and model, number of injuries).

## Data Preparation
I make the data easier to work with by dropping unnecessary columns which contain irrelevant information, as well as records/rows relating to obviously irrelevant incidents (ie. since we are interested in the safest airplanes only, we are removing ameteur built aircraft as well as things like helicopters, parachutes, etc.)

# Exploratory Data Analysis
I analyzed the data in order to find aircraft features which might correlate with number of incidents, which provides a useful tool in order to define saftey.

![image](https://github.com/user-attachments/assets/091bc56c-73fc-4d8b-899f-fe7bc52b2bac)

![image](https://github.com/user-attachments/assets/ad4b1d7e-f907-4b1a-bcb7-b28d48945d53)

![image](https://github.com/user-attachments/assets/8052608d-2e71-474f-b88d-ceb58766dfe3)


# Conclusion

1) Aircraft with multiple engines are more reliable.  Overwhelmingly, aircraft involved in incidents are single engine aircraft.
2) Turbo fan engines appear most reliable, though avoiding reciprocating engines is most crucial when it comes to engine type.
3) Boeing and Airbus made aircraft are safest due to their overall reliability.
   
## Limitations
The dataset outlines "selected" incidents only and does not include information on the total number of aircraft or total flights, leaving room for more precision using a more complete dataset.

## Recommendations
1) Aircraft with multiple engines are recommended, as single engine aircraft are overwhelmingly involved in more incidents.  2) Non-reciprocating engines are recommended, as reciprocating engines are involved in more incidents.  3) Boeing and Airbus made aircraft are specifically recommmended for safety.

## Next Steps
Evaluating cost and other variables will be crucial, such as ease of service and repair, as well as ability to modify for business purposes, since these considerations will factor into choosing aircraft to purchase.
More information included in this Presentation and Notebook: https://github.com/sfp13VA/Phase_1_Project/blob/main/presentation.pdf
https://github.com/sfp13VA/Phase_1_Project/blob/main/notebook.pdf
