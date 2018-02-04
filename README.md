# Project Title
Inventory Management System
Description:
Mr. X owns a store that sells almost everything you think about. Now he wants a inventory management system to manage his inventory. Mr. X feels that controlling his inventory through SMS from his mobile will be revolutionary. So as a prequel, he decides that he wants a system that accepts one line commands and performs the respective operation.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
See deployment for notes on how to deploy the project on a live system.
1) Method 1
	a) Open .bat file
		i) Location: 
	b) Enter Commands
	c) Enter q to Quit.
2)Method 2
	a) Import project to Workspace Directory from git 
		i)	Order to checkout a remote project, you will have to clone its repository first. Open the Eclipse Import wizard (e.g. File => Import ),select Git => Projects from Git and click Next . 
		ii)	Now you will have to enter the repository's location and connection data. 
		iii)Entering the URI will automatically fill some fields

### Prerequisites

1) JDK or JRE  classpath is mandatory  

## Running the tests
	Enter something,'q' to quit :
		create Book01 10.50 13.79
		create Food01 1.47 3.98
		create Med01 30.63 34.29
		create Tab01 57.00 84.98
		updateBuy Tab01 100
		updateSell Tab01 2
		updateBuy Food01 500
		updateBuy Book01 100
		updateBuy Med01 100
		updateSell Food01 1
		updateSell Food01 1
		updateSell Tab01 2
		report

## Versioning
	1.0.0

## Authors

* **Dileep Surapaneni** - *Initial work*
