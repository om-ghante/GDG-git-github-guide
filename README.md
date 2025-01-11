# Step-by-Step Guide to Git and GitHub

## **Step 1: Orientation**

## **Step 2: Introduction to the Event**

### Topics Covered:
1. **What is GitHub?**

2. **Importance of GitHub:**

3. **Uses of GitHub:**

4. **What is Git?**

## **Step 3: Account Creation**
Guide participants to create a GitHub account at [https://github.com](https://github.com).

## **Step 4: Git Installation and Personal Access Token Setup**
1. Install Git from [https://git-scm.com/](https://git-scm.com/).
2. [Installation for mac OS](https://www.youtube.com/watch?v=B4qsvQ5IqWk)
3. Configure Git with your information:
    ```bash
    git config --global user.name 'your-username'
    git config --global user.email 'your-email-used-during-account-creation'
    git config --global github.user 'your-username'
    git config --global github.token 'your-personal-access-token'
    ```

## **Step 5: Explanation of GitHub Dashboard**

## **Step 6: Repository Basics**
1. **What is a Repository (Repo)?**
   
2. **Creating Your First Repo:**

## **Step 7: What is a README.md File?**

## **Step 8: Frequently Used Commands**
1. **Initialize a Repository:**
    ```bash
    git init
    ```
2. **Clone a Repository:**
    ```bash
    git clone <repository-URL>
    ```
3. **Check File Status:**
    ```bash
    git status
    ```
4. **Commit Changes:**
    ```bash
    git commit -m "Your commit message"
    ```
5. **Branch Management:**
    ```bash
    git branch
    ```

## **Step 9: Push Files to a Repository**

```
git init
```     
```
git remote add origin https://github.com/username/repo_name.git 
```
```
git remote –v 
```
```
git remote set-url origin https://personal-access-token@github.com/usrname/repo_name 
```
```
git fetch origin  
```
```
git switch main 
```
```
git branch 
```
```
git pull origin 
```
```
git log 
```
```
git add . / git add specific_folder or specific_file  
```
```
git commit –m “your msg” 
```
```
git push origin main 
```
## **Step 10: Collaboration and Open Source**

## **Step 11: Forking a Repository**

## **Step 12: Pull Requests (PRs)**

```    
git init 
```
```
git clone https://github.com/username/repo_name 
```
```
cd folder_name 
```
```
git remote add origin https://github.com/username/repo_name.git 
```
```
git remote add upstream https://github.com/owners_usrname/repo_name.git 
```
```
git fetch upstream 
```
```
git branch > git branch branch_name > git switch branch branch_name / git checkout –b branch_name 
```
```
git add . / git add specific_folder or specific_file  
```
```
git commit –m “your msg” 
```
```
git push origin branch_name 
```

## **Step 13: Issues**

---

## **Bonus Tip: GitHub Profile README**
- Create a README file for your profile repository (e.g., `username/username`) to showcase your skills, achievements, and projects.

---

