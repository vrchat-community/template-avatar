# VRChat Avatar Project Template

This repo makes it easy to start a new VRChat Avatar project!

<details>
<summary>

## I Wanna Go Fast
If you don't care about using source control and just want to make something quick:

</summary>

1. [Download this Zip](https://github.com/vrchat-community/template-avatar/archive/refs/heads/main.zip) and unpack it somewhere.
2. Go to "3. Open the Project" below.

</details>

<details>
<summary>

## I Want To Use Source Control
This template is set up to easily make your own GitHub projects, and we highly recommend you take this route.

</summary>

## 1. Make Your Own GitHub Project

Press [![Use This Template](https://user-images.githubusercontent.com/737888/185467681-e5fdb099-d99f-454b-8d9e-0760e5a6e588.png)](https://github.com/vrchat-community/template-avatar/generate)
to start a new GitHub project, and follow the directions there. This is an optional step but gets you started with using GitHub for source control so you'll always have a backup.

## 2. Clone or Download the Project

If you're not ready to use git yet, you can download a zip of your project by pressing the "Code" button and then "Download Zip".

If you're familiar with git, use your favorite client or the command line to clone your repository.

</details>

<details>
<summary>

## 3. Open the Project

</summary>

Use Unity 2022.3.6f1 to open the project. Press "OK" on the dialog that offers to download the required VRChat packages.
  
![image](https://user-images.githubusercontent.com/737888/185468226-33492169-c1f5-4b27-b5c4-83febb5e6e66.png)

</details>

<details>
<summary>

## 4. Load the Example Avatar

</summary>

Find the "VRChat SDK" item in the menu bar at the top of the Unity Editor window, press it to open, then choose "Samples > Avatar Dynamics Robot Avatar".

  ![avatar-sample](https://user-images.githubusercontent.com/737888/185468680-43c8900d-37df-45c1-979c-8c7007c99d3e.png)

Once the scene opens, choose "File > Save As..." and give the scene a new name.

Then modify the avatar however you'd like - you can [read all about our Avatars 3.0 System here](https://docs.vrchat.com/docs/avatars-30).

</details>

<details>
<summary>

## 5. Test Your Avatar

</summary>

When you're ready to try out your Avatar, find and choose the menu item "VRChat SDK > Show Control Panel". 
* Sign into your VRChat Account in the "Authentication" tab.
* Switch to the "Builder" tab and choose "Build & Test".
* After a quick build process, you should see a popup with the message "Test Avatar Built".
  
  ![image](https://user-images.githubusercontent.com/737888/185468821-425a132f-3271-4096-b6d1-fb5b70b51c10.png)

* Launch VRChat, open your Avatars menu (click on "Avatars" in your Quick Menu) and look in the "Other" section. Your test avatar will have a temporary name based on the name of the GameObject with the VRC Avatar Descriptor on it. The default name will be "SDK: Tutorial_Robot_Avatar_Dynamics_Demo_v1".
* Select your Test Avatar and press "Test This Avatar" on the left-hand side of your menu.

You should now be testing your custom avatar!

</details>

<details>
<summary>

## 6. Publish Your Avatar

</summary>

When you're ready to publish your Avatar so you can use it regularly:
* Return to the VRChat SDK Control Panel in your Unity Project
* Switch to the "Builder" tab and press "Build and Publish for Windows". 
* This will build your Avatar and add some publishing options to your Game window.
* Fill out the required fields "Avatar Name", "Description", "Sharing", and check the terms box "the above information is accurate...".
* Press "Upload".

Return to VRChat - your Avatar should now show up under "My Creations" at the top of the Avatar listing. Choose it and enjoy!

</details>
