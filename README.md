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
    <li><a href="#resources">Resources</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
# About The Project

Welcome to Data Science and Digital Operations specialism! 

I am creating this repository to put together useful open-source resources for you to learn Python coding and enhance your data science skills. Here are two main sections in this repository: one for coding and another for data science. Please start with programming and use these resources as complementary resources to your module content. You are expected to check these learning materials independently in your spare time outside the class. And this is not a compulsory task for you to complete your degree. It's all up to you how you would use the resources provided to you. 

I have categorised the resources to help you find out the right resources you need. There might be overlaps in terms of content, so you do not have to go through all the materials one by one. I have provided some more information about the shared resources and how you could use them. Please read them before using the resources.

This repository will be open to all DSDO students throughout the academic year. If there are more students from other specialisms in eBM who are interested in learning Python and data science, feel free to share this repository with them. 

Feel free to `Star` or `Folk` this repository for use. 

Hope you enjoy learning with us. 

Please jump into the next section to get started.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
# Getting Started

Here is a quick instruction on how you can better use this repository. 

## Prerequisites

This repository is mainly for MSc e-Business Management students, specifically students from DSDO specialism. 
For using this repository, we assume that you have basic knowledge about Python and data science. 
This repository is not replacing the module content, but as additional resources for DSDO students. 

## Installing Python

All the resources are Python-based. You are expected to install Python locally or have access to Python IDE on Cloud. Please check the below tutorial for Python installation.

### Setting Up Your Programming Environment

A programming environment is a space where you write, test, and run your code. Think of it as a workshop where you have all the tools you need to build and test your projects.

**- Local vs. Online Environments**

  - Local Environment: This is set up on your own computer. You'll need to install some software.
  - Online Environment: This is hosted on the web. No installations needed. Just open a browser, go to a website, and start coding.

**- Python Files vs. Python Notebooks**

  - Python File (.py): This is a standard file where you write Python code. It's like a text document but for Python scripts.
  - Python Notebook (.ipynb): This is an interactive document where you can mix text, code, and outputs. It's great for experiments, data analysis, and teaching.

### Using Online Environment for Running Python
In most of the DSDO modules, we will be using online environment (Google Colab) since it is easy to access and does not require any complex installation. And we will be using Python notebook since Colab basically is a hosted Jupyter Notebook service that requires no setup to use and provides free access to computing resources, including GPUs and TPUs.

In Google Colab, you are writing your codes in Jupyter Notebook, but you are able to download your codes into either types of file (.py or .ipynb). Just click "File" on the menu and then move to "Download" in the drop-down menu and you should see two options - "Download .ipynb" and "Download .py". And then you can choose what you want. If you are running your codes through Terminal in your local machine, .py file is usually recommended. Also, if you are building web apps in Python, .py file is also recommended. In most of cases, you can use notebook file directly for coding and saving file.

The DSDO tutors will be mainly sharing the codes through Google Colab and GitHub, so you can directly open the codes in Colab and then save the codes to your Google Drive or download the codes. 

### Setting Up Your Local Programming Environment

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

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- RESOURCES -->
# Resources

## Learn Python
According to the 2024 Developer Survey (Stack Overflow, 2024)(https://survey.stackoverflow.co/2024/technology#most-popular-technologies-language), Python is ranked No.3 as one of the most used programming languages in the developer community. Specifically, this survey revealed that Python is also the most learned coding language, which reflects the high demand of Python in the market. 

Learning a new programming language requires long-term commitment. Building a good foundation at the very beginning and keeping up on practicing would be the key to the success. Here are some suggestions for you to learn Python, along with different resources. 

**If this is the first time you learn Python, I would suggest you start with the recommended book and eBM Python Bootcamp material designed by Jordan.**
- eBM Python Bootcamp: To be released on week 4 of eBF. Stay tuned.
- Recommended Python book:
  - [Python Crash Course](https://go.exlibris.link/TpWFr087)
  - [Learn Python the hard way](https://go.exlibris.link/TpWFr087)
  
  *Python Crash Course* is an awesome resource for Python beginners and is very hands-on and project-driven. It is brief and to the point. However, it might be quite fast-paced as you learn a lot at once in each chapter. If you prefer fast-paced learning or you have learned Python a bit previously and now you want to quickly refresh your knowledge and skills, then this book would be a great choice for you. *Learn Python the hard way* is another good book for learning Python, but what is different is that it contains lots of chapters and each chapter is not very packed. You will be learning through repetition. This would be great to further enhance your learning in the process.
  You do not have to read both books because there might be overlaps and it could be a waste of time. Just pick one as you prefer. Both books can be found in the library. Online links are shared above.

**If you prefer a more interactive way to learn coding, here are some other resources recommended to you.**
- [Futurecoder](https://futurecoder.io/) — This is a free and open-source platform and course for complete beginners to teach themselves programming in Python. It includes integrated debuggers, enhanced tracebacks, hints for exercises and more.
- [Tutor-edited Google Colab Python notebook]() - This is edited by eBM tutors and to provide students to learn to code in Python within Google Colab platform. Students are not required to install Python and no resources will be needed from local machines. This tutorial covers all the basic concepts of Python, alongside three exercises with answer. 

**If you have learned Python basics and you would like to enhance your skill, I would suggest you learn through doing small projects or you can jump into leaning data science directly.**
- [Tiny Python Projects](https://go.exlibris.link/0LJXNzcV) - This book is different from other books, which provides different projects for you to learn coding with Python. There are different projects in different level and you can pick up those you are interested in or you would like to challenge yourself. Thus, the way to use the book can be flexibile.

**You could keep practicing in your spare time by solving some Python problems like doing exercises.**
- [Hackerrank](https://www.hackerrank.com/domains/python) - Hackerrank is my personal preference as it does not require any register or login. You can open it and do solve problems any time you want. There are also different levels of problems. If you are preparing coding test in job seeking, this could be good practices for you. The industry used platform for coding test is [LeetCode](https://leetcode.com/).
- There are also some gaming-based platforms for practice, such as [Coding Game](https://www.codingame.com/start/), [Code Combat](https://codecombat.com/). Take what you prefer.

**Except for knowing the Python concepts, you also need to know the good practice of Python coding.**
Please read the [pep8 rules](https://pep8.org/?ref=blog.paperspace.com). It is important to know how to write and style python correctly.

## Learn Data Science

Data Science is a interdisciplinary subject, including different areas such as maths & statistics, big data & analytics, AI and machine learning. We will introduce different data science resources by topics.

### Maths and Statistics

Mathematics builds foundation for you to learn machine learning, so make sure you understand the basics well. Generally, what you have done in high school and Bachelor university should be enough for you to start machine learning. If you would like to further check, there are some areas you should look for.

- Linear Algebra
- Calculus
- Probability

Statistics is also very important for learning machine learning. You will be learning stastics in class in PSWS module, so you could just follow the module pace to equip yourself with stastics key concepts. Learning statistics well will help you better understand machine learning models and know to optimise the models with good understanding of parameters. 

If you prefer a simple and light-weighted read alongside your statistics module, here is the recommendation:

- [Naked statistics: stripping the dread from the data](https://go.exlibris.link/G0VChB7W)

### Big Data & Analytics

We will cover big data pipeple in the BDAO module and you will have chance to learn different concepts with big data including types of data, data retrieval, database for data data storage, data processing techniques, analytics and visualisation. There will be practical sessions for you to apply what you learn. 

If you would like to have some first ideas about big data and some key techniques, I am suggesting some extra reading for you.

#### Big Data

- [Big data: a revolution that will transform how we live, work, and think](https://go.exlibris.link/prCktgtH) - This is an enjoyable read because there are lots of story-telling to explore the impact of big data. The only drawback is that this book is published over 10 years ago, so some views might be outdated. But still think it could be quick read to understand big data.
- [Data Strategy : How to Profit from a World of Big Data, Analytics and Artificial Intelligence](https://go.exlibris.link/T9jzvT4d) - This book provides some interesting perspectives on how to source, use, manage and monetising data. The author Bernard Marr is quite well knowned in this area. He wrote a few books on big data.
- [Big data in practice](https://go.exlibris.link/nBwqXBTn) - If you like to read some real-world examples to understand the impacts of big data, then this is the book for you. This books is talking about how 45 successful companies used big data analytics to deliver extraordinary results.
- [Storytelling with data: a data visualization guide for business professionals](https://go.exlibris.link/Sn14p4Pt) -  This book could be an easy read for understanding the role of data visualisation for presenting insights from data. We will cover more about data visualisation in class and you have lots of chances to practice data visualisation in BDAO module. 

#### SQL (Structured Query Language)

We will be covering SQL in BDAO module and give you chances to use it in the project. However, you might wish to learn it beforehand. Here are some recommended resources for you. 

- [Practical SQL](https://go.exlibris.link/w4j31vby) - Practical SQL is an approachable and fast-paced guide to SQL (Structured Query Language), the standard programming language for defining, organizing, and exploring data in relational databases. 
- Optional: Sams Teach Yourself SQL in 10 Minutes - This is a book for learning SQL basics. It is designed for beginners to learn SQL and it is very easy to understand. However, this book is not available in the university library. You would need to buy it from Amazon or from second-hand book shops if you would like to have one for yourself.

There are also free online tutorials that you could follow, such as this free tutorial: [SQL Tutorial](https://www.sqltutorial.org/)

### AI, Machine Learning & Deep Learning

#### Artificial Intelligence

AI is a hot topic in recent years, thought it could be dated back to 1950s when we first time talk about AI. Here are some free resources available online for you to choose. However, most of them require register and login, so it is up to you whether you would like to go for them. The courses are mostly built by industry experts, so they tend to be more practical and easy to understand. 

- [Building AI](https://buildingai.elementsofai.com/) - Building AI is a free online course where you'll learn about the actual algorithms that make creating AI methods possible.
- [IBM's AI courses](https://cognitiveclass.ai/courses?type%5B%5D=all&sort%5B%5D=featured&topic%5B%5D=Artificial+Intelligence)) - Cognitiveclass.ai is a learning platplatform developed by IBM, which provides various courses on AI, Data Science and other emerging technologies. There are a bunch of free AI sources available on the platform labelled with difficulty level, so you can find anything suited your need. 

#### Machine Learning

You will learn all the key ceoncepts and techniques of machine learning in DSML module. As long as you follow the module and practices of skills in your spare time, that should be enough for you learn the machine learning basics. 

If you would like take some free online courses for learning machine learning in your spare time, here is the recommendation.

- [Google's Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
  This course covers practical introduction to machine learning, featuring a series of lessons with video lectures, interactive visualizations, and hands-on practice exercises.
  
Once you have a good theoretical and practical understanding of Machine Learning. You could get hands on some practical projects to apply what you have learned. 

- [Kaggle](https://www.kaggle.com/) is a data science community with different datasets and projects. And it is a great platform to apply what you have learned. You could start with some classic and simple projects and learn from others. For example, you could start with the [Titanic Classification](https://www.kaggle.com/c/titanic?ref=blog.paperspace.com) challenge on Kaggle and play around with the data and plug and play different Machine Learning models. There are also lots of coders sharing their solutions in Kaggle, so you can check other people's work and learn different techniques. You could build up your own porfolio by doing projects in Kaggle.
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/) is a great platform maintaining 670 datasets as a service to the machine learning community. You could find lots of datasets suitable for build your first machine leraning projects. Since it is a very popular platform for finding dataset within the machine learning community, you could find lots of examples on the internet if you would like to learn from others.

#### Deep Learning

Deep learning is a subset of machine learning, including more advanced techniques in AI area. You should have chance to know some basics of deep learning in your DSML module. But if you would like some extra learning materials to explore deep learning further, here are some free resources that you could use. 

- [Intro to Deep Learning using Tensorflow and Keras Course at Kaggle](https://www.kaggle.com/learn/intro-to-deep-learning)
- [Free online deep learning course](https://course.fast.ai/) - This fast.ai course is a practical Deep Learning course, which is designed for people with some coding experience, who want to learn how to apply deep learning and machine learning to practical problems. This course covers more depth and more practical content.

#### Other extra resources for AI, machine learning and deep learning

***YouTube channels*** - Watching YouTube videos could be an easy way to learn some practical concepts. It is usually more engaging and also free to access. However, they are more for personal use and not recommended to use as reference in your academic work. Below are some recommended channels from big tech companies - Google, Amazon & Microsoft. There are more other channels that you could explore further.

- [DeepMind](https://www.youtube.com/channel/UCP7jMXSY2xbc3KCAE0MHQ-A/videos)
- [Amazon - Machine Learning University](https://www.youtube.com/channel/UC12LqyqTQYbXatYS9AA7Nuw)
- [Microsoft Research](https://www.youtube.com/user/MicrosoftResearch)

***Blogs*** - It is always nice to hear some fresh thoughts on different topics within the data science community. They could be some sharing of practical skills or some personal views/thoughts on some recent news or trending technologies. It is great to get inspired through blogs. However, do not cite them as reference in your academic work because they might not be credible enough.

- [Towards Data Science](https://towardsdatascience.com/)
- [Towards Machine Learning](https://towardsml.com/)
- [Towards AI](https://medium.com/towards-artificial-intelligence)
- [MIT News](https://news.mit.edu/topic/artificial-intelligence2)
- [Becoming HumanAI](https://becominghuman.ai)
- [Machine Learning Mastery](https://machinelearningmastery.com/blog/)

***AI research in big companies*** - AI is the area with quick changes, so it is crucial to keep up on trends. Big companies are always leading the way as they are having very strong teams for research and tests on new technology and new areas. Here are some company websites you could follow.

- [Machine Learning at Apple](https://machinelearning.apple.com/)
- [AI at Uber](https://www.uber.com/us/en/uberai/)
- [AI at Microsoft](https://www.microsoft.com/en-us/ai)
- [AI Research at Google](https://ai.google/research/)
- [AI Research at Huawei](https://www.huawei.com/en/industry-insights/technology/ai)
- [Amazon Science](https://www.amazon.science/)
- [AI at Alibaba](https://damo.alibaba.com/labs/ai)
- [Data Science at Gojek](https://blog.gojekengineering.com/data-science/home)
- [Autopilot AI at Tesla](https://www.tesla.com/autopilotAI)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
# Contributing

We will continue updating this repository to make it better, and we'd love to hear your feedback.

We might make mistakes or there might be something missing. If you spot any errors or bugs, please [Report Bug](https://github.com/Liping-LZ/awesome-DSDO/issues/new?labels=bug&template=bug-report---.md) and describe the issues and submit the report. You could also click the "Report Bug" button on the top. 

We also welcome any good suggestions. If you have any suggestions for this repository, please [Request Feature](https://github.com/Liping-LZ/awesome-DSDO/issues/new?labels=enhancement&template=feature-request---.md) to tell us what you would like us to add to this repository.

You could also email me at liping.zheng.1@warwick.ac.uk for any other requests. I am more than happy to have a chat with you and update the repository. 

## Top contributors:

<a href="https://github.com/Liping-LZ/awesome-DSDO/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Liping-LZ/awesome-DSDO" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
# License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
# Contact

Liping Zheng - liping.zheng.1@warwick.ac.uk


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
# Acknowledgments

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
