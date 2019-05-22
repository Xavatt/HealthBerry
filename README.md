# HealthBerry

HealthBerry Project

## Objective

The objective of this project is the creation of medical history and make it portable using a raspberry (a very small computer). 

The application should provide medical information for patients and doctor each one in its own interface

## Goals

**Our principal goals are:**

-   With the use of the application **"HealthBerry"** is to grant patients access to their clinical file in a portable way, access anywhere they are allowing them to take better control of this information and as a consequence to be able to lead better health.
-   With the implementation of the application will allow doctors to work more efficiently saving time which is invested in obtaining patient data, facilitating their access to them and leading to a better diagnosis at the time of consultation.
-   Thanks to the **"HealthBerry"** application, in case the patient wants to change clinics or doctors, it will not be necessary for his clinical file to start again since all the data as well as his exams, consultations, previous prescriptions will be stored in an encrypted form and safe, also protecting the data of previous doctors.
-   To innovate in the medical and technological industry by implementing a better use of resources, and also to unify a little more these 2 areas in which large technological implementations can be made to improve work efficiency in the medical field.

## Problem Statement

We are required to implement a database that contains all the information provided by the patients and the doctors stored in the following tables:

- PACIENTE
- DOCTOR
- CONTCTEMERG
- EXAMENES
- RECETAS
- ATENCION

Our program will run as an executable file that will be load in a microSD card that will be the storage for the executable and the database of our program. That will be inserted in the microSD slot of the raspberry. The application will make a connection with the database and will load all the information stored in the database, ready for storage new information or in case they have the permissions and the keys modify personal information.

## Expected Outputs

Here we have  some screen of the interface that we are expecting.

![WhatsApp Image 2019-05-20 at 4 46 20 PM(1)](https://user-images.githubusercontent.com/15019106/58097181-63251500-7b9c-11e9-9538-ad26f814c4c1.jpeg)

![WhatsApp Image 2019-05-20 at 4 46 20 PM](https://user-images.githubusercontent.com/15019106/58097216-7e902000-7b9c-11e9-934c-95a08d2b7f52.jpeg)

## Problem Solving



## How To Install The Material Needed

Using a Windows environment of **64-bits**, to build the executable of the program is required the use of the terminal, also called *command line*. For running the script that contains the query of the database or using the following programs. 

### The prerequisites are:

  - 1.- The programming language Java (JDK)
  - 2.- MySQL Connector Java 
  - 3.- MySQL & MySQL Workbench

**1. Install MySQL installer & MySQL Workbench**

- 1.- Write in the seeker of your preference **"MySQL"** and make click in the first result of the search 
- 2.- Once you are in the Home Page of MySQL go to section **"Downloads"** 
- 3.- Go to the subsection **"Community"**
- 4.- Make click in the section **"MySQL on Windows"** once you click on it you will find **"MySQL Installer"** 
- 5.- Once you scroll down the page you will find two options ***"MySQL-Installer-Web-Community"*** and ***"MySQL-Installer-Community"*** choose the second one.
- 6.- Download the file and install them

Also you can make click in the following link to go directly to the download the file:

[MySQL Installer Community](https://dev.mysql.com/downloads/file/?id=484920 "Download me")

**2. Install Java & MySQL Connector Java**

- 1.- Write in the seeker of your preference **"JDK"** and make click in the first result of the search
- 2.- Once you are in there you will find two download options Java Platform (JDK) and NetBeans we will continue with both options
    - 2.1.- JDK: You will find several download options, choose the one that satisfy your computer specifications
    - 2.1.1.- You will download an executable file, run it and follow the steps of the installation
- Downloading NetBeans apart from providing the JDK provides you with an editor for the execution of the entire project as well as an editor for more code execution.    
    - 2.2.-NeatBeans: You will find several download options, choose the one that satisfy your computer specifications 
    - 2.2.1.- You will download an executable file, run it and follow the steps of the installation

Also you can make click in the following link to go directly to the download the file:

[JDK File](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html?ssSourceSiteId=otnes "Download me")

[NeatBeans](https://www.oracle.com/technetwork/es/java/javase/downloads/jdk-netbeans-jsp-3413139-esa.html "Download me")

**NOTE: Since the source code is in several files, the files MUST be in the same directory**


