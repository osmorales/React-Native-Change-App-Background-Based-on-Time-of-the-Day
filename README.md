# React-Native-Change-App-Background-Based-on-Time-of-the-Day
This project targets to:
1. set background image for different screens of app
2. to change it dynamically based on the time of the day

About the App:
The app has two pages:
1. The Login Page
2. A Welcome Page
No Authentication has been applied on Login page as the app is developed to play with the background image only.
So if you click on "Access" button from Login page, even without putting a username and password, you will navigate to Welcome page.

How to Test the App:
- Load the App. You should land on the Login page.
- Considering that it is Daytime at your place (say 10:00 AM). Below is how the app will look:
<p align="center">
  <img src="https://github.com/abir4u/React-Native-Change-App-Background-Based-on-Time-of-the-Day/blob/master/Page%20Design/LoginDay.png" width="350"/>
</p>
- Click on "Access" button.
- You will be navigated to the Welcome page. Below is how the app will look:
<p align="center">
  <img src="https://github.com/abir4u/React-Native-Change-App-Background-Based-on-Time-of-the-Day/blob/master/Page%20Design/SecuredDay.png" width="350"/>
</p>
- Now change the time of your real/virtual device to some time after 6 PM (say 10:00 PM)
- Click on "Logout" button
- You will be navigated to Login page. Below is how the app will look:
<p align="center">
  <img src="https://github.com/abir4u/React-Native-Change-App-Background-Based-on-Time-of-the-Day/blob/master/Page%20Design/LoginNight.png" width="350"/>
</p>
- Notice how the same Login page looks different for different time of the day
- Now click on "Login" button again to navigate to Welcome page. Below is how the app will look:
<p align="center">
  <img src="https://github.com/abir4u/React-Native-Change-App-Background-Based-on-Time-of-the-Day/blob/master/Page%20Design/SecuredNight.png" width="350"/>
</p>
