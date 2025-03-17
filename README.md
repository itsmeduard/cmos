# Customer Membership Onboarding System (CMOS)

## Outsystems Technical Assignment - Filsen Eduard Valdez

This is a technical exam for Savant Infotech Solutions Pte Ltd, created by [Filsen Eduard Valdez](https://filseneduardvaldez.bss.design).

The **Customer Membership Onboarding System (CMOS)** is a web application developed using OutSystems, designed to streamline the customer loyalty membership program. It facilitates the process from application submission by sales consultants to approval or rejection by managers. 

CMOS effectively addresses the client's need for a structured and efficient membership onboarding process, ensuring data accuracy and a clear workflow between sales consultants and managers.

The tech stack used for this project is OutSystems Service Studio(IDE), OutSystems Service Center, OutSystems Lifetime, HTML, CSS, Javascript.
- - - - -

## Screenshots 

![Filsen Tech Exam Img 1](https://i.imgur.com/G3HIBhS.png)

- - - - -

![Filsen Tech Exam Img 2](https://i.imgur.com/il3xnWX.png)

- - - - -

![Filsen Tech Exam Img 3](https://i.imgur.com/RCjOVNr.png)

- - - - -


## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- You can login to adminpanel by going go `/login` URL and login with credentials __admin@admin.com__ - __password__


## Technical Exam

**Instructions:**

You are given three calendar days to complete and submit this technical assignment. You
are to follow the instructions stated here.
- You are to build a web application using Outsystems to solve the problem statement
- You can create a free Outsystems environment here and download the IDE
- You are to submit the Outsystems OAP and OML files with a README.md to
indicate the URL to your application, any assumptions and information to support
your assignment
- Upload the files to google drive and share the link via email with subject title
“Outsystems Technical Assignment - name”

**Problem Statement**

Your client wanted to start a loyalty membership program for their customers. Whenever a
customer wants to join as a member, a sales consultant will submit the membership
application and a manager will approve the application before it is recorded in the system.
You may make the following assumptions when building the application
- There is no requirement for any authentication or authorization
- You may use Outsystems default themes
- You may state any other assumptions made on requirements.

**Business Requirements**

- As a sales consultant, I want to be able to capture the following information of my
customers’ membership application

- As a manager, I want to review and approve the membership application entered by
my sales consultant. I can make changes to the profile where necessary

- As a manager, I can also reject the membership profile with a comment on the
reason

- As a sales consultant, I want to see that my manager has approved the membership,
and a membership number is generated upon approval

- As a sales consultant, I want to see that my manager has rejected the membership
application, and the comment provided


**Assessment**

You will be assessed on
- How well the program solves the problem statement and met requirements (30%)
- Design of the application using workflows, screen actions and server actions (30%)
- Design of the entities (20%)
- Ease of understanding, structure and maintainability of logic (20%)

