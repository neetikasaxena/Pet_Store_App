# Pet_Store_App
Designed the Pet Inventory Application by using the Object-Oriented Programming concept.
## Pet Application
The base class Pet has the following attributes:
pet’s name (String)
date of birth (date), 
birth weight (float), and 
owner (Person). 
The child classes Mammal, Fish and Amphibian that inherit from Pet and have the following additional properties 

•	Mammals - litter size (int), hasClaws (boolean)

•	Fish - scale condition (String), length (float)

•	Amphibian - isVenomous (boolean). 

      Additional Feature
### Current weight is calculated as follows:

•	Mammal: Weight increases by 8% every 50 days for the first 300 days. Weight is constant after that. Assume that the increase occurs on the 50th day only.

•	Fish:  Weight increases by 4% every 90 days for the first 360 days and then stays constant. Assume that the increase occurs on the 90th day only. 

•	Amphibians: Weight increases by 5% every 120 days for the first 360 days and then increases by 3% every 120 days for the next 240 days and then stays constant. Assume that the increase occurs on the 120th day only.

Used Exceptional Handling to validate user input for date of birth and weight.  If the user enters a non-numeric value for either, or if the month or day for the date of birth is an invalid value, print a message and exit the program.
### Dates: 
The user should enter year, month and date (in that order) separated by commas.  If the year is not 2 characters long, raise a ValueError.  Otherwise prefix ‘20’ to the year.  This has been converted to a 4-digit numeric value later. 

