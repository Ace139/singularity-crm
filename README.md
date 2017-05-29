# Singularity-CRM
An One Stop shop for a **Scalable, Unified and Customized CRM System** built on top of Microservices.

* Fully Customized Material Design UI
* Option to deploy in any Cloud Service of choice
* Ease of customizing every component without writing any code
* Option to choose from numerous services
* Inbuilt Analytics Dashboard
* API for accessing data for Analysis
* Integrated Hybrid-Mobile application for all platforms

## Target Users :

* Small and Medium scale Starups (**B2B** and **B2C**) having limited funding for investing in CRM.
* Small and Medium established Businesses who want a **_Unified CRM System_**.
* Any compnay having trouble in **Scaling** their existing CRM System.
* Any company wanting to **Rebuild** existing CRM System from scratch with **customized features**.


## Elements in CRM : 

* Prospect
* Customer
* Product Developer
* Accountant
* Sales Executive
* Manager
* Support Personel
* Product


## Features :

* [ ] **Profile** : It will contain all the details of a CRM element.

(Prospect | Customer | Product | Sales Executive | Manager | Accountant | Product Developer)

* [ ] **Interactions** : It will record interaction of company personels with the Prospects and Customer. Mainly,
    - Prospects interact with Sales Executive
    - Customer interact with Support Personel and sometimes Manager

(Prospect | Customer | Sales Executive | Manager | Support Personel)

* [ ] **Billing/Payment/Salary** : It will record and manage all the transactions. Like 
    - Billing for the Customers
    - Payment to the 3rd Party Services
    -  Salary to all the employees

(Customer | Sales Executive | Manager | Product Developer | Support Personel | Accountant)

* [ ] **Feedbacks** : It will be for recording all the feedbacks from different elements of the CRM. Like
    - Customer feedback on Product or Support
    - Manager feedback on Employees, Customer
    - Employee feedback on Manager etc.

(Prospect | Customer | Sales Executive | Manager | Product Developer | Support Personel | Accountant)

* [ ] **Communication** : It will be for internal communication of the company. Mode will be IM.

(Sales Executive | Manager | Product Developer | Support Personel | Accountant)

* [ ] **Tracker** : It will enable to track progress and activity. Like,
    - Track production stage of Product
    - Track product delivery to customer
    - Track payments from customer and payments to employees
(Customer | Sales Executive | Manager | Product Developer | Accountant | Product)

* [ ] **TODO Schedular** : It will enable to schedule meetings and other activities in calender format with reminders

(Sales Executive | Manager | Product Development | Accountant | Support Personel)

* [ ] **Analytics/Insights** : It will provide with basic analytics (Need Clarity).

(Sales Executive | Manager | Acountant)

* [ ] **Group Formation** : It will enable to categorize elemnts of a CRM into groups on some basis.

(Prospect | Customer | Sales Executive | Manager | Prooduct Developer)

* [ ] **Multi-role Provision** : It will enable to assign multiple responsibilty to a single employee, especially applicable for startups.

(Manger | Employee | Sales Executive | Accountant | Product Developer)


## Details : 

* [ ] **Prospect** :
    - [ ] Add | Modify | Delete | Details
    - [ ] Interactions with Sales Executive
    - [ ] Feedbacks
    - [ ] Sales Executive
    - [ ] Manager
* [ ] **Customer** : 
    - [ ] Add | Modify | Delete | Details
    - [ ] Interaction with Managers
    - [ ] Product Tracker
    - [ ] Billing
    - [ ] Feedbacks
    - [ ] Interaction with Services or Support
* [ ] **Product** : 
    - [ ] Add | Modify | Delete | Details
    - [ ] Delivery & Manufacturing Schedule 
    - [ ] Analytics
* [ ] **Manager** :
    - [ ] Add | Modify | Delete | Details
    - [ ] Interactions with Everyone
    - [ ] Salary
    - [ ] Payment
    - [ ] Feedbacks on Sales Executive | Product | Customer | Employees
    - [ ] Communications with Sales Executive | Employees
    - [ ] Schedule Meetings
    - [ ] TODO Planner
    - [ ] Analytics
    - [ ] Tracker on Progress
* [ ] **Sales Executive** :
    - [ ] Add | Modify | Delete | Details
    - [ ] Interactions with Prospect
    - [ ] Salary
    - [ ] Feedbacks on Sales Customers
    - [ ] Communications with Managers
    - [ ] Schedule Meetings
    - [ ] TODO Planner
    - [ ] Analytics
    - [ ] Tracker on Progress
* [ ] **Accounts** :
    - [ ] Add | Modify | Delete | Details
    - [ ] Salary
    - [ ] Billing
    - [ ] Communication with Managers

## Technology Stack :

* **Containers** - [Docker](https://www.docker.com/)
* **Orchestration** - [Kubernetes](https://kubernetes.io/)
* **Back-end** - [Django](https://www.djangoproject.com/)
* **Front-end** - [ReactJS](https://facebook.github.io/react/) | [VueJS](https://vuejs.org/)
* **Database** - [PostgreSQL](https://www.postgresql.org/)
* **Visualization** - JavaScript Frameworks
* **Analytics** - [GoLang](https://golang.org/) | [Julia](https://julialang.org/)
