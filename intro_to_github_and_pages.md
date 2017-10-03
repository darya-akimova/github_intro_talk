Intro to GitHub and GitHub Pages
========================================================
author: Darya Akimova
date: 10/3/2017
width: 1440
height: 900

WCM Data Science Club


Clarification: Git vs GitHub
========================================================

![alt text](git_logo.png)

Git
- Version control system
- Projects and changes to them are stored in a repository (repo)
- Command line tool
- Repos are stored locally

***

![alt text](GitHub-Mark.png)

GitHub
- Hosting service for Git repos
- Used to share repos and collaborate or get feedback
- Can use either command line or a GUI
- Repos can be public or private


Why GitHub? 
========================================================

- Use it to share and download open source code
- Not just for sharing pure code - can share data analysis projects too!
- Great for a job app (if computational)
- Can get involved in open source projects
- Social aspect


Setting up a GitHub account 
========================================================

GitHub Free Account 
- Free to sign up
- Public repos only

Recommended: GitHub Developer Account
- Unlimited private repos
- Normally $7/month, but...
- Free for students through the Student Developer Pack:
https://education.github.com/pack


Basic Project Structure
========================================================

![alt text](branches_git.png)

Think branches


Other important terminology
========================================================

- Fork: copy the project to your own GitHub account
- Pull Request: a request to pull a fork back into the Master branch
- Commit: A "revision" or "snapshot" of a project 


Time for a quick GitHub tour!
========================================================

https://github.com/


You can host a website on GitHub!
========================================================

Pros:
- Don't have to think about hosting and everything that comes with it
- No ads for a free site
- Show off and share your code or analysis projects

***

Cons:
- One website per user (but unlimited project pages)
- Static page only
- Not complete beginner friendly


R Blogdown
========================================================

![alt text](blogdown.png)
- R package by Yihui Xie (Software Engineer at RStudio, best known for knitr package)
- Integrates R Markdown with Hugo (static website generator, https://gohugo.io/ )
- Makes it easy to create an R-focused project blog/website

Installation:
- require(devtools)
- devtools::install_github("rstudio/blogdown")


GitHub Pages process using R Blogdown package
========================================================

1. Make repo *username*.github.io
2. Create website using R blogdown::new_site(), edit as needed
3. Render page using blogdown::hugo_build()
4. Copy the contents of the public folder into the repo created in Step 1


Resources
========================================================

GitHub Pages:
https://pages.github.com/

R Blogdown book:
https://bookdown.org/yihui/blogdown/


