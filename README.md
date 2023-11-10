# Assignment Week-3
---
## Create Basic Website with HTML and CSS

[Layout can click this link :] (https://seoul-3-example-week-3.netlify.app/)

---
# **Assignment Week-4**

---
Hi, I'm Usman Ali. I'm training to become a software engineer at Revou. I have now entered week 4 and created deploy and have assignment of creating deployment process, connecting to domain and DNS, and documenting deployment. The last, i had learned to create a clone website for Ace Hardware and now i will connect it to the domain and DNS.

[link website connecting to domain and DNS](https://almanit.site/) : https://almanit.site/

Here are the steps :
## **1. Dublicate file**
---
This guide will walk you through the steps to create new folder, copy files, add files, commit changes, push to GitHub using the terminal and git commands from Visual Studio Code.

Before you start, make sure you have the following prerequisites :
- Git
- Visual Studio Code

### **Step 1 : Create Folder and Dublicate Files**
1. Open Visual Studio Code and run terminal and following command to create folder :
    ```
    mkdir week-4 (in folder local repository module-2)
    ```
    ![create folder](/week-4/git_img/board1c.PNG)
2. Dublicate file ```assets, Index.html, script.js, style.css``` in folder week-3 transfer to folder week-4
    ![dublicate files](/week-4/git_img/board2.PNG)

### **Step 2 : Adding Files, Committing Changes, and Push on Github**
1. cek files status in terminal and run the following command :
    ```
    git status
    ```
2. Next, run the following command to add the file to the list of changes :
    ```
    git add .
    ```
3. Then, run the following command to commit the changes:
    ```
    git commit -m "Assignment week-4"
    ```
    ![git add](/week-4/git_img/board3.PNG)
4. After committing the changes, run the following to push the changes to the GitHub repository:
    ```
    git push origin main
    ```
    ![git push](/week-4/git_img/board4.PNG)

### **Step 3 : Deployment with Netlify, Custom Domain and Setting DNS**

This documentation will guide you through the process of registering with Netlify, connecting it to your GitHub repository, enabling automatic deployment, and changing the domain. Follow the steps below to complate to task.

#### **Registration on Netlify and Connectiong to GitHub for Deploy**
1. Open https://www.netlify.com/ in your browser.
2. Click the "Sign up" button to create a new account or "Login" if you already have the account. You can choose various options for creating a new account with email, gitlab or bitbucket account.
    ![register - login](/week-4/git_img/board18.PNG)
    ![dashboard](/week-4/git_img/board5.PNG)
3. Follow the provided registration steps.
4. After signing up, you will be directed to the Netlify dashboard.
5. In the Netlify dashboard, click the "Add new site" button.
    ![add new](/week-4/git_img/board6.PNG)
6. Select "Deploy with GitHub".
    ![deploy](/week-4/git_img/board7.PNG)
7. Grand the necessary permissions to access your repository.
8. Choose the repository you want to connect.
9. Configure the deployment settings according to your needs, such as the branch to deploy and the build command to execute.
10. Click the "Deploy site" button to initiate the initial deployment process.
11. Once your repository is connected, Netlify will automatically trigger deployments whenever changes occur in your GitHub repository.
12. You can changes name link after deployment setting according to your needs in site configuration.
    ![name](/week-4/git_img/board14.PNG)
    ![name](/week-4/git_img/board15.PNG)

#### **Buy Custom Domain**