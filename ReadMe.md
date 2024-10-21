# This Repository will allow you to practice using Git before touching the real project
**NOTE:** It can also serve as the bases for a web portfolio for each of you.

## 1. Create a Github Account
- Create an account on [Github](https://github.com/)
- Enter your email address and click `Sign up for Github`.
- Click `Continue`.
- Create a password and click `Continue`.
- Create a username and click `Continue`.
- Click `Continue`
- Verify your account by solving the puzzle.
- Go to your Email to and copy past launch code to Github.
- **CONGRATS YOU CREATED A GITHUB ACCOUNT**.

## 2. Install Git 
- Navigate to [GIT](https://git-scm.com/downloads) and download the installer for your OS.
- Go to your downloads folder and launch the installer.
- Click `Next`.
- Click `Next`.
- Select **Use Visual Studio Code as Git's default editor** and click `Next`.
- Select **Override the default branch name for new repositories** and **set to main** then click `Next`.
- Select **Git from command line and also from 3rd-party software** then click `Next`.
- Select **Use bundled OpenSSH** then click `Next`.
- Select **Use the OpenSSL library** then click `Next`.
- Select **Checkout Windows-style, commit Unix-style line endings** then click `Next`.
- Select **Use MinTTY (the default terminal of MSYS2)** then click `Next`.
- Select **Fast-forward or merge** then click `Next`.
- Select **Git Credential Manager** then click `Next`.
- Select **Enable file system Caching** then click `Next`.
- Select `Next`.
- Select `Install`.

## 3. Setting up Git Environment
- Launch VS Code application.
- Navigate the tool bar and Select **View -> Terminal**.
- Click the downward arrow in the top right corner of the terminal window and select **Git Bash**.
- In the terminal enter `git config --global user.email "<email>"` then hit **Enter**.
- In the terminal enter `git config --gobal user.name "<username>"` then hit **Enter**.

## 4. Creating Your Own Repository for Your Portfolio
- Navigate to [GitHub](https://github.com/) and sign in.
- Click on your icon in the top right corner and select `Your repositories`
- Click the green `New` button.
- Create your Repository name, description if desired, and click `Create Repository`.
- Copy and save the URL in the Quick Setup section **NOTE: This is your Repositories URL. We will use it in a later step.**.
- Create an empty folder named portfolio.
- Copy and past both the index.html  and style.css files as well as the images folder to your empty portfolio folder.
- Open your portfolio folder in VS Code **File -> Open Folder -> Selecte the file -> Click Select Folder**.
- Click `Yes, I trust the authors`.
- Open the Terminal **View -> Terminal**.
- In the terminal enter `git init` then hit **Enter**.
- In the terminal enter `git commit -m "first commit"` then hit **Enter**.
- In the terminal enter `git branch -M main` then hit **Enter**.
- In the terminal enter `git remote add origin <Ropsitory URL>` then hit **Enter**.
- In the terminal enter `git push -u origin main`.


## 5. Create a free account on [Font Awesome](https://fontawesome.com/)
- Click on **Start for Free** to make a free account.
    - Enter Email.
    - Agree to [Terms of Service](https://fontawesome.com/tos) and [Privacy Policy](https://fontawesome.com/privacy).
    - Click on **Send Kit Embed Code**.
    - Check your Email to **Finish Setting Up Your Account**.
    - Create a password .
    - Sign in.
    - Enter your first name, last name, select 2024, and click **All set. Let's Go!**.
- Select **all the Free Styles** and click **Next**.
- Select **Hosted by Us** and click **Next**.
- Customize Kit Icon, assign it a name, and click on **Make My Kit** in bottom right.
- Copy and Save your the HTML script tag for your Font Awesome Kit.

## 6. Editing your Personal Index HTML Page Head and Header.
- Open the VS Code terminal and enter the command `git checkout -b header_edits`.
- In the head section change the page title to `<FirstName> About Page`.
- Edit the script tag in the head element with your personal script tag from your Font Awesome Kit.
- Change the nav elements logo **I created this logo using PowerPoint and Gimp**.
- Edit the header-text div to fit you.
- Go to your style.css page and edit the background-images url in the #header section.
- In the terminal enter the following commands.
    - `git add .`.
    - `git commit -m "Edits made to index Header"`.
    - `git push --set-upstream origin header_edits`.
    - `git checkout main`.
    - `git merge header_edits`.
    - `git push origin main`.
- To delete the header_edits branch enter the command below:
    - `git push origin --delete header_edits`.
    - 

## 7. Editing your personal Index HTML About Section
- Open the VS Code terminal and enter the command `git checkout -b about_sec`.
- Edit the p tag on line 51.
- To modify your skills edit the div where the `id="skills"`.
- To modify your experiences edit the div where the `id="experience"`.
- To modify you education edit the dive where the `id="education"`.
- In the terminal enter the following commands.
    - `git add .`.
    - `git commit -m "Edits made to the about section"`.
    - `git push --set-upstream origin about_sec`.
    - `git checkout main`.
    - `git merge about_sec`.
    - `git push origin main`.
- To delete the about_sec branch enter the command below:
    - `git push origin --delete about_sec` **deletes branch from online repository**.
    - `git branch -d about_sec` **deletes branch from local repository**.


## 8. Editing your personal Index HTML Services Section
- Open the VS Code terminal and enter the command `git checkout -b services_sec`.
- to modify the first card in My Services edit lines 115-123.
- to modify the second card in My Services edit liens 124-132.
- To modify the third card in My Services edit lines 133-141.
- Once you are satisfied with your changes enter the following lines into your terminal.
    - `git add .`.
    - `git commit -m "Edits made to services section"`.
    - `git push --set-upstream origin services_sec`.
    - `git checkout main`.
    - `git merge services_sec`.
    - `git push origin main`.
- To delete the about_sec branch enter the command below:
    - `git push origin --delete services_sec` **deletes branch from online repository**.
    - `git branch -d services_sec` **deletes branch from local repository**.

## 9. Editing your personal Index HTML Portfolio Section
### NOTE: This is where your post your projects
- Open the VS Code terminal and enter the command `git checkout -b portfolio_sec`.
- This section currently has four cards but can be tailored to fit your need.
    - **NOTE**: if you decide to include more I would suggest modifying this sections CSS properties.
- to modify the first card in the portfolio edit the first div with where `class="work"`.
- to modify the second card in the portfolio edit the second div with where `class="work"`.
- to modify the third card in the portfolio edit the third div with where `class="work"`.
- to modify the fourth card in the portfolio edit the fourth div with where `class="work"`.
- Modify the href attribute for the See More button so that it directs to your github.
- Once you are satisfied with your changes enter the following lines into your terminal.
    - `git add .`.
    - `git commit -m "Edits made to portfolio section"`.
    - `git push --set-upstream origin portfolio_sec`.
    - `git checkout main`.
    - `git merge portfolio_sec`.
    - `git push origin main`.
- To delete the about_sec branch enter the command below:
    - `git push origin --delete portolfio_sec` **deletes branch from online repository**.
    - `git branch -d portfolio_sec` **deletes branch from local repository**.


## 10. Editing your personal Index HTML Contact Section
- Open the VS Code terminal and enter the command `git checkout -b contact_sec`.
- To change the email edit the first p tag in the div where `class="contact-left"`.
- To change the phone number edit the second p tag in the div where `class=contact-left"`.
- To change the social icons and there linds edit the div where `class="social-icons"`.
    - Tailor the social icons to reflect what you want to show/share.
        - For example if you want to get into web devlopment you may want to share your work on codepen.
- Replace the pdf resume in the resources folder with your own personal resume.
- Modify the href attribute for the `Download CV` button to link to your resume.
- Once you are satisfied with your changes enter the following lines into your terminal:
    - `git add .`.
    - `git commit -m "Edits made to contact section"`.
    - `git push --set-upstream origin contact_sec`.
    - `git checkout main`.
    - `git merge contact_sec`.
    - `git push origin main`.
- To delete the about_sec branch enter the command below:
    - `git push origin --delete contact_sec` **deletes branch from online repository**.
    - `git branch -d contact_sec` **deletes branch from local repository**.

## 11. Setting up your Google Sheet Script for Form
- Open the VS Code terminal and enter the command `git checkout -b form_submission`.
- Navigate to [Google Sheets](https://docs.google.com/spreadsheets)
    - Create a new blank sheet and rename it `Contact Form`
    - Set column headings as seen below:

|   |   A  |   B   |    C    |
|---|:----:|:-----:|:-------:|
| 1 | Name | Email | Message |

- Navigate to the [Form to Google Sheets Repository](https://github.com/jamiewilson/form-to-google-sheets).
- Copy the code from the repositories step two.
- Navigate back to your google sheet and cick the **Extensions -> Apps Script tab**.
- Dobule click the name `Untitled Project` and rename it to Contact Form.
- Delete the function and paste the code copiedfrom online [Google Sheet](https://github.com/jamiewilson/form-to-google-sheets) repository.
- Click on the save icon.
- Once it has saved click **run**.
    - Click on review permissions.
    - Confirm your account.
    - Click on **advanced -> Go to contact form (unsafe)**.
    - Click allow.
- CLick **deploy -> New deployment**   .
    - Click on the **settings icon -> Web App**.
    - Add description.
    - In the Who has Access box select `Anyone`.
    - Then click **deploy**.
    - Copy and save the Web app URL and click Done.
- Replace the value of scriptURL in your index html script, with the webApp URL you copied from Google Sheets.
- Once you are satisfied with your changes enter the following lines into your terminal:
    - `git add .`.
    - `git commit -m "Configured Google Sheet Contact Form Submission"`.
    - `git push --set-upstream origin form_submission`.
    - `git checkout main`.
    - `git merge form_submission`.
    - `git push origin main`.
- To delete the about_sec branch enter the command below:
    - `git push origin --delete form_submission` **deletes branch from online repository**.
    - `git branch -d form_submission` **deletes branch from local repository**.