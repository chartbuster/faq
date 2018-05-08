# Faq site
#KEY FEATURES
* Access Control
* Database Notifications
* Email Notifications Using Mailtrap

**Frequently asked questions:**
This demo website has few features similar to quora and other Q&A forum websites.

**To run this project on your local:**

**Clone:**

git clone https://github.com/hc373/faq.git

**Composer:**

CD into FAQ and run composer install

**env file:**

cp .env.example to .env

**Database Setup**

Setup sqlite database

**Generate artisan key**

php artisan key:generate        

**Migrate**
php artisan migrate

#ABOUT FAQ
Epic Story explaining the key features:

There are three kinds of Access types/roles (Access controls) for a user
1. Super Admin
2. Admin
3. Member (In this project we have focused on this user role only!)
![image](https://user-images.githubusercontent.com/35869378/39732134-b3f2d6b2-5239-11e8-86ee-2392171699f2.png)
 


**Register and Create Profile:**
To become a website user can create an account using email. Once logged in, the user should be able to create his/her profile and can also Edit it!
Ask questions:
A user once logged in will be able to create questions, view the questions and edit the questions admin, one should be able to view the faqs and view the users.
Answer a question:
A user once logged in can answer a question, edit and delete it. 

**Answer Notifications (via database):** 
Once a question is answered, the user is notified that his/her question is notified via database. The count of the notifications depends on the number of answers.
![2](https://user-images.githubusercontent.com/35869378/39732179-dab3d152-5239-11e8-829b-eacbba685f8b.jpg)
 

**Answer Notifications (via Mailtrap):**
Once a question is answered, the user is notified that his/her question is also notified via mail to the mailtrap inbox that. Each new answer is notified via an email.

![3](https://user-images.githubusercontent.com/35869378/39732183-dec2714a-5239-11e8-91df-2a88e942b9eb.jpg)

  


**Unit Testing**
10 successful tests and 10 asserstions.

![4](https://user-images.githubusercontent.com/35869378/39732191-e5fec3e6-5239-11e8-83ff-cea2e78aa1c0.jpg)

**Link to Heroku App**
 This app is only till the point where user can create and answer questions. When tried to push the notification feature, heroku is showing an database error.
 Link to heroku app: https://faqsite.herokuapp.com/
 
 
 **Website working Demo Video**
 Link to demo video on youtube https://youtu.be/kVQADRlkKsY


**References**
These videos by Mr. Keith Williams, Professor at NJIT, will be very helpful for those who want to start their career in Web Systems development. This will be a standard intro series for the web dev beginners.
Link to Mr. Keith Williams Youtube Channel : https://www.youtube.com/channel/UCSOm2zK1tPb3DyUqYR36Xag

**License**

**Faq** is licensed under the MIT license


