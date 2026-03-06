# Deployment Guide for 000webhost

## Overview
This guide provides step-by-step instructions for deploying your application on 000webhost, including setup of the database, configuration, and common troubleshooting steps.

## Prerequisites
Before you begin, ensure you have the following:
- An account on 000webhost
- Access to your project files
- Database credentials (if applicable)

## Step 1: Create a New Project on 000webhost
1. Log in to your 000webhost account.
2. Click on "Create New Site."
3. Choose "Start from scratch."
4. Set your website name and password.
5. Click "Create."

## Step 2: Upload Files
1. In the dashboard, go to the "File Manager."
2. Click on "Upload Files."
3. Drag and drop your project files into the root directory (or use the upload button).

## Step 3: Set Up the Database
1. In your 000webhost dashboard, click on "Manage Database."
2. Click on "Create New Database."
3. Enter a name for your database and click "Create."
4. After that, note down the database name, username, and password.

## Step 4: Configure Database Settings
1. Open your application's configuration file (usually `config.php` or `.env`).
2. Enter the following details:
   - Database Host: `localhost`
   - Database Name: your_database_name
   - Database User: your_database_username
   - Database Password: your_database_password

## Step 5: Import Database (if applicable)
1. Go to "Manage Database" and click on "PHPMyAdmin."
2. Select your database.
3. Click on the "Import" tab and upload your `.sql` file if you have one.

## Step 6: Configure Website Settings
1. Back in the dashboard, go to "Settings."  
2. Set your website offline mode as needed.

## Step 7: Troubleshooting
- **Error 500**: Check your `.htaccess` file for any misconfigurations.
- **Database Connection Error**: Ensure your database credentials are correct and that the database is created.

## Conclusion
You are now ready to launch your application on 000webhost! Refer to the 000webhost support for additional assistance as needed.