

# iMessage

## About App
This is a simple iOS swift 4 app created for learning purpose. It is a tutorial on how to build an instant messaging app with functionalities similar to whatsapp. 

## What you will learn

* How to integrate third party libraries in your app.
* How to store data in the cloud using Firebase.
* How to query the Firebase database.
* How to use Firebase for user authentication.
* How to work with a UITableView.
* How to use custom cells in a Table View.
* How to embed View Controllers in a Navigation Controller and understanding the navigation stack.
* How to create Segues for navigation.
* How to make custom .xib files to modify native design components.
* Using Grand Central Dispatch to queue asynchronous tasks.


## The Tutorial: step by step approach
#step 1:
Launch Xcode and start up an xcode project in your prefered directory on your device.

#step 2: 
Create a git repository for your app. Goodnes for github is that you can now create a private repo for free. You can make use of this advantage to create a private repo for your app.

#step 3: 
Add a readme file and make your first commit to your repo

#step 4:
Now it is time to create your view. I am a fan of the MVC design pattern and will encourage you to do thesame though it is not entirely compulsory but it is absolutely relevant. 
On storyboard.main, create 4 scenes; 
- the welcome scene (should have register and login button displayed)
-register scene (should have form to collect users details for registration)
-login scene (should have form to collect user's login details)
-chat room scene (this is where the actual chatting takes place)
Ensure to wrap all your scenes in a navigation controller scene

#step 5: 
Create a view controller file for each scene and link the view to view controller

#step 6:
now it is time to create your database in firebase. Register for an account if you dont already have one

#step 7:
Install framework and third party libraries through cocoapods. Integrate cocoapods to your app

#step 8:
Build your app at this stage to ensure that your app is bug free. It is also a good time to commit what you have done so far to your online repo

#step 9:
write the logic for your registration scene

#step 10: 
write the login for your login scene

#step 11:
now it is time to implement the UITableview logic to your chat room scene.
It is required to create a custom tableview and extend the default table view.
Hint: Ensure to map the datasource and delegate of your tableview interphase to the view controller

#step 12:

