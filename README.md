TEAM MEMBERS :
Mahima Reddy,Mohd Iftequar Hussain,Ganesh Kurra,Venkata Siva Kishore,Chandeep Kumar Dasari
A training end project for Pension Management System

**PENSION MANAGEMENT SYSTEM** :
  Here is a project for the Pension Management System Runtime SDK for Java with Maven.
  
**Project Overview** :
        State government aims to automate a portion of the Pension detail provisioning.This project covers pensioner detail provision,calculate provision and view for further processing.
        
        
 **System Architecture** :
 
 ![file](https://user-images.githubusercontent.com/107530885/174226104-19df6eff-9036-4c0d-b8ad-1c72197d39f3.png)
 
 
 **Requirements** :
 
 *Hardware and Software Requirements* :
         
         1. Hardware Requirement:
             1. Developer Desktop PC with 8GB RAM
          
         2. Software Requirement (Java) :
             1. Spring Tool Suite (STS)Or any Latest Eclipse
             2. Have PMD Plugin,EclEmma Code Coverage Plugin
             3. Configure Maven in Eclipse
             4. Maven
             5. Docker 
             6. Postman Client in Chrome 
             7. git
            
            
  **Workflow** :
 
  *Eclipse* : 
 
 1. Open Eclipse and select File > Import.
 2. In the import wizard, choose Maven > Existing Maven Projects, then click Next.
 3. Select the java-maven-starter-project as the project root directory.
 4. Click Finish to complete the import.
 5. Select Project > Properties . In Java Build Path, ensure that under the Libraries tab, Modulepath is set to JRE System Library (JavaSE-11). In Java Compiler, ensure that the Use compliance from execution environment 'JavaSE-11' on the 'Java Build Path' checkbox is selected.
 6. Right-click the project in the Project Explorer or Package Explorer and choose Run As > Maven Build.... In the Edit Configuration dialog, create a new configuration with name unpack. In the Goals field, enter dependency:unpack. Click Run to run the goal. This will unpack the native libraries into $USER_HOME/.pension management system.
 7. Again, create a new run configuration with name run. In the Goals field, enter compile exec:java. Click Run to run the goal. The app should compile and run.
 
 
 **Run the Workflow** :
         Build the project in the project's root directory run : ./maven build 
         
         
 **License** :
         Copyrights TCS under 2022
