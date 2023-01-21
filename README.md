# smtp-env-setup
setup email smtp gmail utk aplikasi php (laravel, etc)

# How-to

How to get security key for your gmail account:

1. Go to myaccount.google.com and choose your account
2. Go to "Security" tab on the sidebar


   ![image](https://github.com/KevinNVM/smtp-env-setup/blob/dc54bc1e49ee9b8fa0bb2dc7eaa71c7485e51096/images/Screenshot%202023-01-21%20230632.png)

3. Activate 2 Step Verification
4. After that, go back to "Security" tab and click on "App Password" to setup a new app
5. Click "select app" and choose "Other (custom name) 
6. Type in your app name eg: Laravel App
7. Click "Generate"
8. Copy the app password and paste it in your env file

