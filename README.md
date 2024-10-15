<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Liping-LZ/awesome-DSDO">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Awesome-DSDO</h3>

  <p align="center">
    An awesome repository of open-source resources for DSDO students!
    <br />
    <a href="https://github.com/Liping-LZ/awesome-DSDO"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/Liping-LZ/awesome-DSDO/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/Liping-LZ/awesome-DSDO/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#resources">Resources</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Welcome to Data Science and Digital Operations specialism! 

I am creating this repository to put together useful open-source resources for you to learn Python coding and enhance your data science skills. Here are two main sections in this repository: one for coding and another for data science. Please start with programming and use these resources as complementary resources to your module content. You are expected to check these learning materials independently in your spare time outside the class. And this is not a compulsory task for you to complete your degree. It's all up to you how you would use the resources provided to you. 

I have categorised the resources to help you find out the right resources you need. There might be overlaps in terms of content, so you do not have to go through all the materials one by one. I have highlighted some particular resources as highly recommended, thus you can start with those resources if that's easier for you. 

This repository will be open to all DSDO students throughout the academic year. If there are more students from other specialisms in eBM who are interested in learning Python and data science, feel free to share this repository with them. 

Feel free to `Star` or `Folk` this repository for use. 

Hope you enjoy learning with us. 

Please jump into the next section to get started.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Here is a quick instruction on how you can better use this repository. 

### Prerequisites

This repository is mainly for MSc e-Business Management students, specifically students from DSDO specialism. 
For using this repository, we assume that you have basic knowledge about Python and data science. 
This repository is not replacing the module content, but as additional resources for DSDO students. 

### Installing Python

All the resources are Python-based. You are expected to install Python locally or have access to Python IDE on Cloud. Please check the below tutorial for Python installation.

#### Setting Up Your Programming Environment

A programming environment is a space where you write, test, and run your code. Think of it as a workshop where you have all the tools you need to build and test your projects.

**- Local vs. Online Environments**

You have two main choices:

Local Environment: This is set up on your own computer. You'll need to install some software.
Online Environment: This is hosted on the web. No installations needed. Just open a browser, go to a website, and start coding.

**- Python Files vs. Python Notebooks**

You may use two types of Python files:

Python File (.py): This is a standard file where you write Python code. It's like a text document but for Python scripts.
Python Notebook (.ipynb): This is an interactive document where you can mix text, code, and outputs. It's great for experiments, data analysis, and teaching.

#### Using Online Environment for Running Python
In most of the DSDO modules, we will be using online environment (Google Colab) since it is easy to access and does not require any complex installation. And we will be using Python notebook since Colab basically is a hosted Jupyter Notebook service that requires no setup to use and provides free access to computing resources, including GPUs and TPUs.

In Google Colab, you are writing your codes in Jupyter Notebook, but you are able to download your codes into either types of file (.py or .ipynb). Just click "File" on the menu and then move to "Download" in the drop-down menu and you should see two options - "Download .ipynb" and "Download .py". And then you can choose what you want. If you are running your codes through Terminal in your local machine, .py file is usually recommended. Also, if you are building web apps in Python, .py file is also recommended. In most of cases, you can use notebook file directly for coding and saving file.

The DSDO tutors will be mainly sharing the codes through Google Colab and GitHub, so you can directly open the codes in Colab and then save the codes to your Google Drive or download the codes. 

#### Setting Up Your Local Programming Environment

Online environment might not be ideal. If you have more resources in your own machine, you might prefer to run the program locally on your own machine. 

If you want to run locally, here is the guidance:

**Option 1: Installing Anaconda and Python and use Jupyter Notebook**

We are recommending installl Python through Anaconda distribution. This will simplify the package management and deployment. The distribution includes data-science packages suitable for Windows, Linux, and macOS. This will make it much easier to install and use python and other add-ons.

Firstly, visit https://www.anaconda.com/download from your browser of choice. The correct version for your operating system (Windows or Mac or Linux) can be selected (if this does not happen automatically) by clicking on the appropriate logo at the top of the page. Irrespective of your operation system, you are suggested to choose graphical installer. For Windows, select the appropriate bit-type for your machine (usually 64-bits), and for Mac select the appropriate one depending on whether you are using Macbook with Intel processor or with Apple silicon (introduced in 2021 or later).

Once it is downloaded, run the downloaded executable file to start installing. Follow the on-screen instructions and accept the default settings.Once the installation is complete, launch Anaconda Navigator from the Start menu.Here we recommend you use Jupyter Notebook to start coding. Once the Anaconda Navigator is launched, you should be able to see "Jupyter Notebook" on the menu. Simply click "Launch", you will see a kernel window (terminal window) starts first and then a browser window where you will be able to create folder and file to edit and run codes.

With Anaconda, you can also access other text editor or IDE to edit and run your codes. For example, you can also use VSCode, or PyCharm or Spyder, up to your choice.

**Option 2: Installing Python independently**

1) Go to Python's official website. Download the latest version.
2) Run the installer and follow the prompts.
3) Using a Text Editor with Python

While installing Python provides you with the essential tools to run and execute scripts, it's highly recommended to use a text editor alongside it.

A text editor is a software application that allows you to write and edit plain text files. Unlike word processors, text editors don't add formatting to text, making them ideal for coding. They often come with features like syntax highlighting, line numbering, and auto-completion, which can significantly enhance your coding experience and efficiency.

Microsoft VSCode (https://code.visualstudio.com/) is one of the recommendations that you can go for. It's free and lightweight. But it has many extensions. You can add tools for almost any coding task. Plus, it works with Python notebooks, making it a viable option for students on either specialism.

You can also use Sublime Text (https://www.sublimetext.com/), which is very easy to use and very lightweight.

If you are a beginner, we would suggest you install through Anaconda as it comes with lots of ready-to-use libraries and packages and it reduces lots of efforts.


<!-- How-to-guide -->
## How you should use the resources



<!-- RESOURCES -->
## Resources

### Learning Python
According to the 2024 Developer Survey (Stack Overflow, 2024)(https://survey.stackoverflow.co/2024/technology#most-popular-technologies-language), Python is ranked No.3 as one of the most used programming languages in the developer community. Specifically, this survey revealed that Python is also the most learned coding language as it might be one of 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

We will continue updating this repository to make it better, and we'd love to hear your feedback.

We might make mistakes or there might be something missing. If you spot any errors or bugs, please [Report Bug](https://github.com/Liping-LZ/awesome-DSDO/issues/new?labels=bug&template=bug-report---.md) and describe the issues and submit the report. You could also click the "Report Bug" button on the top. 

We also welcome any good suggestions. If you have any suggestions for this repository, please [Request Feature](https://github.com/Liping-LZ/awesome-DSDO/issues/new?labels=enhancement&template=feature-request---.md) to tell us what you would like us to add to this repository.

You could also email me at liping.zheng.1@warwick.ac.uk for any other requests. I am more than happy to have a chat with you and update the repository. 

### Top contributors:

<a href="https://github.com/Liping-LZ/awesome-DSDO/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Liping-LZ/awesome-DSDO" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Liping Zheng - liping.zheng.1@warwick.ac.uk


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template/tree/main)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Liping-LZ/awesome-DSDO.svg?style=for-the-badge
[contributors-url]: https://github.com/Liping-LZ/awesome-DSDO/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Liping-LZ/awesome-DSDO.svg?style=for-the-badge
[forks-url]: https://github.com/Liping-LZ/awesome-DSDO/network/members
[stars-shield]: https://img.shields.io/github/stars/Liping-LZ/awesome-DSDO.svg?style=for-the-badge
[stars-url]: https://github.com/Liping-LZ/awesome-DSDO/stargazers
[issues-shield]: https://img.shields.io/github/issues/Liping-LZ/awesome-DSDO.svg?style=for-the-badge
[issues-url]: https://github.com/Liping-LZ/awesome-DSDO/issues
[license-shield]: https://img.shields.io/github/license/Liping-LZ/awesome-DSDO.svg?style=for-the-badge
[license-url]: https://github.com/Liping-LZ/awesome-DSDO/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/liping-zheng-23a71a92
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
