# Reading

## Google’s app publishing guide

1. How are releases and versioning related?
  - Each release must have a version number. Which allows each update or change can be distinctively identified by it's number. They can also be named,
    like each large macOS update having a unique name

2. What are the 5 main tasks you need to complete to prepare your application for release to the Google Play Store?
I'll just copy and paste these from the link. Way easier.

  Configure your app for release.
    - At a minimum, you need to make sure that logging is disabled and removed and that your release variant has debuggable false for Groovy or isDebuggable = false for Kotlin script set. You should also set your app's version information.
  
  Build and sign a release version of your app.
    - You can use the Gradle build files with the release build type to build and sign a release version of your app. For more information, see Build and run your app.
  
  Test the release version of your app.
    - Before you distribute your app, you should thoroughly test the release version on at least one target handset device and one target tablet device. Firebase Test Lab is useful for testing across a variety of devices and configurations.
  
  Update app resources for release.
    - Make sure that all app resources, such as multimedia files and graphics, are updated and included with your app or staged on the proper production servers.
  
  Prepare remote servers and services that your app depends on.
    - If your app depends on external servers or services, make sure they are secure and production ready. 
