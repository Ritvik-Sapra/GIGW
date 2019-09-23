# GIGW
Completed this project during my internship period at ERNet. The project is a Web based software which lists all the Guidelines for Indian Government Websites (GIGW). An employee can check a particular website for compliance of these guidelines and tick the checkbox. The complete data will be stored in a database under the ID of the employee.

#### _What is GIGW ?_
GIGW stands for Guidelines for Indian Government Websites. These are a set of guidelines that all Indian Government websites must abide by. For example, there should be an option to enlarge text for weak eye sight, there should be site navigation and pictures description, etc. These guidelines maybe subject to change, but this project was build in 2018, so guidelines during that period is taken into account.

## What does the project look like ?
The project opens up in a website login page. When all the correct database are made and found, the user can either create an ID or use his/her exising ID to log into the workspace of the projects. The IDs are kept in a seperate database and are protected by MD5 encryption. The work space has main sections under which different guidelines are divided into for better navigation (_there are more than 100 guidelines_). Inside each section are the guidelines written and has a check box at the end which the employee can tick. So for example if the website has proper navigation, you check box. At the end, when the user will click submit, all the clicked checkbioxes will be saved in a database under the user's ID and website name, so that when the same user opens up, he can resume where he last left.

## How to run it on my computer ?
I used the local server XAMPP to develop and test this project. Unfortunately this was not deployed on internet or in the office at my time, but it was being developed further and soon it would be deployed for all the employees for easy and organised working. So if you have to run it, run it on XAMPP environment. You can get it here: https://www.apachefriends.org .
For the database, I used PHP MyAdmin. The name of the data base is **lab_data** (given in the zip folder). There will be 7 tables when you import the database to php my admin. The name of all the tables are given below:
1. gigw_points
2. gigw_sub
3. mobile_accessibility
4. mobile_general
5. reg_user
6. website_accessibility
7. website_general
All these will be SQL tables and SQL querries can be performed on all of the tables.

After this, run *Apache* and *MySQL* from XAMPP control panel and type "localhost/lims". The first page opens up in login page. For first time, scroll down and click register as new membership, and the project should open up. Remember you user ID and password.
By the way, if anyone is wondering, LIMS is short for **Laboratary Information Management system**.

# What is the use of this project ?
There are several Indian Government websites. Each of them needs to be checked for these guidelines (*reminding again that there are more than 100 guidelines and they are subject to change.*). It becomes almost imposible to keep a track record of all the websites and which guidelines it follows. Using this site we could do everything digital and the user could start off where he last left off. This becomes very useful when working with such a huge and complex data. Obviously more features could be incorporated in this like emailing the auto-generated report or give a message when all the guidelines are completed. I am sure all of the features would be updated and hopefully this project is in use right now :innocent:.

**All the required files are in the zip folder. If any file is missing, try contacting me and suggesting changes.**
