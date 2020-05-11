# Send-OTP-Through-Firebase

1. Create a Firebase project
Skip if you already have one
Go to Firebase Console and sign with your Google account.
Click on “Add Project”
Enter a project name, check the terms agreement checkbox
Click “Create Project”

Create a Firebase Project

2. Create a Firebase App
Click on the gear icon beside Project Overview and choose “Project Settings”

Click on “Add App”

Enter a name and click “Register App”

Copy the firebaseConfig object as well as the firebase.initializeApp . We will use these later.

3. Enable Phone Authentication
Click on “Authentication” on the sidebar

Click on “Sign In Method”

Click on the pencil icon on the “Phone” item, and click on the toggle on the top right to enable phone authentication.

Click on the “Phone numbers for testing” dropdown and add a fake a phone number with fake code for testing.

Using phone numbers from this list will allow authentication without consuming your usage quota and sending actual SMS.
