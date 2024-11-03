# Club-Organizing-System
This project is a Club Organizing System written in C++ designed to help organize and calculate the costs for outings with a group of senior citizens. The program calculates the total cost of an outing based on the number of participants, taking into account various costs like coach hire, meals, and tickets. It also allows for additional members to join and calculates profit or loss based on payments made.

Features
Calculate Outing Costs: Based on group size, calculates total outing costs including coach hire, meals, and theater tickets.
Individual Payment Collection: Collects and records payment from each participant, including additional members who may join later.
Profit/Loss Calculation: Calculates profit or loss based on total collected payments versus the calculated outing costs.
Additional Carers: Includes the option to add carers based on the group size and calculates their cost in the total budget.
How It Works
Group Size & Costs:

10-16 members: Coach cost is $150, meal cost is $14.00 per person, and theater ticket cost is $21.00 per person.
17-26 members: Coach cost is $190, meal cost is $13.50 per person, and theater ticket cost is $20.00 per person.
27-36 members: Coach cost is $225, meal cost is $13.00 per person, and theater ticket cost is $19.00 per person.
Cost Per Person & Carer Cost:

Calculates the cost per person and adds an additional amount for carers based on the group size.
Data Input for Each Citizen:

Prompts for each participant’s name and payment, including optional additional participants.
Profit/Loss Calculation:

Compares total payment collected from participants against the outing costs and determines whether there was a profit or loss.
Code Structure
group1(), group2(), group3(): These functions calculate costs for groups of 10-16, 17-26, and 27-36 participants, respectively.
in_out(): This function handles participant data input, payment collection, additional participants, and profit/loss calculations.
main(): The main driver function that controls the program flow and prompts user input.
Example Usage
plaintext
Copy code
***Welcome to the Club Organizing System***

Enter the number of people going on outing including carers: 15

***Orignial cost for outing***
The cost of hiring coach for 10-16 senior citizens is 150$.
The cost of meal per person is 14.00$.
The cost of theatre ticket per person is 21.00$.

***Total cost for outing***
The cost of hiring coach is: 150$
The cost of meal is: 210$
The cost of theatre ticket is: 315$
The total cost is: 675$
The cost per person is: 45$
The cost for taking 2 carers on outing is: 90$

***Enter the data of Citizens going on Outing***

Enter the name of citizen 1: John
Enter the payment 1: 45$

Enter the name of citizen 2: Jane
Enter the payment 2: 50$

Are there any additional citizens?
Enter the choice(yes/no): no

***PAYMENT Detail and Profit/Loss***

The total payment paid by citizens:  675$
The original cost is: 675$
The carers cost is: 90$
The loss is: 90$
Compilation and Execution
Compile the Program:

bash
Copy code
g++ -o club_organizing_system main.cpp
Run the Program:

bash
Copy code
./club_organizing_system
Requirements
C++ compiler (e.g., GCC)
License
This project is open-source and available under the MIT License.
