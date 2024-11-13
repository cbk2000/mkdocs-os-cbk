---
layout: "layout"
title:  "Simple Documentation"
hide:
  - navigation
  - toc
---

## How to Prepare the Source Code

- **Download the Source Code:**  
   Click the link below to download the latest version of the source code as a ZIP file:  
   [Download Source Code](https://github.com/cbk2000/mkdocs-os-cbk/archive/refs/heads/master.zip)

- **Extract the ZIP File:**  
   Once downloaded, unzip the `mkdocs-os-cbk-master.zip` file to access the source code files.

- **Create Your GitHub Repository and Push Initial Changes**  
  Start by creating a GitHub repository to host your MkDocs project if you haven’t already.  
  [Create New Repository on GitHub](https://github.com/new)

    Once your repository is ready, use the following commands to set it up locally, add your files, commit, and push them to GitHub. After this initial push, a `gh-pages` branch will be created automatically:

```bash
git init
git remote add origin <your github repository link>
git branch -M master
git add .
git commit -m "<your message>"
git push -u origin master
```

* **Set Up GitHub Pages Deployment:**  
    - Go to your repository’s settings, open the **Pages** section, and set the source to **Deploy from a branch**.  
     <img src="../assets/images/template/deployment_source.jpg" alt="Deployment Source" width="800"/>
    - Set the deployment branch to `gh-pages`.  
     <img src="../assets/images/template/deployment_branch.jpg" alt="Deployment Branch" width="800"/>
    - Save your changes.  
     <img src="../assets/images/template/deployment_save.jpg" alt="Save Deployment Settings" width="800"/>

* **Access Your Deployed Site and Add the Deployed Site Link to Repository Details:**  
    - After the workflow completes successfully, refresh the GitHub Pages section and visit the GitHub Pages URL to access your MkDocs site.  
   <img src="../assets/images/template/deployment_link.jpg" alt="Deployment Link" width="800"/>
   
    - To make it easy for visitors to find your site, add the GitHub Pages URL to the repository details or the README file.  
     <img src="../assets/images/template/repository_about.jpg" alt="Repository About Section" width="800"/>
    - In the "About" section, click the gear icon to add the URL under "Website" and save your changes.  
     <img src="../assets/images/template/about_website.jpg" alt="About Website" width="800"/>
    - Save your changes.