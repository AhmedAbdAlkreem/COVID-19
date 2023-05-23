# first_stat_in_flutter

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


# We work in three parts in this project:
1) First part build CNN Model and preprocessing in the image.
2) Second part build simple mobile app.
3) 3th part connect Mobile App with Deep Learning Model.

## First Part:
In the first part work on the model and deal with preprocessing of image a bout using four function to handle all the problem in
the image and can read it with easy way the first function to transform image to matrix and deal with all image RGB and Gray 
the second function deal with real all image from files with the path and extention of the image the 3th function is to
transform all the image to matrix and called the first function that transform one image and the 4th function use to call all
three function in one block to load all images.

## Second Part:
In the secound part work on build simple mobile app that contain two screen the first screen called splash screen make animation 
still 5 secound and then transform to the second screen that contain two image and two bottom the first bottom to upload image 
from galary then show it in the position of old image and the second bottom to send image to model and return the value of label
of image and show it in Mobile App.


## The two screen of Mobile App:


![WhatsApp Image 2023-05-23 at 6 59 12 PM](https://github.com/AhmedAbdAlkreem/COVID-19/assets/109450704/312d6b99-d849-4f6c-8e58-34d2370e7e48) 

![WhatsApp Image 2023-05-23 at 6 59 12 PM(1)](https://github.com/AhmedAbdAlkreem/COVID-19/assets/109450704/5e5f2934-8067-46dd-ad14-ff0a7d99bf0d)


## 3th Part:
In the 3th part work on connect Mobile App with CNN Model using Flask API we build API with flask to make request from model and
return the value of label and show it in mobile app we make it about make the labtop is server and passing IP of labtop to 
Mobile App and can any device in the same network to use the API.






