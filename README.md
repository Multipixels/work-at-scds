# My Work at the Sherman Centre

Thank you to all my coworkers at the Sherman Centre for making my summer co-op term a wonderful experience! None of what I did would have happened if it weren't for them. Please check them out at [scds.ca](https://scds.ca) and check out some of the fabulous resources they have made available to all.

## Summer 2024

### Projects

- Updated our analytics board that reports the website and video usage by users using the Echo360 API, the Google Analytics platform, and LookerStudio.
  - Created a program that would query the Echo360 API, filter out videos created by the centre, and collect/aggregate relevant statistics and data for over 200 workshop videos automatically using Python and GitHub Actions.
- Started to co-design and develop a README generator tool that would help researchers create READMEs for their datasets with ease. Prototyped in HTML/CSS/JS, to be moved to Drupal over the Fall.

### Website Content

- Helped move our public GitHub Pages content over to a custom domain (learn.scds.ca).
- Published interactive digital zines created by students from our [CMST&MM 720 Data Cultures graduate course](https://learn.scds.ca/events23-24/zines.html). Some examples include:
  - [Validating or Violating: An Introspective Look on How Health Information is Shared Online](https://learn.scds.ca/events23-24/zines/validating-or-violating.html) by Elsie Sheppard
  - [All AI Is Local: Rejecting the Permicious Myth of Universalism in AI Discourse](https://learn.scds.ca/events23-24/zines/all-ai-is-local.html) by Elisabeth Greve

### Logistics

- Maintained, updated, and archived old repositories, websites, and videos.
- Created and updated technical documentation about the systems and processes in the centre.
- Revamped the centre's workshop creation process (from planning all the way to release) to minimize redundancy and maximize efficiency.


## Summer 2023

### Website Theme and Module Template

Using the [Just the Docs](https://github.com/just-the-docs/just-the-docs) template as a base, I customized the website theme to match the Sherman Centre's and McMaster's branding, as well as adding a few features on top of the theme to increase productivity and usability. Some of these features include:
- An automatically generated "Previous Page" and "Next Page" button system, based on a page's navigation order, as well as its parent/children properties.
- Some more config settings that allow for easy to customize things like:
  - The module credits, located in the footer of each page.
  - A module's subtitle, also located in the footer of each page.
  - Two banners that can be showcased at the bottom of the navigation menu.
  - Enabling/disabling automatic "previous/next" button navigation
- Social share previews
- Collapsible, non-viewable "folders"

All this is internally documented by myself so that future coworkers and employees can easily pick up the template and theme to use or even expand upon.

Alongside the theme, I also designed a template for which our asynchronous learning modules should follow, based on coworker and student feedback. This template is designed to be easy to use for just about anyone and comes with a tutorial on setting up the GitHub Pages for the module, as well as a "kitchen sink" of common markdown and HTML elements.

### Asynchronous Learning Modules

As a Learning Resource Development Assistant, I've also developed some asynchronous learning modules based on workshop content that the Sherman Centre has run in the past. Module content topics varies from introductory data analysis, digital scholarship, and even research data management. 

Modules I created content for:
- [Getting Started with GitHub and GitHub Pages](https://scds.github.io/github-pages/) (content based on Jay Brodeur's workshop)
- [Introduction to Python](https://scds.github.io/intro-python/) (content based on Vivek Jadon's workshop)
- [Introduction to R](https://scds.github.io/intro-r/) (content based on Vivek Jadon's workshop)
- [Introduction to Git](https://scds.github.io/intro-git/) (content derived from [The Carpentries](https://carpentries.org/))
- [Introduction to LaTeX](https://scds.github.io/intro-latex/) (content based on John Fink's workshop)
- [Introduction to SPSS](https://scds.github.io/intro-spss/) (content based on Vivek Jadon's workshop)
- [Best Practices for Managing Data in Your Research](https://scds.github.io/rdm-best-practices/) (content based on Jay Brodeur's workshop)

Modules I assisted in regarding formatting:
- [Pre-Processing Textual Data](https://scds.github.io/text-analysis-1/) (content by Devon Mordell)
- [Named Entity Recognition](https://scds.github.io/text-analysis-2/) (content by Devon Mordell)
- [Exploring Themes with Topic Modeling](https://scds.github.io/text-analysis-3/) (content by Devon Mordell)

### Other Projects

As part of a task to shift some videos from one platform to another, I created a Python script that converts SRT subtitle files to VTT subtitle files. Later I edited this script to also allow for shifting of time stamp, to fix some video subtitle files that were off by +- 3 seconds.

In another project, I used GitHub Actions to mass-rebuild repositories hosting Github Pages, allowing for updates to be made to the main theme repository without having to manaully rebuild each repo that pulls off of it.

## Articles and Blog Posts about My Work

- McMaster Library: [Students of summer: Meet Richie](https://library.mcmaster.ca/news/students-summer-meet-richie)
- SCDS: [Meet Our Team: Summer Students Shrey Acharya and Richie Motorgeanu](https://scds.ca/meet-our-team-summer-students-shrey-acharya-and-richie-motorgeanu/)
- SCDS: [New Asynchronous Learning Modules: Self-Paced Lessons on Python and R](https://scds.ca/r-python-modules/)
- SCDS: [New Asynchronous Learning Modules: Self-Paced Lessons on Data Analysis, File Organization, Interactive Fiction, and Scientific Publishing](https://scds.ca/new-asynchronous-learning-modules-self-paced-lessons-on-data-analysis-file-organization-interactive-fiction-and-scientific-publishing/)
