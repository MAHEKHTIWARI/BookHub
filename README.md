# 📚 Library Management System -Java


A Library Management System made using the concepts of Object Oriented Analysis and Design. Minimal Code is written in the GUI and the entities are decoupled as well. The interface is console based. This project was designed during the course "Object Oriented Analysis and Design CS309".

The **Class Diagram** of the project is also provided along with the **Database Schema** file. The class diagram file can be opened using [Star UML](http://staruml.io/).

## Class Diagram
![class diagram](../master/images/diagram.PNG)

**Note**: After Refactoring, new Class "HoldRequestOperations" is added to the above structure which lies in between the HoldRequest class and Book class.
This class removes the bidirectional dependency between HoldRequest and Book. More details mentioned [here](https://github.com/OSSpk/Library-Management-System-JAVA/issues/9) 

## Interface
<p align="middle">
   <img src="../master/images/interface.PNG" width="400"/>
   <img src="../master/images/interface2.PNG" width="400"/>
</p>   

## Actors:
The actors include the following: 
* Librarian
* Checkout Clerk
* Borrower
* Administrator

## Use Cases:
After determining the actors, the second step in use case analysis is to determine the tasks that each actor will need to do with the system. Each task is called a use case because it represents one particular way the system will be used.

**In other words, only those use cases are listed that actors will need to do when they are using the system to solve the customer’s problem.** 

### Borrower:
* ❏ Search for items by title.
* ❏ ... by author.
* ❏ ... by subject.
* ❏ Place a book on hold if it is on loan to somebody else.
* ❏ Check  the  borrower’s  personal  information  and  list  of  books  currently
borrowed.

### Checkout Clerk:
* ❏ All the Borrower use cases, plus
* ❏ Check out an item for a borrower.
* ❏ Check in an item that has been returned.
* ❏ Renew an item.
* ❏ Record that a fine has been paid.
* ❏ Add a new borrower.
* ❏ Update a borrower’s personal information (address, telephone number etc.).

### Librarian:
* ❏ All of the Borrower and Checkout Clerk use cases, plus
* ❏ Add a new item to the collection.
* ❏ Delete an item from the collection.
* ❏ Change the information the system has recorded about an item.

### Administrator:
* ❏ Add Clerk.
* ❏ Add Librarian.
* ❏ View Issued Books History.
* ❏ View All Books in Library.


## How to Run
1- Install these:
 * [Java SE Development Kit 8 (JDK 8)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
 * After installing JDK 8, install [NetBeans IDE](https://netbeans.org/downloads/)

2- Open NetBeans IDE. Click on File -> Open Project and browse to the downloaded folder named "Project" and select it. It will load the NetBeans project.

3- Now everything is setup except the Java DB (Derby) Database of NetBeans. So, follow these steps to setup the database:

**Step 1:** In the Netbeans Window, there is a tab named "Services" on the left. Select it. Then right click on JavaDB > Properties and    change database location to "Database" folder downloaded with this repository (its placed besides the "Project" folder).

![step1](../master/images/step1.PNG)
   
**Step 2:** After that a database named LMS will show up under JavaDB tab. Now Right Click Databases > New Connection and select Java DB Network and click Next. 

![step2](../master/images/step2.PNG)
   
**Step 3:** Provide the following database crendentials in the next popup and click Next.
  ```
  Host: localhost
  Port: 1527
  Database: LMS
  User Name: haris
  Password: 123
  ``` 
![step3](../master/images/step3.PNG)

**Step 4:**
Now just click Next for the rest of the windows. After all this the database connection is made. Make sure that you connect with the database before running the project by right clicking on the connection and selecting connect. Now you are ready to run the project!

![final](../master/images/final.png)

## Note
The password for Administrative Functions is *lib*. The admin adds new clerks and librarian, then they both do the rest of the functions.

<hr>

<h1 align="left">Hey there, I'm <a href="https://www.linkedin.com/in/harismuneer/">Haris </a><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"> 
 <a href="https://github.com/harismuneer/Ultimate-Facebook-Scraper"><img align="right" src="https://user-images.githubusercontent.com/30947706/79588950-17515780-80ee-11ea-8f66-e26da49fa052.png" alt="Ultimate Facebook Scraper (UFS)" width="200"/></a> - Maker of Things</h1> 


### Creator of <a href="https://github.com/harismuneer/Ultimate-Facebook-Scraper">Ultimate Facebook Scraper</a> (one of the best software to collect Facebook data for research & analysis) 

<hr>


## 🤝 Consulting / Coaching
Stuck with some problem? Need help in solution development, guidance, training or capacity building? I am a Full Stack Engineer turned Project Manager with years of technical and leadership experience in a diverse range of technologies and domains. Let me know what problem you are facing at <b>haris.muneer5@gmail.com</b> and we can schedule a consultation meeting to help you get through it.

## 👨‍💻 Technical Skills & Expertise

- Development of Web Applications, Mobile Applications, and Desktop Applications
- Development of Machine Learning/Deep Learning models, and deployment 
- Web Scraping, Browser Automation, Python Scripting
<hr>


## ❤️ Support / Donations
If you or your company use any of my projects, like what I’m doing or have benefited from my projects in any way then kindly consider backing my efforts.

For donations, you can follow these simple steps:

<b>1)</b> Free signup at <b>[TransferWise](https://transferwise.com/invite/u/harism95)</b> using this link: https://transferwise.com/invite/u/harism95</li>. (Signing up through this link will save you from any transcation fee on the donation)

<b>2)</b> Select the amount e.g (15$) and choose the receiving/recipient's currency to be PKR. It supports multiple payment options (credit card, debit card, wire transfer etc)

<b>3)</b> Then it will show my info as the recipient, select it. If my name isn't shown, then type my email haris.muneer5@gmail.com in recipients.

<b>4)</b> Choose the reason for transfer to the one that suits you the most (in this case it could be 'General expenses') and in the reference section, you can mention 'Support'
 
If you face any issue in sending donation then feel free to get in touch with me at haris.muneer5@gmail.com 

Thank you for your contribution!

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](../master/LICENSE)

Copyright (c) 2018-present, harismuneer, MahamAmjad                                                       
