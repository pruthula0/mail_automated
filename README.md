# mail_automated
 Node.js based app that is able to respond to emails sent to your Gmail mailbox while you’re out on a vacation. 
 
What should the app do?
The app should check for new emails in a given Gmail ID
💡
You need to implement the “Login with google” API for this
The app should send replies to Emails that have no prior replies
💡
The app should identify and isolate the email threads in which no prior email has been sent by you. This means that the app should only reply to first time email threads sent by others to your mailbox.
The email that you send as a reply can have any content you’d like, it doesn’t matter.
The app should add a Label to the email and move the email to the label
💡
After sending the reply, the email should be tagged with a label in Gmail. Feel free to name the label anything. If the label is not created already, you’ll need to create it. 
Use Google’s APIs to accomplish this
The app should repeat this sequence of steps 1-3 in random intervals of 45 to 120 seconds
What things should be tested properly?
Use your own Gmail to write and test the app. You can send an email to yourself.
The app should make sure that no double replies are sent to any email at any point. Every email that qualifies the criterion should be replied back with one and only one auto reply.
Technical guidelines for building the app:
Use Google APIs to implement the app. Go though the API documentation linked below and decide the best approach for each of the modules that you need to build.  
💡
https://developers.google.com/gmail/api/guides


