# VProfile project Setup [Local]

 # About the Project 

* Multitier web application stack
* setup on Laptop or desktop
* Baseline for Upcomming Projects
* Helps to setup any project locally

# Objective 

* VM Automation Locally 
* Base Line for upcomming projects 
* Real world projects setup Locally (For R and D)

# Scenario

* working in a project
* Varieties of services That power the  project
* we may have services like database mysql ,Postgresql webservices, Apache Nginx application services maybe like tomcat ,jboss,glassfish  or any other stack like that 
* Run book / setup document to setup the project stack

  # Problems

  * Not comfortable in making changes in real servers
  * Local setup is complex
  * Time consuming
  * Not repeatable
 
  # Solution

  * We have the Loacl Setup YES But it would be automated repetable Because were going to have infrastructure as a code 
  * We have code to setup the entire stack  Locally
  * We can doit many as time 
  * We can do as much as R and D you want on your Local Machine
 
  # Tools

  * Hypervisor - Oracle VM Virtual Box
  * Automation - vagrant
  * CLI - Git Bash
  * IDE - Sublime Text

  # Architectural Design

     * # Architectural Project services

     * Nginx 
     * tomcat 
     * Rabbitmq 
     * Memcached 
     * MySql Service

   ![vp](https://github.com/Bhavana851/vprofile-project-main/assets/153347669/7ede0ed9-9dd6-4d2b-89ae-d3121775c1fb)


    *  # Architecture of automated setup

     * Vagrant 
     * virual Box 
     * gitBash
       
    ![AVP](https://github.com/Bhavana851/vprofile-project-main/assets/153347669/4b9ff267-8314-4369-ab01-66d7a960eaae)


    # Flow of Execution
  
    * setup tools as mentioned in Prerequisite Video
    * clone source code
    * cd into the vagrant dir
    * Bring up the VM's
    * Valindate
    * Setup all the services
       - My sql
       - Memcached
       - Rabbit MQ
       - Tomcat
       - Nginx
       - App Build and Deploy
    * Verify from browser










  
