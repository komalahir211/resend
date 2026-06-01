# Setup Instructions

## Step 1: Create a Blank WordPress Instance
1. Open your local server tool (e.g., LocalWP).
2. Create a new blank WordPress site.
3. You can use any temporary admin username and password during this setup, as they will be replaced when the website is imported.

## Step 2: Download & Extract the Website Files
1. Download the resend.zip file from this repository.
2. Extract the ZIP file.
3. Inside the extracted folder, you will find the website backup file (.wpress) and a credentials.txt file containing the WordPress login credentials.

## Step 3: Install the Migration Plugin
1. Log in to your newly created local WordPress dashboard.
2. Navigate to Plugins → Add New.
3. Search for All-in-One WP Migration.
4. Install and activate the plugin.

> Note: If the .wpress file exceeds your local server's upload limit, install the All-in-One WP Migration File Extension plugin to remove the restriction.

## Step 4: Import the Website
1. Go to All-in-One WP Migration → Import.
2. Drag and drop the .wpress file extracted from resend.zip.
3. Wait for the upload and import process to complete.
4. When prompted, click Proceed to overwrite the existing database, media, themes, plugins, and settings.
5. After the import is completed, WordPress will automatically log you out.

## Step 5: Log In Using the Provided Credentials
1. Open the credentials.txt file from the extracted folder.
2. Use the provided username and password to log in to the WordPress Admin dashboard.

## Step 6: Refresh Permalinks
1. Navigate to Settings → Permalinks.
2. Without changing any settings, scroll down and click Save Changes.
3. Click Save Changes once more.

This refreshes WordPress rewrite rules and helps prevent 404 errors on internal pages.
