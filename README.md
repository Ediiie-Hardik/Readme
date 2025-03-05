
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="128" height="128">
  </a>

  <h3 align="center">Lead School AR Book</h3>

  <p align="center">
    Lead School AR Book Docment that will boost your learning.
    <br />
    <a href="#"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#">View Demo</a>
    &middot;
    <a href="#">Report Bug</a>
    &middot;
    <a href="#">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Steps</a></li>
        <li><a href="#installation">Android setup</a></li>
        <li><a href="#installation">iOS setup</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

LEAD School is currently offering LEAD School@Home for all our partner schools parents. Your child can now attend live classes daily, attempt quizzes, ask doubts to their school teachers.

You can also join our LEAD School@Home program even if you are not part of a LEAD partner school, simply register your number and your child details to start your classes.
The LEAD School Student & Parent App allows parents of partner schools to track the progress of their child in school by keeping them updated on:
* Unit Progress: Know which units are completed and what your kid has learned.
* Attendance: Check your kids attendance in school for every day.
* Assessments: View reports on the student grade and scores by the student in different assessments.

We at Lead School define excellence as education that empowers students to be capable adults, responsible citizens and empathetic human beings. This is captured by our education mantra: LEARN.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

This project is build using following teck stack and external open source or custom plugin and framework developerd by Ediiie. 

[![Made with Unity](https://img.shields.io/badge/Made%20with-Unity-57b9d3.svg?style=for-the-badge&logo=unity)](https://unity3d.com)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Here is some instruction that will help you to setup this project locally and build and test.
To get a local copy up and running follow these simple example steps.

### Prerequisites

To run this project i am assuming you have install following in your system.
* UnityHub
  ```sh
  https://unity.com/download
  ```
* Unity3D  - 2022.3.39 or above
  ```sh
  https://unity.com/releases/editor/archive
  ```
* While install Unity must add Android , iOS , Winodw , WebGL and Visual Studio 

### Steps

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
2. Open Unity Hub
3. Click on "Add" button and then "Add project from disk"
4. Select your cloned project path 
5. Click on project and open for Android or iOS 
6. wait till project load 
7. click fix incase of getting any shader issues

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Android setup
1. Click File > Build Setting. (Ctrl + Shift + B)
2. Select Android.
3. Click on "switch Platform".
4. wait till switch complete.
5. How to Build Android APK 
    1. Check all modules prefab in "Assets  >> Ediiie >>  Resources" folder
    2. Click File > Build Setting. (Ctrl + Shift + B)
    3. Make sure 3 scene added in "Scene In Build" (Menu , Launcher_DataTest , ARI)
    4. Export project should mark as false
    5. Open Scene "Menu" Select GameInit Component > mark isTesting = true
    6. Build > Select path > Save 
6. How to create Addressable
    1. Check all modules prefab in "Assets  >> Ediiie >>  Resources" folder
    2. Rename "Resources" folder to "Addressable"
    3. Select Add prefab inside that folder and tick as Addressable from inspector 
    4. Click on Window > Asset Management > Addressable > Groups
    5. Expand Modules (default)
    6. Rename and keep only prefab name for example "Assets/Ediiie/Addressable/OSCI7C04" to "OSCI7C04"
    7. Build as new or previous build 
7. For Android Export for native
    1. Check all modules prefab in "Assets  >> Ediiie >>  Resources" folder
    2. Rename "Resources" folder to "Addressable"
    3. Click File > Build Setting. (Ctrl + Shift + B)
    4. remove  "Launcher_DataTest"  from "Scene In Build"
    5. Open Scene "Menu" Select GameInit Component > mark isTesting = false
    6. Export project should mark as true
    7. Click on Export 


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### iOS setup
1. Click File > Build Setting. (Ctrl + Shift + B)
2. Select iOS.
3. Click on "switch Platform".
4. wait till switch complete.
5. How to Build  
    1. Check all modules prefab in "Assets  >> Ediiie >>  Resources" folder
    2. Click File > Build Setting. (Ctrl + Shift + B)
    3. Make sure 3 scene added in "Scene In Build" (Menu , Launcher_DataTest , ARI)
    4. Open Scene "Menu" Select GameInit Component > mark isTesting = true
    5. Build > Select path > Save
    6. Open build in Xcode and build and run 
6. How to create Addressable
    1. Check all modules prefab in "Assets  >> Ediiie >>  Resources" folder
    2. Rename "Resources" folder to "Addressable"
    3. Select Add prefab inside that folder and tick as Addressable from inspector 
    4. Click on Window > Asset Management > Addressabl >Groups
    5. Expand Modules (default)
    6. Rename and keep only prefab name for example "Assets/Ediiie/Addressable/OSCI7C04" to "OSCI7C04"
    7. Build as new or previous build 
7. For iOS Export for native
    1. Check all modules prefab in "Assets  >> Ediiie >>  Resources" folder
    2. Rename "Resources" folder to "Addressable"
    3. Click Flutter from menubad >> iOS Export (releases) or (Ctrl + Altr + I) 
    4. Save on path 


    [product-screenshot]: images/screenshot.png
