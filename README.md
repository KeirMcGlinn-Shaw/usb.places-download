# usb.places

usb.places is a tour app developed for use by prospective students and their guests when visiting the university

## Getting Started
These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites
What you will need to run this project

* Android Studio Version 3.6.3

  * We suggest using Android Studio Version 3.6.3 to run this project on your local machine
  * If you **do not** have this version of Android Studio then you can get it from <https://developer.android.com/studio>
  * **Alternatively**, we have a guide in the setup section of this README for making adjustments to the project to allow you to run it with an older version of Android Studio

* An Android mobile device or Android Virtual Device
  * If you intend to use an Android Virtual Device. Please read the section in this README about setting up GPS on your Virtual Device
  
### Setup
A guide to downloading this project and getting it running on your machine

#### If you have Android Studio Version 3.6.3
1. Download the zip file from our website: https://usbplaces.myportfolio.com/download
2. Extract the project folder from the .zip
3. Open the extracted folder with Android studio
4. Run the 'app' using an emulator or USB debugging

#### If you are running an older version of Android Studio
1. Download the zip file from our website: https://usbplaces.myportfolio.com/download
2. Extract the project folder from the .zip
3. Open the extracted folder with Android studio
4. Navigate to the build.gradle file at /usbplaces/build.gradle
5. Change the dependencies classpath (on line 10) to match you current version of Android Studio
**For example, for Android Studio Version 3.5.3, change the following:**
```gradle
classpath 'com.android.tools.build:gradle:3.6.3'
```
**To**
```gradle
classpath 'com.android.tools.build:gradle:3.5.3'
```
6. Sync the project (Android Studio should prompt you to sync the project when you make any change to build.gradle)
7. Once the sync is complete, run the 'app' using an emulator or USB debugging

#### Setting up your Android Virtual Device
1. Create your Android Virtual Device running **Android Version 8.0 or later**
2. Run your Virtual Device from the AVD manager in Android Studio
3. On your Virtual Device's control panel, select the extended controls option
4. In the Location tab of extended controls, select IMPORT GPX/KML
5. Navigate to and select usbplaces/Location_setter.gpx
6. In the location tab, select the SET LOCATION button
7. Your device should now show your location as outside Newcastle Central Station. You are now ready to run the app on your phone

## Built with
usb.places is built with [Android Oreo (8.0)](https://www.android.com/versions/oreo-8-0/ "https://www.android.com/versions/oreo-8-0/")

## Authors
* **Keir McGlinn-Shaw** - *Lead front-end developer* - [KeirMcGlinn-Shaw](https://github.com/KeirMcGlinn-Shaw)
* **Piotr Kolodziejski** - *Lead back-end developer* - [Peter019](https://github.com/Peter019)
* **Karolina Pieskute** - *Developer* - [sweetdarkness](https://github.com/sweetdarkness)
* **Arturs Spaks** - *Developer* - [ArthurShpak](https://github.com/ArthurShpak)
* **Diana Slepikaite** - *Developer* -
* **Kian Hudson** - *Developer* - [kian-hudson](https://github.com/kian-hudson)


## Acknowledgments
* **Harry Sahota** - *Team Leader* - [HarryIsSecured](https://github.com/HarryIsSecured)
* **Ben Greenow** - *Lead Designer* - [bengreenow](https://github.com/bengreenow)
* **Joe Marks** - *Designer* -
