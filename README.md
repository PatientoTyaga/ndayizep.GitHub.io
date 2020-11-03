# How to Host your Resume on GitHub Pages
------------------------------------------
 
## Introduction
------------------------------------------
This README describes the steps to post a resume on GITHUB pages using strategies described in Etter's book Modern Technical communication.

## Prerequisites
-----------------------------------------
1. **Possess basic understanding of how Markdown works.** You can click [here](https://commonmark.org/help/) to get to know the basics. 
2. **Use Markdown to make your Resume**. Check below on point 4 for link to a markdown text editor you can use.
3. **Have/create a GitHub account**. You can visit [the GitHub website](https://github.com) to login/create an account where you will be hosting your resume.
4. **Have/install text editor Atom**. You can use this to make your resume and transfer it to your GitHub account. [Click here](https://atom.io) to access the download page
5. **Have/install GitHub desktop application**. [This link](https://desktop.github.com) should take you to the download page. We will be using this application to transfer the Markdown file to the GitHub website.

## Instructions
---------------------------------------
**Hosting your Resume**

First thing we want to do here is create our resume in the form of a static website as suggested in Etters book. This is much better than having your resume in pdf/.docx format. It may sound like a difficult thing to do, having your resume as a static website but fear not, it is pretty simple and no you don't have to do crazy amounts of coding.

**Step 1: Creating repository**
1) Open the GitHub desktop application that we downloaded earlier.
2) On the "Let's Get started page", click on "Create a New Repository on your Hard Drive".
3) You want to name your file as "username.GitHub.io". For instance, if my user name if moses then it will be "moses.GitHub.io".
4) Click on the check mark "Initialize this repository with a README", to ensure a README file is created. 
5) Click on "Create Repository".

Below is a demonstration of how you would carry out the instructions above.

![](gitHubRepo.gif)

**Step 2: Opening repository with Atom and formatting resume**

As Etter suggests, we are going to use a lightweight markup in this case atom to format our resumes and readme files.
1) On your desktop, open the Atom application.
2) On the top right, click on "Open a Project".
3) Once clicked, a pop up will appear where you will locate your file "username.GitHub.io" that we created in step 1. Click on this to select. Your repository will appear on the top left hand side.
4) Right click on the repository and click on add new file and create a yourResume.md file and click on the enter button.
5) Using the Markdown link provided earlier, you can go ahead and start writing your resume on your newly created file.
6) Once done, save your files by being on the formatted page and holding control/command button and click on "S" to save.

**Step 3: Publishing resume online at GitHub**

1) Go back to the GitHub Desktop application and you should see the changes made on Atom reflected here
2) Make sure both your files are selected/check marked
3) On the bottom left hand side, you will have a text box with a button "Commit to main". You can put anything in the text box and then click on commit to begin the process of pushing our repository to GitHub
4) Once done, on the top of the page click on "Publish repository"
5) Pop-up will appear and go ahead and click on "Publish". 
6) That's it! Go to your GitHub page and you will see your repository there.

## Resources
---------------------------------------
Markdown Resources
- [Getting Started with Markdown](https://www.markdownguide.org/getting-started/)
- [Markdown Cheat Sheet](https://commonmark.org/help/)
- [Markdown Quick Tutorial](https://commonmark.org/help/tutorial/)

Access to Etter's book
- [Etter's Book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

Access to GitHub Desktop application
- [GitHub Desktop application](https://desktop.github.com)

## Authors and Acknowledgments
-------------------------------------------
Author(s): Patient Ndayizeye

## FAQ
------------------------------------------
**Why is Markdown better than a word processor?**
With Markdown, you can modify/update your content at anytime/almost instantly and it enables you to keep your content in sync with the latest software release which wouldn't be possible if storing your content in a word processor.

**Why is my resume not showing up?**
It might be that during the publishing of your repository, the resume.md file was not checkmarked/selected. Ensure there is a blue tick/check mark on your GitHub desktop app before commiting to main and hitting on publish.
