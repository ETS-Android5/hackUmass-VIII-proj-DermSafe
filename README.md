Disclaimer: The project is originally forked from https://github.com/MRauf1/Skin-Cancer-Detector-Android, where only a very basic Skin Cancer Detector had been initially created. Our team repaired the project, and used it as our own canvas, heavily modified it, as well as added various features of our own to compliment and extend upon the original application. 

# DermSafe
## Overview: <a name="Overview"></a>

DermSafe is an Android application that helps people with various skin-related health diseases identify the same and act upon it as soon as possible. Users can either use their phone's camera to click pictures and/or upload photos of various different kinds of anomalies that occur on their skin on the app to know their cause. Users also get access to a wide variety of resources and contact information that would help them obtain the relevant treatment(s), as well as keep them well informed about their ailments and various preventive measures they can take.   

As time was a major constraint for this event, this particular application only focuses on Skin Cancer for the time being. However, we plan to train the model with various other datasets so that it can detect various different skin diseases, as well as help the user obtain proper treatment and care for the same. 

## Table of Contents:
1. [Overview](#Overview)
2. [Background](#Background)
3. [Additional Features](#features)
4. [How it Works](#how-it-works)
5. [How to Use](#using)

## Background: <a name="Background"></a>

This Repo contains the project done by:

Nikhil Jain (https://github.com/jainnikhil1005)

Kushagra Srivastava (https://github.com/k-u-sh)

Nhan Ton (https://github.com/tonducnhan)

Rebecca Wang (https://github.com/rebeccawang06)

For the 8th HackUmass hackathon. 

## Additional Features: <a name="features"></a>

The original idea was forked from https://github.com/MRauf1/Skin-Cancer-Detector-Android, and we have used that basic detector as a canvas to create an all-in-one health application, complete with features such as:

->References and Resources: Helps the user learn more about various Skin Diseases (at the time, focused on Skin Cancer)

->A complete UI/UX overhaul: Helps the user navigate the App with ease

->Emergency Contacting features: Helps the user get in contact with various individuals in order to get help whenever needed

-> Pictures and other sources to help people judge the severity of their ailment

## How it Works <a name="how-it-works"></a>

DermSafe uses TensorFlow and Keras in order to compare the User's uploaded photos to it's own database, from which it gives feedback on the type of the skin disease that the user is currently suffering from. Currently, the model is trained on very high quality images of various different types of skin cancer, and can therefore give almost accurate feedback on the kind of skin cancer that the user may be suffering with.

## How to Use <a name="usage"></a>

Upon installing the appliction on your Android device, you will be greeted with a home screen:

![Alt text](https://github.com/k-u-sh/hackUmass-VIII-proj-DermSafe/blob/master/71JvslYorPL._AC_SL1500_.jpg)

-> Load image: Lets you select an image from your gallery to upload to the app to judge. This is the main part of the app: it compares the uploaded picture to it's own trained dataset and determines the type of Skin Cancer the person is suffering from.

-> References: Provides information from various trusted sources 

-> Contact: Users can leave their information in case they want to reach out to a medical professional for any concerns.

-> Pictures: Provides different pictures for users to judge how severe their case is. 

#### Load Images: 

Clicking Load Images will direct the user to this screen: 

![Alt text](https://github.com/k-u-sh/hackUmass-VIII-proj-DermSafe/blob/master/scrn2.jpg)

Where the users can choose their photos to be uploaded to the app; upon which the app will predict the type of Skin Cancer they have.

Users can also use their phone's camera to take a picture and upload it to the app from this screen. 

#### References: 

Clicking References will allow users to browse various trusted sources and get more information on Skin Cancer.

![Alt text](https://github.com/k-u-sh/hackUmass-VIII-proj-DermSafe/blob/master/scrn3.jpg)

We intend to update the sources regularly with up-to-date information always at hand. 

#### Contact:

Clicking Contact will lead the user to this page: 

![Alt text](https://github.com/k-u-sh/hackUmass-VIII-proj-DermSafe/blob/master/scrn4.jpg)

Users can fill out a form and be directly conncted with a Medical Professional to get help with their questions and queries. 

#### Pictures: 

Clicking on Pictures will lead users to a page where they can see various examples of different Skin Cancer patients, and determine the severity of their ailments.

## Contribute:

We intend to release this project under the standard open-source MIT License, and anyone wishing to contribute to this project can do so via these links:

1.[Source Code: GitHub](https://github.com/k-u-sh/hackUmass-VIII-proj-DermSafe)
2.[Issue Tracker](https://github.com/k-u-sh/hackUmass-VIII-proj-DermSafe/issues)

## Future Improvements:

We plan to incorporate various future improvements in this Android Application in the future, some of which include: 

1. Google Maps Integration to direct Users to the nearest Hospital in case of requirement.

2. Emergency Contact Feature to notify the friends and family of the User in case of emergencies.

3. Incorporating a more fluid UI across the entire app, as well as porting it over to various other operating systems. 

4. Including a User-Account setup through which users can save their data on the cloud. 

## Support: 

If you are having issues with the software or any part of the same, feel free to utilize the GitHub Issue-Tracker. Alternatively, you can also reach out to us through my email: ksrivastava@umass.edu

## License:

This project is licensed under the MIT License
