
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
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc quis augue nisl. Duis dictum ipsum quis mauris cursus faucibus. Vivamus vitae eros at odio tempor pellentesque. Phasellus vel convallis massa. Integer commodo arcu augue, a iaculis velit auctor a. Vivamus varius nisl eu nulla tristique elementum. Morbi et justo elit. Quisque aliquet lorem id eros fermentum, vitae luctus metus malesuada.

Here's why:
* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc quis augue nisl. 
* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc quis augue nisl. 
* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc quis augue nisl. 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed nec ultricies nunc. Maecenas placerat neque massa, vel sodales libero scelerisque et. Donec purus urna, ultrices non sapien ac, mattis venenatis ex. Donec nec tellus tristique, sodales massa condimentum, laoreet velit. Fusce suscipit elementum turpis id pellentesque. 

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
    4. Click on Window > Asset Management > Addressabl >Groups
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





### Build iOS 
1. Click File > Build Setting. (Ctrl + Shift + B)
2. Select iOS.
3. Click on "switch Platform".
4. wait till switch complete.
5. Build 
6. Open build in Xcode and run




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
