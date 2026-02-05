📌 Project Overview

This project demonstrates end-to-end automation testing of a Contact List Web Application using Selenium WebDriver with Java and TestNG.
The automation suite covers major user workflows such as Sign Up, Login, Add Contact, Edit Contact, Delete Contact, Logout, and navigation between pages.

This project is designed to showcase real-world automation framework skills for QA / SDET roles.

🛠 Tech Stack

Language: Java

Automation Tool: Selenium WebDriver

Test Framework: TestNG

Build Tool: Maven (optional / recommended)

Browser Support: Chrome, Firefox, Internet Explorer

Design Pattern: Basic TestNG + Config-based setup

IDE: Eclipse / IntelliJ IDEA

🌐 Application Under Test

URL:

https://thinking-tester-contact-list.herokuapp.com/

📂 Project Structure
ContactListAutomation/
│
├── src/test/java
│   └── PAK2
│       ├── Config.java
│       ├── SignUp.java
│       ├── Login.java
│       ├── AddToContacts.java
│       ├── EditContact.java
│       ├── DeleteContact.java
│       ├── ReturnToContactList.java
│       └── Logout.java
│
├── src/test/resources
│   └── DataFile.properties
│
├── testng.xml
└── README.md

⚙ Configuration File (DataFile.properties)

Used to manage browser selection and environment details.

UserName = Sidra Sabar
Browser = Chrome
URL = https://thinking-tester-contact-list.herokuapp.com/

🔑 Key Features Automated

✔ Browser setup using configuration file
✔ User Registration (Sign Up)
✔ User Authentication (Login)
✔ Add New Contact
✔ Edit Existing Contact
✔ Delete Contact
✔ Return to Contact List
✔ Logout Functionality

🚀 Test Scenarios Covered

Verify user can sign up successfully

Verify valid login functionality

Verify contact creation with valid data

Verify editing contact details

Verify deletion of a contact

Verify navigation back to contact list

Verify logout functionality

🧪 Sample Test Flow

Launch browser

Open application URL

Perform user sign-up

Login with credentials

Add a new contact

Edit contact details

Delete contact

Logout
