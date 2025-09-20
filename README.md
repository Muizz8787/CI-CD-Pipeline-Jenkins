# CI-CD Pipeline with Jenkins

> A Jenkins-based Continuous Integration and Continuous Deployment (CI/CD) pipeline for automating build, test, and deployment processes.

---

## 📌 Overview

This project demonstrates how to set up a **CI/CD pipeline using Jenkins** for a Java web application.  
The pipeline includes automated code pull, build, testing, and deployment steps.

---

## 🚀 Features

- Automated code checkout from GitHub  
- Code build & compilation (Ant/Maven)  
- Unit testing (JUnit)  
- Static code analysis (Checkstyle)  
- Deployment automation  
- Test reports & build logs  

---

## 🏗️ Pipeline Jobs

The Jenkins dashboard includes the following jobs:

1. **githubpull** → Pulls the latest code from GitHub  
2. **BuildandCodeReview** → Builds the application and performs code quality checks  
3. **unittest** → Runs JUnit test cases and generates reports  
4. **deploy** → Deploys the application  

---

## 📸 Jenkins Dashboard

Below is the screenshot of the Jenkins pipeline jobs:

<img width="1366" height="768" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/e9939fde-b5b0-4af4-90b8-5d0c7ce38bbd" />

## ⚙️ Prerequisites

- Jenkins (v2.5+ recommended)  
- Java JDK 8 or newer  
- Git installed  
- Ant or Maven installed  
- A web container (Tomcat/Jetty) for deployment  

---

## 🛠️ Setup & Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/Muizz8787/CI-CD-Pipeline-Jenkins.git
    cd CI-CD-Pipeline-Jenkins
    ```

2. Place the project in Jenkins workspace or configure the repo in Jenkins.

3. Create Jenkins jobs as shown in the dashboard:  
   - `githubpull` → SCM checkout  
   - `BuildandCodeReview` → Build + Checkstyle  
   - `unittest` → Run tests  
   - `deploy` → Deployment  

4. Run the pipeline and monitor build/test results.  

---

## 📂 Project Structure

