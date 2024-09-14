# FST CHAOUIA  
# FST Student Services

Welcome to the repository for **FST Student Services**, a web platform designed to improve the academic and administrative workflows for students and faculty at FST CHAOUIA. This project is built using **Java EE**, **HTML5**, **CSS3**, and **JavaScript**, providing a comprehensive system to easily access academic resources, schedules, and campus events.

## Key Features

- **Secure Authentication**: Robust login functionality for both students and administrators.
- **Access to Academic Resources**: Simplified retrieval of course materials, academic schedules, and advisory content.
- **Event Management**: Real-time updates on upcoming university events and activities.
- **Administrative Tools**: Easy access to administrative functions, including faculty and student services.

## Project Overview

For an in-depth look at the project’s objectives, scope, and implementation approach, refer to the full project description:

[Download the FST Student Services Project Description (PDF)](https://github.com/OmarNouih/FSTStudentServices/blob/main/Description.pdf)

## Visual Demo

Here are a few screenshots showcasing the platform's interface and functionality:

![Home Page](https://github.com/Chaimaa-zaghloul/FSTStudentServices/blob/main/FSTStudentServices/WEB_SITE_IMAGES/3.png)  
*Preview of the Home Page*

![Login Screen](https://github.com/OmarNouih/FSTStudentServices/blob/main/WEB_SITE_IMAGES/4.png)  
*Login Screen for Students*

![Administrator Dashboard](https://github.com/OmarNouih/FSTStudentServices/blob/main/WEB_SITE_IMAGES/1.png)  
*Administrator Dashboard Preview*

![Administrator Control Panel](https://github.com/OmarNouih/FSTStudentServices/blob/main/WEB_SITE_IMAGES/2.png)  
*Administrator Control Panel Overview*

![E-Document Management](https://github.com/OmarNouih/FSTStudentServices/blob/main/WEB_SITE_IMAGES/5.png)  
*E-Document Management Interface*

![E-Scolarité Services](https://github.com/OmarNouih/FSTStudentServices/blob/main/WEB_SITE_IMAGES/6.png)  
*E-Scolarité Services Interface*

## Setup Instructions

Follow these steps to install and run the project locally for development and testing purposes.

### Requirements

Before starting, make sure you have the following installed:

- JDK version 1.8 or newer
- Apache Tomcat 9.x
- MySQL Server 5.7+
- Apache Maven for managing project dependencies

### Installation Guide

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/FSTStudentServices.git
   cd FSTStudentServices


   ```

2. **Build the project**
   ```bash
   mvn clean install
   ```

3. **Deploy the WAR file to Tomcat**
   Copy the generated `.war` file from the `target` directory to the `webapps` directory of your Tomcat installation.

4. **Start the Tomcat server**
   Use the `startup.sh` (or `startup.bat` on Windows) script to run the server.

5. **Open the application**
   Visit `http://localhost:8080/FSTStudentServices` in your browser to start using the application.

## Built With

- **HTML5/CSS3** - Frontend development
- **Java (JEE)** - Backend development
- **JavaScript** - Client-side scripting
- **Apache Maven** - Dependency management
- **Eclipse** - Integrated Development Environment
- **XAMPP** - Local server for development

## Authors

- **ZAGHLOUL CHAIMAA**
- **NOUIH OMAR**
  

## Special Thanks

We extend our gratitude to everyone who contributed to this project. A special acknowledgment goes to Mr. Youssef El MORABIT, our project supervisor, for his invaluable guidance and support.
