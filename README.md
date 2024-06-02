# Report-usage-of-AWS

We are assuming that you have to monitor the resources used in your organization and have to send it to the manager by 6 pm every day.
Instead of manually checking, Today We will use AWS CLI and Shell Scripting Knowledge in this Project to get our desired job done using automation.

Outline of our Project
![image](https://github.com/mohit06chaudhari/Report-usage-of-AWS/assets/104330373/c37eca13-3ce8-4f9e-ba0c-11e3a82617bb)


Procedure : 
1. In the console, First We will be configuring aws
   aws configure
   Going on we will give our access key details and our configuration is completed.

2. Creating a bash file (.sh) for writing a shell script
   We will be extensively using the AWS CLI Documentation -> https://docs.aws.amazon.com/cli/latest/# 
   
![image](https://github.com/mohit06chaudhari/Report-usage-of-AWS/assets/104330373/09afdb92-163c-4cf0-b2a4-d602083bdfb6)

3. Modifying the bash file to make it executable using chmod command.
   chmod 700 filename
   
5. Modify the bash file with an echo command for better understanding.
   We can use the "set +x" to  run the command in debug mode

![image](https://github.com/mohit06chaudhari/Report-usage-of-AWS/assets/104330373/5541146a-a90a-4826-830a-0c580f211664)

5. Finally, Install the cronie using the yum command.
   Editing the cron file using crontab -e
   and starting the cronie services

   ![image](https://github.com/mohit06chaudhari/Report-usage-of-AWS/assets/104330373/8a63a11b-770b-4422-940c-35cd64fc3b34)


Thank You ...!!!... 
