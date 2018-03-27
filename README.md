# fireToDoApp

A Simple ToDo App written in React Native (v 0.54) that is connected to Firebase Real Time Database and is capable of 

1. Reading data from firebase
2. Writing data to firebase
3. Update in real time using FireBase Real Time Database
4. Add a to do 'task'
5. Delete a to do 'task' by marking it complete by clicking on the task.

I followed this [tutorial from the firebase blog](https://firebase.googleblog.com/2016/01/the-beginners-guide-to-react-native-and_84.html) but had to change a lot of code along the way
to account for import statements and spelling errors they made in the blog, causing the app to break at weird instances. If anyone was trying to follow that blog
but couldn't get through it, this repo is for you...

Usage: 
![Alt text](wlee367/fireToDoApp/blob/master/usage.gif?raw=true "Title")


Future Goals (Hopefully implemented very soon)

1. Render an automatic 'task id' such that a number is placed in front of each task in the app
2. Give the user a choice of letters or numbers in regards to goal #1.
3. Simple User Authentication using Firebase

##### To run the ios-application using Terminal (2 different terminals preferred)
```
react-native run-ios 
react-native start 
```
##### Alternatively, you can run the react-native app using XCode
```
open /Users/jasonlee/fireToDoApp/ios/fireToDoApp.xcodeproj
click the run button in XCode and everything should be automatically running for you
```

##### Requirements for running this project
1. React Native 0.54
2. XCode V 9.1 
3. Simulator V 10.0
