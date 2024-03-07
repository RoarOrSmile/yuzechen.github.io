# How to host and format a resume
This README aims to instruct computer science students step-by-step how to format with a Jekyll template and host a resume on GitHub pages.
In this process, Etter's Modern Technical Writing principles are constantly applied.


## Prerequisites
- [A GitHub account](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)
- [A resume formatted in Markdown (.md file)](https://www.markdownguide.org/)
- [Basic knowledge of Git and Markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

For those unfamiliar with Markdown, [here's a comprehensive Markdown tutorial](https://www.markdowntutorial.com/) to get you started.


***
## **practical steps** 
* [Prerequisites](#Prerequisites)
* [Purpose](#Why-We-Chose-Markdow)
* [Instructions](#Getting-Started)
   * [Write your resume](#Getting-Started)
   * [Creating the Repository](#Creating-the-Repository)
   * [Add Your Resume](#Add-Your-Resume)
   * [Enable GitHub Pages](#Enable-GitHub-Pages)
   * [Chosing your Jekyll Template](#Chosing-your-Jekyll-Template)
   * [Hosting an Resume](#Hosting-an-Resume)
* [More Resources](#More-Resources)
* [Authors and Acknowledgments](#Authors-and-Acknowledgments)
* [FAQs](#FAQs)


 ### Why We Chose Markdown
Andrew Etter, in his influential book Modern Technical Writing, advocates for the democratization of content creation by making it accessible to as broad an audience as possible. One of the core tenets he discusses is the importance of utilizing lightweight markup languages to facilitate easier contribution and collaboration. Markdown, as highlighted by Etter, embodies this philosophy perfectly. Its simplicity and user-friendly syntax make it an ideal choice for writers and contributors of all skill levels. This ease of learning and use aligns with Etter's vision of encouraging more people to contribute, ensuring that technical writing and documentation are not gatekept behind complex tools. By choosing Markdown, we're not just adopting a tool for writing; we're embracing a methodology that lowers barriers to entry and fosters a more inclusive environment for sharing knowledge.

***
## Getting Started 

### Write your resume 
1. How to write markdown resume[The Markdown Resume](https://mszep.github.io/pandoc_resume/)
2. Change your resume Markdown file name to ```index.md```

### Creating the Repository
In the realm of technical documentation and code management, the challenge of efficiently storing and updating materials is paramount. Echoing the insights of Andrew Etter in Modern Technical Writing, there's a pronounced preference for distributed version control systems (DVCS) among developers. DVCS stands out for its superior performance, offline capability, and enhanced concurrency management for files. Among various DVCS platforms, GitHub emerges as a widely embraced tool, favored for its intuitive interface and robust functionality. In today's development landscape, initiating a new project often begins with the creation of a GitHub repository. This practice not only symbolizes the commencement of a new venture but also empowers developers with the ability to manage multiple branches. Such versatility facilitates continuous updates and progress tracking, embodying the project's evolving nature in a dynamic and collaborative environment.

- Sign into your GitHub account.
- Click the “New repository” button to create a new repository.
- Name the repository `<your-username>.github.io`, where `<your-username>` is your GitHub username.
- It is recommended to initialize the repository with a `README.md` file.

### Add Your Resume

- Save your resume as a Markdown file, recommended name `index.md`, which will serve as the homepage.
- Use Git to push this file to your repository.
```bash
git add index.md
git commit -m "Add resume"
git push origin master
```

### Enable GitHub Pages

To make your resume accessible online through GitHub Pages, follow these steps:

- **Navigate to your repository settings**: Click on the "Settings" tab at the top of your repository.
- **Locate the GitHub Pages section**: Scroll down until you find the "GitHub Pages" area.
- **Select the source**: Use the "Source" drop-down menu to select the `main` branch as the content source for GitHub Pages.
- **Choose a theme (Optional)**: You can improve the appearance of your page by selecting a theme. This is optional, as your Markdown file will be rendered using the default GitHub style if you do not choose a theme.
- **Save your changes**: After making your selection, GitHub will automatically generate a URL for your site, which is usually formatted as `https://<your-username>.github.io`.

![Enable GitHub Pages](https://media.giphy.com/media/Z6ODcBX0bMj8pucO3F/giphy.gif)

### Chosing your Jekyll Template

Recognizing the inherent benefits outlined by Etter, our choice of Jekyll as the theme set for constructing static websites is deliberate. Jekyll simplifies the process of content updates and site customization through its theme-centric architecture. Typically, adjustments to the website can be achieved by modifying settings within the theme files. This level of simplicity ensures that even those with minimal technical expertise can manage and update the website efficiently.Moreover, developers desiring more aesthetically pleasing and personalized pages are not constrained by Jekyll’s theming capabilities alone. The underlying structure of static websites allows for extensive customization through HTML and CSS, enabling developers to tailor the look and feel of their sites to match their unique preferences or branding requirements. This blend of simplicity for basic use cases and flexibility for more complex customizations embodies the core advantages of static websites as extolled by Etter.In essence, static websites serve as a powerful tool for developers, providing a balance between ease of use and the potential for sophisticated website design and functionality. By leveraging tools like Jekyll, developers can efficiently manage their documentation and project pages, ensuring that their content is not only accessible but also presented in a manner that aligns with their vision and standards.


1. Chose your theme [Supported themes](https://pages.github.com/themes/).
2. Copy the code lines in **Usage** section of ```README.md```.
3. Go back to your own main page of repository.
4. Click the **"Add file"** in the main page of repository.
5. Click the **"Create new file"**.
6. Using ```_config.yml``` as the file name.
7. [How to write out a config file](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)
7. Click the **"Commit new file"** at the bottom of page.

### Hosting an Resume
Andrew Etter advocates for the use of websites over PDFs for information dissemination, emphasizing the dynamic and accessible nature of web-based documents. Unlike PDFs, which are static, require local storage, and tend to grow in size, websites offer a flexible platform for publishing documents. This approach enables continuous updates, ensuring documentation remains in lockstep with project versions. Following this philosophy, we leverage GitHub Pages to host our documents, offering a seamless way to keep content current. This method not only aligns with modern technical writing practices but also allows for easy updates to personal portfolios or resumes, simply by editing a Markdown file in the repository's main page. This strategy underscores the importance of adaptability and accessibility in technical documentation, reflecting a move towards more agile and user-friendly content management systems.

1. Click the **"Add file"** in the main page of repository.
2. Click the **"Upload files"**.
3. Drag ```index.md``` (the Resume Markdown file) to the corresponding box.
4. Click the **"Commit changes"** at the bottom of page.
5. Click the **"github pages"** at the bottom right of the main page of the repository
6. Click the **"View deployment"** to visit the GitHub page.
7. Save the address of GitHub page 


![github page resume](https://media.giphy.com/media/82uv1o96nl3yCj1vob/giphy.gif)




***
## More Resources

- ["Modern Technical Writing" by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [5 markdown editors I recommend trying](https://opensource.com/article/21/10/markdown-editors)
- [Basic Syntax](https://www.markdownguide.org/basic-syntax)  
***
## Authors and Acknowledgments

#### GitHub Page Template
- [Ben Balter](https://github.com/benbalter)

#### Authors
- Yuze Chen

#### Group Members/Peer Editors




***
## Frequently Asked Questions (FAQs)

### How Does Markdown Streamline Content Creation Compared to Traditional Word Processors?

- **Ease of Use**: Markdown's syntax is designed to be quick to learn and easy to use, emphasizing the readability and writability of content. This makes it ideal for writers who prefer to focus on their text without the distraction of complex formatting options.
  
- **Versatility and Portability**: Markdown files are plain text, meaning they can be created and edited with a simple text editor on any operating system. This portability ensures that documents are accessible and editable across different platforms and devices, unlike files created in some proprietary word processors.
  
- **Direct Web Publishing**: Markdown's compatibility with HTML allows for straightforward conversion to web formats, facilitating direct publishing on the internet. This seamless transition from document to webpage streamlines the process of sharing content online.

### What Should I Do If My GitHub Pages Site Is Not Displaying My Resume?

- **Check the File Location**: Your `index.md` file must be located in the root directory of your GitHub repository. If it's in a subfolder, GitHub Pages won't automatically recognize it as the main content for your site.

- **Review GitHub Pages Settings**: In your repository settings, make sure GitHub Pages is configured to serve the correct branch and folder. For a resume, you typically want it set to the root of the main branch.

- **Inspect Front Matter**: If you're using Jekyll themes with GitHub Pages, ensure your `index.md` includes the necessary front matter at the top of the file. Even a simple front matter block like `---` (at the beginning and end) can be enough for Jekyll to process the file.
