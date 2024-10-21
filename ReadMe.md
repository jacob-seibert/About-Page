# This Repository will allow you to practice using Git before touching the real project
**NOTE:** It can also serve as the bases for a web portfolio for each of you.

## 1. Create a Github Account
- Create an account on [Github](https://github.com/)
- Enter your email address and click `Sign up for Github`
- Click `Continue`
- Create a password and click `Continue`
- Create a username and click `Continue`
- Click `Continue`
- Verify your account by solving the puzzle.
- Go to your Email to and copy past launch code to Github
- **CONGRATS YOU CREATED A GITHUB ACCOUNT**

## 2. Install Git 
- Navigate to [GIT](https://git-scm.com/downloads) and download the installer for your OS
- Go to your downloads folder and launch the installer
- Click `Next`
- Click `Next`
- Select **Use Visual Studio Code as Git's default editor** and click `Next`
- Select **Override the default branch name for new repositories** and **set to main** then click `Next`
- Select **Git from command line and also from 3rd-party software** then click `Next`
- Select **Use bundled OpenSSH** then click `Next`
- Select **Use the OpenSSL library** then click `Next`
- Select **Checkout Windows-style, commit Unix-style line endings** then click `Next`
- Select **Use MinTTY (the default terminal of MSYS2)** then click `Next`
- Select **Fast-forward or merge** then click `Next`
- Select **Git Credential Manager** then click `Next`
- Select **Enable file system Caching** then click `Next`
- Select `Next`
- Select `Install`

## 3. Setting up Git Environment
- Launch VS Code application
- Navigate the tool bar and Select **View -> Terminal**
- Click the downward arrow in the top right corner of the terminal window and select **Git Bash**
- In the terminal enter `git config --global user.email "<email>"` then hit **Enter**
- In the terminal enter `git config --gobal user.name "<username>"` then hit **Enter**

## 4. Creating Your Own Repository for Your Portfolio
- Navigate to [GitHub](https://github.com/) and sign in.
- Click on your icon in the top right corner and select `Your repositories`
- Click the green `New` button
- Create your Repository name, description if desired, and click `Create Repository`
- Copy and save the URL in the Quick Setup section **NOTE: This is your Repositories URL. We will use it in a later step.**
- Create an empty folder named portfolio
- Copy and past both the index.html  and style.css files as well as the images folder to your empty portfolio folder
- Open your portfolio folder in VS Code **File -> Open Folder -> Selecte the file -> Click Select Folder**
- Click `Yes, I trust the authors`
- Open the Terminal **View -> Terminal**
- In the terminal enter `git init` then hit **Enter**
- In the terminal enter `git commit -m "first commit"` then hit **Enter**
- In the terminal enter `git branch -M main` then hit **Enter**
- In the terminal enter `git remote add origin <Ropsitory URL>` then hit **Enter**
- In the terminal enter `git push -u origin main`


## 5. Create a free account on [Font Awesome](https://fontawesome.com/)
- Click on **Start for Free** to make a free account
    - Enter Email
    - Agree to [Terms of Service](https://fontawesome.com/tos) and [Privacy Policy](https://fontawesome.com/privacy)
    - Click on **Send Kit Embed Code**
    - Check your Email to **Finish Setting Up Your Account**
    - Create a password 
    - Sign in
    - Enter your first name, last name, select 2024, and click **All set. Let's Go!**
- Select **all the Free Styles** and click **Next**
- Select **Hosted by Us** and click **Next**
- Customize Kit Icon, assign it a name, and click on **Make My Kit** in bottom right
- Copy and Save your the HTML script tag for your Font Awesome Kit

## 6. Editing your Personal Index HTML Page Head and Header
- Open the VS Code terminal and enter the command `git checkout -b header_edits`
- In the head section change the page title to `<FirstName> About Page`
- Edit the script tag in the head element with your personal script tag from your Font Awesome Kit
- Change the nav elements logo **I created this logo using PowerPoint and Gimp**
- Edit the header-text div to fit you
- Go to your style.css page and edit the background-images url in the #header section
- In the terminal enter the following commands.
    - `git add .`
    -`git commit -m "Edits made to index Header"`
    -`git push --set-upstream origin header_edits`
    -`git checkout main`
    -`git merge header_edits`
    -`git push origin main`
- To delete the header_edits branch enter the command below:
    - `git push origin --delete header_edits`

## 7. Editing your personal Index HTML About Section

## 8. Editing your personal Index HTML Services Section

## 9. Editing your personal Index HTML Portfolio Section

## 10. Editing your personal Index HTML Contact Section

## 11. Setting up your Google Sheet Script for Form
- Navigate to [Google Sheets](https://docs.google.com/spreadsheets)
    - Create a new blank sheet and rename it `Contact Form`
    - Set column headings as seen below:

|   |   A  |   B   |    C    |
|---|:----:|:-----:|:-------:|
| 1 | Name | Email | Message |

- Navigate to the [Form to Google Sheets Repository](https://github.com/jamiewilson/form-to-google-sheets)
- Copy the code from the repositories step two
- Navigate back to your google sheet and cick the **Extensions -> Apps Script tab**
- Delete the function and paste the code from online repository
