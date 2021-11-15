# Lab 8 - Starter

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**Selected** Within a Github action that runs whenever code is pushed 
Manually run them locally before pushing code
Run them all after all development is completed

**Why?** Better to test throughout the develpment fase - easier to fix smaller mistakes than to fix the complete project. One should also allways try to make sure that the master branch is good code, and therefore one should do all necessary tests before combining different modules. Doing it within a github action saves time.
 
2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

**answer:** No, because E2E imitates user actions, hence being more of a front end testing method. 

3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

**answer:** Depends I guess, but could be to big of a feature for using unit testing. Maybe e2e is better for this task. 


4) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.

**answer:** Yes, seems like an appropriate "size" of fetature for unit testing. 