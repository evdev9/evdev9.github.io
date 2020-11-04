# README

# Purpose

This README has two goals:
1. To describe the practical steps of how to host and format a resume using Markdown, a Markdown editor, GitHub Pages and Jekyll
2. To relate the practical steps described to the general principles of current Technical Writing, as explained in Andrew Etter’s book *Modern Technical Writing*

# Prerequisites
Before working through these steps, there are few things you'll need:

- A Github Account
- A Resume Formatted in Markdown

Knowledge of Git and Git commmands is not nessesary\
[Markdown tutorial]

# Practical Steps: How to Host and Format a Resume
### Markdown

Markdown is a markup language with a plain-text formatting syntax, which translates into HTML. Compared to HTML, Markdown is much easier to learn and read. Markdown allows for fast and simple static website generation, and can also be used for email, or general word processing. 

**Markdown Editors:**\
Using a Markdown editor accelerates the formatting process, allows for exporting to multiple file types, and for formatting on any platform. Choose a Markdown editor to begin formatting your resume.

There are Many Markdown editors one can use: [A list of Markdown editors, by OS]\
\
The Markdown editor *Dillinger* was used to create this README:
* **Dillinger:**
    * Online cloud based Markdown editor
    * Loads into web-browser - no need to download or install an application
    * Allows for real-time preivew in either markdown format or HTML
    * Open source with a [public repository][dill] on GitHub.

A tutorial on how to use Markdown can be found in the 'More Resources' section of this README.

### Github Respository
Once you have formatted your resume using Markdown, you can begin to host your resume using Github Pages.\
Github allows for effective version control and collaboration for any project. Even when hosting a simple document such as a resume, these tools are a great asset.

First, you'll need to setup a Github repository to host your Github Pages site:
1. [Create a Github account] (if you haven't already) and log in
2. [Create a new repository]
3. Name the repository `username.github.io` where `username` is your Github username. You can find your github username by clicking your profile icon at the top right of the page.
4. Click the **Add a README file** checkbox
5. Click the  **Create repository** button

![How to create a repository](https://github.com/evdev9/evdev9.github.io/blob/main/createRepo.gif)

### Adding your Resume
The next step is to add your resume to the repository that will be transformed into a static site using Github Pages.

1. Click the **Add file** dropdown menu
2. Click **Upload files**
3. Drag your resume .md file into the box to add it to your repository
4. Click the **Commit changes** button at the bottom of the page
4. Navigate to your Github respository
5. Click the name of your resume file in your repository
6. Click the 'pencil' icon near the top right of your resume
7. At the top of the page, change the file name to `index.md`
8. Click the **Commit changes** button at the bottom of the page

![How to add your resume](https://github.com/evdev9/evdev9.github.io/blob/main/adding-resume.gif)

### Selecting a Jekyll theme for your site
Github pages is powered by Jekyll, a simple static site generator. You can select a Jekyll theme using the Github Pages intergration to stylize your resume.

How to select a Jekyll theme using Github Pages:
1. Navigate to your Github repository
2. Click on the **Settings** button at the top of the page
3. Scroll down to the **Github Pages** section
4. Under **Source**, using the **Branch** dropdown menu, ensure the "main" branch is selected
5. Click **Choose Theme**
6. Browse the Jekyll themes by clicking the thumbnails at the top of the page, and find one you like
7. Click **Select Theme** once you have made your choice
8. Click the **Commit changes** button at the bottom of the page

![How to select a Jekyll Theme](https://github.com/evdev9/evdev9.github.io/blob/main/JekyllTheme.gif)

### Viewing and editing your Github Pages Resume
- You can now view your resume in your web browser using the address `https://username.github.io` where `username` is your Github username.
- You can edit and reupload your resume .md file to update its contents on your site
- You can configure your Jekyll theme using the `_config.yml` file located in your respository. A tutorial on how to configure Jekyll themes can be found the the 'More Resources' section of this README.

![Viewing your Resume]()

# Relating Practical Steps

### General principles from Andrew Etter's Book: *Modern Technical Writing*
In his book *Modern Technical Writing*, Andrew Etter describes a series of guiding principles for technical writing in the software industry. In this section, I will define and relate a couple of those principles to the practical steps described above.

**Principle 1: Build a Website**
For this principle, Etter mentions that we should build and host websites, rather than distributing PDFs or other document files. Etter eludes to how documentation goes out of date, and will often require revision. Hosting content on a website allows for instant revision and access to your content, while a downloaded file does not.\

This principle relates to the entire process of hosting a resume on Github Pages, as a resume will require revision as time goes on. Whether it be new skills and qualifications you aquire, or new work experience, editing a pdf file and sending it to employers every time is both tedious and unnessesary.

**Principle 2: Use Lightweight Markup**
Here Etter describes how we should use a lightweight markup language to format our content. Writing in HTML or XML is cumbersome and completely unnessesary when a much easier solution such as Markdown exists to streamline the process. Lightweight markup languages are also more easily accessible when compared to other text formatting tools such as Word; there are lightweight markup options for almost every operation system, and on top of that, tools such as Markdown are free.\

This principle relates to the steps involved in learning and using Markdown to format a resume, as well as selecting a suitable Markdown editor for your operating system. Exporting a resume formatted using software such as Word into HTML, to be used on a static website, is much more difficult than with Markdown, as Markdown is built from the ground up to be easily translated into HTML.

# FAQs
### "Why is Markdown Better than a word processor?"
  - To start, compared to a word processor such as Word, Markdown is both more accessible and free to use. Markdown is also more widely supported, especially in use for static site generation, as Markdown is easily exportable into HTML which is used across the web. This also means version control tools such as Github can be used to collaborate with others and make instant updates. Markdown files are also signifignatly smaller when compared to files created using a word processor, meaning they can store many times more information with the same amount of space.

### "Why is my resume not showing up?"
There are a few things you can try to ensure your resume shows up on your Github Pages site:
- Ensure that you have named your repository `username.github.io` where `username` is your Github username. Your Github username can be found by clicking you profile icon at the the top right of the page once you are logged into Github.
- Ensure the "main" or "master" branch is selected in the **Branch** dropdown menu in your repository's **Settings**
- Ensure your resume is named `index.md` as opposed to `resume.md` or some other name
- Ensure your resume is formatted properly for Markdown, and is of **.md** file type. 
   - See the Markdown tutorial provided in the 'More Resources' Section

If all else fails, try creating a new repository and following the steps provided above again.

# More Resources
  - [Markdown Tutorial]
  - [Resume Formatted in Markdown]
  - [Jekyll theme Configuration tutorial]
  - [Andrew Etter's book: Modern Technical Writing]

# Authours and Acknowledgments
  - Kent Van, peer reviewer
  - Lucas Huynh, peer reviewer
  - Andrew Etter, author of *Modern Technical Writing*


   [Jekyll theme Configuration tutorial]: <https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll>
   [Create a Github account]: <https://github.com/join>
   [Create a new repository]: <https://github.com/new>
   [Markdown Tutorial]: <https://www.markdowntutorial.com/>
   [Resume Formatted in Markdown]: <https://www.markdowntutorial.com/>
   [A list of Markdown editors, by OS]: <https://www.oberlo.ca/blog/markdown-editors>
   [Andrew Etter's book: Modern Technical Writing]: <https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS>
