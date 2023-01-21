# smtp-env-setup
setup email smtp gmail utk aplikasi php (laravel, etc)

# How-to

How to get security key for your gmail account:

1. Go to myaccount.google.com and choose your account
2. Go to "Security" tab on the sidebar


   ![image](https://github.com/KevinNVM/smtp-env-setup/blob/dc54bc1e49ee9b8fa0bb2dc7eaa71c7485e51096/images/Screenshot%202023-01-21%20230632.png)

3. Activate 2 Step Verification

   ![activate 2 step verif](https://github.com/KevinNVM/smtp-env-setup/blob/0a98127758864b0973b1b48ff8e959c379187e05/images/Screenshot%202023-01-21%20230907.png)

5. After that, go back to "Security" tab and click on "App Password" to setup a new app

   ![setup new app pass](https://github.com/KevinNVM/smtp-env-setup/blob/0a98127758864b0973b1b48ff8e959c379187e05/images/Screenshot%202023-01-21%20230929.png)

7. Click "select app" and choose "Other (custom name) 

   ![setup new app](https://github.com/KevinNVM/smtp-env-setup/blob/0a98127758864b0973b1b48ff8e959c379187e05/images/Screenshot%202023-01-21%20230952.png)

9. Type in your app name eg: Laravel App

   ![type app name](https://github.com/KevinNVM/smtp-env-setup/blob/0a98127758864b0973b1b48ff8e959c379187e05/images/Screenshot%202023-01-21%20231044.png)

11. Click "Generate"
12. Copy the app password and paste it in your env file

   ![your app key](https://github.com/KevinNVM/smtp-env-setup/blob/0a98127758864b0973b1b48ff8e959c379187e05/images/Screenshot%202023-01-21%20231119.png)

