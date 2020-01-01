# Blood Bank Management using JAVA with GUI

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Usage](#usage)
* [Summary](#Summary)
* [Results](#Results)
* [Report Link](#report-link)
* [Authors](#Authors)

## General info
This project is Java implmentation implmentation that aims at maintaining all the information pertaining to blood donors, different blood groups available in each blood bank, processing requests for bottles of blood, and help them manage in a better way. We have used some data structures like linked list and array list which are dynamic in nature and hence would help us achieve our aim. 

	
## Technologies
Project is created with:
* Software: Eclipse Java Oxygen
* Programming Language: JAVA

## Features	
* User And Admin Functionality
    * Admin can view the information of Donors, Purchasers, Bloodbottles Availability and manage them.
    * User can register and then login to purchase / donate blood
* Authentication is provided with password functionality to ensure security
* Data Structures such as Linked List and Array List are implemented
* File Handling is used for easy access to information
* GUI (Graphical User Interface) is implmented


## Summary
The program used to create this system will require dynamic memory since the number of users – donors or purchasers are not fixed. The use of linked list will therefore be useful in implementing the above-mentioned feature. The records are stored in files using File Handling. Our approach towards building this system is as follows – The system is operated upon by two kinds of people – User and Admin. As the program begins, a welcome frame appears asking the person operating to choose between a user and an admin. A user can either login or register depending on whether he/she is operating for the first time or not. In the case of admin, the respective person will only have the option of login and not register since the number of people who belong to admin panel will be pre-determined. Starting with the user, it is further divided into two distinctions –Donor and purchaser. The donor will have the functionality of donating blood and in order to do so he/she will have to respond to certain questions which are necessary for checking the basic blood health. Whereas, the purchaser can request for a specific blood group from the admin and if it is available then admin will give the receipt to the purchaser else admin will notify the purchaser whenever the blood bottle will be available. The functionality of inserting the details of users, deleting them when required, displaying all the details, searching for a specific donor or purchaser, sorting the details, and updating them are performed by the admin. All these functionalities have been implemented using linked list. It is done so by inserting the objects of the respective classes into linked lists having data type of those classes. To execute the functionalities, corresponding function to the functionality is called upon the object of the respective linked list. For the processing of data in all cases, firstly the existing data is read from the file and added to the linked list then after the data is added it is processed, and then it is finally written into the files. However, in some cases the data is only read depending on the functionality. The sorting functionality has been implemented using merge sort since it has the least, worst case running time O(nlgn). In sorting, arraylist is specifically used because it will be easy to first sort by one element of the linked list object and then order the complete linked list by putting the sorted object back into linked list. Therefore, when all the functionalities are combined, it will result into the full-fledged blood bank management system as stated by the problem. Further, to make it visually appealing and to provide ease for the user to operate upon, we have implemented the system on Graphic User Interface(GUI). 


## Results

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/1.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/2.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/3.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/4.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/5.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/6.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/7.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/8.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/9.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/10.JPG)

![Alt Text](https://github.com/MuskanM1/Blood-Bank-Management/blob/master/docs/screenshots/11.JPG)

## Report Link
https://drive.google.com/open?id=1bFs-6hs6GIYz1NB73rGcrLBfGF5DDNCA

## Authors
* Muskan Matwani (@MuskanM1)
* Yesha Shastri

