
# ✈️ Flight Ticket Booking Service

A flight booking website that allows users to search and book one-way, round-trip, or multi-city flights. The application is tested using automation scripts to ensure smooth functionality and user experience.




## Tech Stack

- **Java**
- **Selenium WebDriver**
- **TestNG**
- **Maven**
- **Jenkins** (CI/CD)
- **Ngrok**


## Features Covered

- Round trip.
- One-way trip.
- Multi-city travel.


## Installation/ Setup Instructions

1.	Install Eclipse IDE (or any preferred IDE).
2.	Install Java JDK (ensure JAVA_HOME is set).
3.	Clone this repository:
```bash
git clone https://github.com/your-username/your-repository-name.git
```
4.	Open the project in Eclipse.
5.	Make sure Maven is installed and configured.
6.	Update Maven dependencies (Right-click on project > Maven > Update Project).
7.  Java and Selenium basics are recommended for understanding

    
## Running Tests

-	Via testng.xml:
    Right-click testng.xml → Run As → TestNG Suite
-	From Eclipse:
    Right-click on test classes → Run As → TestNG Test
-	Test execution reports will be generated automatically.
-   The test can also be run using mvn from the command prompt by running the code below: 
```bash
mvn test
```


## Folder Structure

```
├───.settings
├───reports
├───src
│   ├───main
│   │   └───java
│   │       └───SeleniumProject
│   │           ├───PageObject
│   │           ├───Resources
│   │           └───ReuseableComponents
│   └───test
│       └───java
│           └───SeleniumProject
│               ├───Data
│               ├───main
│               └───Test
├───target
│   ├───classes
│   │   ├───META-INF
│   │   │   └───maven
│   │   │       └───SeleniumProject
│   │   │           └───Flight_Ticket_Booking_using_Framework
│   │   └───SeleniumProject
│   │       ├───PageObject
│   │       ├───Resources
│   │       └───ReuseableComponents
│   └───test-classes
│       └───SeleniumProject
│           ├───Data
│           ├───main
│           └───Test
└───test-output
    ├───Default suite
    ├───junitreports
    ├───old
    │   ├───Default suite
    │   └───Suite
    └───Suite
```
## Screenshots
- Extent Report
![image](https://github.com/user-attachments/assets/6229565f-7784-4471-b4fd-029abb960016)
- Jenkins(CI/CD)
![image](https://github.com/user-attachments/assets/2d7cfff1-cbac-4dd7-af34-4e7149ee9840)
- QA ClickJet
![image](https://github.com/user-attachments/assets/41b17493-2a75-4c73-a8be-576f3fbbd217)




