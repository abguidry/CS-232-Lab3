# CS-232-Lab3
## Intro
This lab code takes a (.csv) list of names and associated addresses and sorts then and outputs a cleaner version similar to what one would list on a contact card.
## Installation
1) To install this program simply:
1) Click the "Clone or Download" prompt
2) Click the "Download ZIP" prompt
3) Choose your desired install location (if not prompted it will automatically download to the User's Downloads folder)
4) Locate your download
5) Extract the "CS-232-lab3-master" folder from its (.zip) folder
6) Move the "lab3b" to the desired directory on your computer
7) Double click "lab3b.jar" to run
## Operation
In general the program will sort a list of comma seperated values (csv) into an array using hashmaps. It will then loop through to the end of the provided CSV to ensure that everyone is matched with their address. The program starts by setting up a main which instanciates an ArrayList<String> for both key names and any subsequent values. It then uses a hashmap to hold both of the ArrayList values. The program then opens the given CSV file using a "scanner in" and proceeds to define the already instanced keys. The program then uses a while loop to create new maps for each row that it has read. It will then uses a simple for loop to output each individual name and address based on the Keys defined in the CSV.
## Acknowledgements
This code was written for a lab in my CS 232 class. Skeleton code was written by Jay Snellen.
