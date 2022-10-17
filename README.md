# CS-360
Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The application that I developed is a simple weight tracking application. The application required a login screen that accesses a login database, a home screen that displays daily weight data from a seperate database, and the functionality to set a goal weight, add daily weight information, update previously inserted data, and delete previously inserted data. The requirements also called for the ability to send a notification if the goal weight was reached. This application was aimed at users who weren't looking for fancy features, just a quick and simple way to track and log their weight. Keeping this in mind, I decided that simplicity in design and quickness of navigation and operation were importnant to producing a successful application.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

My application ended up with 6 screens in total:
1.Login screen
2.Home screen
3.Add Weight screen
4.Set Goal screen
5.Edit Info screen
6.Delete info screen
Each of these screens stuck with a very minimalistic and simple design. The login screen contains the application logo, title, edit text boxes for username and password, and two buttons for creating user acocunts and loging in. The home screen is the most complex of all with the table view displaying the information from the database. It also contains several buttons allowing for setting a goal, adding daily weight info, editing info, and deleting info. The remaining screens are all laid out in the same manner. The only change is in the edit text boxes that ask for specific information based upon which screen you are on. Each of them has a submit button as well as a return button for if you decide to abandon the activity. Every screen eventually returns to the home screen keeping things simple and streamlined.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

I approached the process of coding based on how I felt the application should function. I started with the login activity as that is the first activity that a user encounters. From there, I set up the main database for storing information within the application and coded the home screen. Everything else past the home screen was coded and approached in a similar way as each screen performed a very similar function of taking in input and performing actions on the database itself.

How did you test to ensure your code was functional? Why is this process important and what did it reveal?

I used several try/catch/finally statements as well as switch/case statements that helped me in testing the applications functionality to ensure it was working properly. Typically with the try/catch/finally statements, I used dialogs in text views to display on the screen if the exception is caught. This is a very simple and easy to understand way to test functionality.

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

My biggest challenge was in coding the functionality. Designing the layout of each screen was quite simple. Figuring out how to initiate and utilize the databases was the most challenging. I watched many videos and ready many articles/tutorials in order to figure out the best most efficient way to implement the databases within my application.

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think my best screen was the login screen activity. It went and worked the smoothest. The home screen was a close second, but I still feel like it could be improved upon and made better.
