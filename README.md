# How to host and format a resume
This README aims to instruct computer science students step-by-step how to format with a Jekyll template and host a resume on GitHub pages.
In this process, Etter's Modern Technical Writing principles are constantly applied.


Prerequisites
A GitHub account
A resume formatted in Markdown (.md file)
Basic knowledge of Git and Markdown syntax
For those unfamiliar with Markdown, here's a comprehensive Markdown tutorial to get you started.

## Prerequisites
- [A GitHub account](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)
- [A resume formatted in Markdown (.md file)](https://www.markdownguide.org/)
- [Basic knowledge of Git and Markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

For those unfamiliar with Markdown, [here's a comprehensive Markdown tutorial](https://www.markdowntutorial.com/) to get you started.


***
## **practical steps** 
* [Prerequisites](#Prerequisites)
* [Instructions](#Instructions)
   * [Why We Chose Markdown](#Why-We-Chose-Markdow)
   * [Creating the Repository](#Creating-the-Repository)
   * [Setting Up the Repository Page](#Setting-Up-the-Repository-Page)
   * [Selecting the Jekyll Template](#Selecting-the-Jekyll-Template)
   * [Hosting a Resume on GitHub Pages](#Hosting-a-Resume-on-GitHub-Pages)
* [More Resources](#More-Resources)
* [Authors and Acknowledgments](#Authors-and-Acknowledgments)
* [FAQs](#FAQs)



***
## Getting Started 

**Markdown is a markup language which translates into HTML.**

#### Installing The Markdown Editors
- [Markdown Editors by OS](#More-Resources)
- [Online Markdown Editors](#More-Resources)
#### Markdown Tutorial
- [Good Tutorial](#More-Resources)
- [Basic Syntax](#More-Resources)

#### The Resume Formatted in Markdown
- [The Example](https://andre-loo.github.io/)

#### The Account for GitHub
- [Sign Up](https://github.com/join)

***
## Instructions

 ### Why We Chose Markdown
 Andrew Etter states that everyone can be a contributor. In order to find an easy and free way to achieve this goal, using lightweight markup languages is an excellent choice, since they are easy to learn and it is better to make contributions. Markdown is the most widely used of them in the world.

1. Change your resume Markdown file name to ```index.md```

### Creating the Repository
The storage and updating of documentation and code is always a core issue for developers. Andrew Etter prefers the distributed version control system(DVCS), which offers better performance and allows users to work offline. Developers are also able to handle the concurrency of the same file better. GitHub is one of the representatives of DVCS that is loved by the majority of people. In the present day, many developers treat the creation of a new repository as the starting point for their development. A repository represents a complete project, so they can control multiple branches to continuously update the development progress.

1. Log into your [GitHub](https://github.com/) account.
2. Click the **'+'** symbol at the top right corner of website.
3. Select the **'New repository'**.
4. Enter ```YourUserName.github.io``` as the repository name. (e.g, andre-loo.github.io)
5. Check the box **"Add a README file"**.
6. Click the **"Create repository"** to finish.

### Setting Up the Repository Page

1. Click the gear button **"Settings"** in the main page of repository.
2. Select **Pages** at the left side of code and automation.
3. Change the **"None"** status to **"main"** in Branch section.
4. Click the **Save** button.

### Selecting the Jekyll Template
Andrew Etter states that static websites are speedy, simple, portable and secure. For documents that need to be constantly changed, technicians do need a simple and user-friendly way to iterate. Static websites provide an easy way to do this. In other words, they are tools that allow developers to update the content of your documents at any time without any additional environment. Therefore, we choose Jekyll as the theme set for the static website. We usually only need to change some setting information in the theme file to be able to adjust the pages of the static website. Developers who need more aesthetic and beautiful pages can also personalize their static websites through HTML and CSS.

1. Enter the website [Supported themes](https://pages.github.com/themes/).
2. Pick one of your favorite name of themes.
3. Click the **"preview the theme to see what it looks like"** or    **"Theme preview"** in ```README.md```.
4. Does this style of the theme make you happy?
- If no, go back to website [Supported themes](https://pages.github.com/themes/).
- If yes, copy the code lines in **Usage** section of ```README.md```.
5. Go back to your own main page of repository.
6. Click the **"Add file"** in the main page of repository.
7. Select the **"Create new file"**.
8. Enter ```_config.yml``` as the file name.
9. Paste the code lines (from step 4) as contents of file. 
10. Click the **"Commit new file"** at the bottom of page.

### Hosting a Resume on GitHub Pages
Andrew Etter encourages saving information through websites instead of PDFs. PDFs can only be saved on your local hard drive, and they inevitably increase in size. In contrast, developers can publish documents on a static website. Moreover, they can keep updating the content according to the project version, always keeping the project version in sync with the document content. Therefore, we use the GitHub page as a website for continuously updating the document. Even if your personal experience and personal skills are enhanced afterward, you only need to modify your resume markdown file in the main page of repository.

1. Click the **"Add file"** in the main page of repository.
2. Select the **"Upload files"**.
3. Drag ```index.md``` (the Resume Markdown file) to the corresponding box.
4. Click the **"Commit changes"** at the bottom of page.
5. Click the **"github-pages"** at the bottom right of the main page of the repository
6. Click the **"View deployment"** to visit the GitHub page.
7. Record the address of GitHub page (e.g, https://andre-loo.github.io/)

![A GIF showing my own github page resume](https://media.giphy.com/media/dmC3I5XDB8NGwrBPYD/giphy.gif)





***
## More Resources
- [Markdown Editors by OS](https://www.oberlo.ca/blog/markdown-editors)
- [Online Markdown Editors](https://techwiser.com/online-markdown-editor/)
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [Basic Syntax](https://www.markdownguide.org/basic-syntax)  
- ["Modern Technical Writing" by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

***
## Authors and Acknowledgments

#### Authors
- Junyi Lu

#### Group Members/Peer Editors
- Zac Kolton
- Benjamin Paspaporn
- Evan Murray

#### GitHub Page Template
- [Ben Balter](https://github.com/benbalter)

***
## FAQs
#### Why is Markdown better than a word processor?
- Markdown allows HTML syntax so we can directly create static websites without any obstacles, compared to word's poor HTML export which requires more manipulation and time.
- In fact, word still requires payment to access. However, Markdown is mostly free and easy to use.
- Markdown has no platform requirements. As a user, you only need to choose between the online or OS version and you can start using it immediately.

#### Why is my resume not showing up?
- Double check the resume file name, since it has to same as ```index.md```
- Make sure ```index.md``` is not empty file