# Crushly-Description
### Note: The Source Code for this Mobile Application is private. Please email me at khan993@umd.edu to request access




## Application Onboarding Task Flow
![Screen Shot 2021-08-16 at 9 18 58 PM](https://user-images.githubusercontent.com/44535434/129648636-3e43f8ee-97b9-4f6e-a855-27a996e5d369.png)

- **Splash Screen:** Crushly opens up to a Splash Screen with our logo. The app connect to the back end server while the splash screen is being displayed.
- **Sign Up:** The user enters their credentails like Name, DOB, email etc. Finally, the user adds their photos which are stored in a S3 bucket on the backend.
- **Sign In:** The user is authenticated through this route.

![Screen Shot 2021-08-16 at 10 04 30 PM](https://user-images.githubusercontent.com/44535434/129652777-137e7a5c-1e3c-4749-afef-ea2c18e1d046.png)




## Landing Page
![Screen Shot 2021-08-16 at 9 31 05 PM](https://user-images.githubusercontent.com/44535434/129652869-158563c9-034d-4105-8276-533fb91b75f3.png)
After successfully authenticating, the user is directed to Crushly's landing page. The landing page showcases the recommendations we have for you based on your school and interests. Additionally, the landing page has the following features:
- **Crush:** Press the Crush button if you admire the recommended user profile. The recommended user will be notified of this action.
- **Secret Crush:** Press the Secret Crush button if you are a *shy* person. The recommended user will *not* be notified of this action.
- **Access Notifications:** Access all the recent notifications we have for the user
- **Search:** Search for any user
- **View Profile:** The user can double to view the recommended user's profile. The profile will showcase pictures and the recommended user's *Crush Count*
Finally, the user can choose to swipe up or down to keep viewing new recommendations or come back to the old ones.

![Screen Shot 2021-08-16 at 9 59 19 PM](https://user-images.githubusercontent.com/44535434/129652179-bff8e696-9aeb-49b2-aaab-c271c94f8796.png)




## Messaging
![Screen Shot 2021-08-16 at 10 03 02 PM](https://user-images.githubusercontent.com/44535434/129652292-d9d67e0f-bde4-4d80-8367-c64f3507142c.png)

The user can swipe left to view their conversations. The user can only message the following:
- Users that have a Crush on user (Secret Crush included)
- Users that the user has a Crush on (Secret Crush included)

![Screen Shot 2021-08-16 at 10 08 53 PM](https://user-images.githubusercontent.com/44535434/129653620-becc2a23-cbd6-469c-92fc-0120b4e970e6.png)

*Conversations with secretly crushed users in anonymous, i.e, all publically viewable credentials and the profile picture are hidden.* 

- #### Report and Block
The user can choose to report another user (User 2) and add a description in the dialog box as to why they have chosen to report User 2. User can also block communication with User 2.

- #### Request to reveal identity
At any point, a user can request an anonymous user to reveal their identity. The anonymous user can choose not to do so. 




## My profile
The user can use this page to add or remove pictures from their profile as well as change permissible user credentials. The User can also view the profiles of all the users that have a Crush on the User. The user can also logout from accessing the settings page from this page.
![Screen Shot 2021-08-16 at 10 06 59 PM](https://user-images.githubusercontent.com/44535434/129652489-3ceedf44-1310-4719-bc31-ba443883a4ae.png)
