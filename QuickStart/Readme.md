# GUIDE TO CREATE A UNO PLATFORM PROJECT IN VISUAL STUDIO

In this document we will see how to create a Uno Platform project from scratch in Visual Studio.

The first thing we will have to check is if we have the extension of Uno added in Visual Studio.

### 1. Install extension Uno in Visual Studio 

First, we have to create our project. Uno will be installed to the corresponding extension in Visual Studio. For this we must:
![]()
- Start Visual Studio using “Continue without code”.
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/Start_VisualStudio.PNG)
- At the top we click on Extensions -> Manage Extensions.
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/Extensions.PNG)
-               We expand the “Online” section, look for Uno Platform and click on Download
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/ManageExtensions.PNG)
-               Once downloaded, you will have to restart Visual Studio to make sure everything is correct. After that we can start creating our Uno project

### 2.    Create a new project
![]()
-               We start Visual Studio again but this time through “Create a new Project”.
-               We look for Uno Platform and select “Cross-Platform App (Uno Platform).
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/Create_Project.PNG)
-               We setup our new project by filling in the following fields and, once finished, click on “Create”. We have already created our new Uno project.
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/Configure_Project.PNG)
- As can see, we have created a solution with 5 projects inside:
                -               UWP
                -               Android
                -               WASM
                -               iOS
                -               Shared
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/Create_Solution.PNG)
In the “shared” folder is going to be where we will create the parts that share the rest of the projects. The other 4 projects correspond to each of the platforms where we can deploy our application, these projects will also include the data that are exclusive to each one like you see on the pictures.

Next, we will see how our application looks on different platforms:
•              UWP:
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/CaptureUWP.PNG)
•              Android:
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/CaptureAndroid.png)
•              iOS:
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/CaptureiOS.png)
•              Wasm:
![](https://raw.githubusercontent.com/idiWork/UnoPlatform/master/QuickStart/docs/assets/CapturaWasm.PNG)
