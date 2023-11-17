# Todo Webapp

Technologies used 
1. Angular
2. SpringBoot
3. MySQL
------------------------------------------------------------------------------------------------------------------------------------------------
Functionalities -

1. User Registration (Email, username, password OR via gmail)
2. User Login (username/password OR via gmail)
3. Multi-factor authentication
4. User deactivation/deletion
5. Forgot password
6. Encrypted password
7. Create/Modify/Delete Todo task
8. Create/Modify/Delete Todo Card
10. Integrate Todo task to Google Calendar
11. Categorize/Tags for the tasks
12. Prioritize and deadline
13. Todo task reminders
14. Recurring todo tasks
15. Auto save changes
16. Send over email
17. Share as image/pdf/excel
18. Search and filter tasks

------------------------------------------------------------------------------------------------------------------------------------------------
Plan

Phase 1 - 
User Regis/Login/Deleting | 
Forgot password + Encrypted password | 
Create/modify/delete todo Task and Card | 
Tags for cards | 
Auto Save

Phase 2 -
Multi-factor authentication | 
Integrate with google calendar | 
Filter tasks | 
Deadline for cards | 
Prioritize tasks | 
Reminders | 
Recurring todo tasks | 
Send over email | 
Share

------------------------------------------------------------------------------------------------------------------------------------------------
High Level Architecture -

![image](https://github.com/parul-sinha/Todo/assets/30214106/c5faa868-cc1c-4be1-855d-593940e9bc38)


------------------------------------------------------------------------------------------------------------------------------------------------
Data Object Models -

User{
user_id, 
user_name, 
encoded_pass, 
user_email, 
user_status
}

Task{
task_id, 
task_description, 
task_deadline, 
task_tags, 
task_reminder_date,
found_in_cards,
task_priority, 
is_cal_integrated, 
is_having_priority, 
is_having_deadline, 
is_having_tags, 
is_having_reminder, 
}

Card{
card_id, 
card_date, 
contains_tasks, 
created_timestamp, 
}

------------------------------------------------------------------------------------------------------------------------------------------------
