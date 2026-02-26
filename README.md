name: pefince (personal finance)
description: personal finance manager android app



rough idea:

* login
* register
* reset password
* verify email / account
* manage user profile
* manage income
* manage expenses
* manage savings profile
* chart of income and expenses
* manage session in db



functional Requirements:

* tracking income and expenses
* just have user role
* user can login and register
* the data for login: username and password
* the data for register: username, first name, last name, email, DOB, password
* user can reset password by sending some kinda code or link to registered email for reseting password
* user can reset password by using emergency code
* user must verify account after login by sending some kinda code or link to registered email
* user must verify email after register by sending some kinda code or link to email
* user have emergency code that generate when register account and sending to email
* user have their own user profile
* user can see income and expenses
* user can see chart of income and expenses with color, green color for income and red color for expenses
* user can add income and expenses
* user can see, add, edit and remove savings profile
* user can alocate their income to savings profile
* system see, add, edit and delete session in db using supabase auth



page: 

* home
* detail income and expenses
* add income
* edit income
* add expenses
* edit expenses
* profile
