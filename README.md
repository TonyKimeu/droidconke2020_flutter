<p align="center">
  <a href="https://github.com/droidconKE/droidconKE2020App">
    <img src="https://raw.githubusercontent.com/droidconKE/iconPack/master/androidIcon/android-icon-144x144.png" alt="droidconKE2020">
  </a>
  <h3 align="center">droidcon2020 Conference App</h3>
  <p align="center">
    The official  <a href="https://droidcon.co.ke/">DroidconKE 2020 Conference</a> App. Made with <a href="http://www.flutter.dev/">Flutter</a>
    <br>
   </p>
</p>

## ABOUT DroidconKE
Droidcon is a global conference focused on the engineering of Android applications. Droidcon provides a forum for developers to network with other developers, share techniques, announce apps and products, and to learn and teach.

This three-day developer focused gathering will be held at iHub Nairobi Kenya on August 6th to 8th 2020 and will be the largest of its kind in Africa. 

## ABOUT THE APP
### Features
The app will have the following features:
* Sessions
* Feed
* About
* Home
* Speakers
* Authentication
* Feedback (For both the Conference and each Session)

### Technical Details

#### Architectecture
The app will make use of the BLoC pattern to handle data flow and the provider package for state management and dependency injection.

The Business Logic Component (BLoC) pattern is a pattern created by Google and announced at Google I/O ’18. The BLoC pattern uses Reactive Programming to handle the flow of data within an app.

A BLoC stands as a middleman between a source of data in your app (e.g an API response) and widgets that need the data. It receives streams of events/data from the source, handles any required business logic and publishes streams of data changes to widgets that are interested in them.

<img src="https://miro.medium.com/max/1173/1*5kWI6Kg2sUj9QUTSapOWxQ.png" alt="BloC Architecture"></img>


#### Directory Structure
    android/      contains Android specific build files and resources
    ios/          contains iOS specific build files and resources
    assets/       contains resource files like images and fonts
    lib/          contains source files for the app    
      blocs/        contains assets definition
      models/       contains data class files 
      screens/      contains full screen widgets
      services/     contains service classes with specific functions like making `http` calls
      widgets/      contains reusable comonent widgets
      utils/        contains any misceleneous utility functions

#### Dependencies

## CREDITS
### Contributors
<a href="https://github.com/droidconKE/droidconke2020_flutter/graphs/contributors">
  <img src="https://contributors-img.firebaseapp.com/image?repo=droidconKE/droidconke2020_flutter" />
</a>

Made with [contributors-img](https://contributors-img.firebaseapp.com).



      



