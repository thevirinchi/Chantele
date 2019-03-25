# Chantele
An android app to identify songs using string-matching.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
1. Android Studio :laughing:
2. Android Phone
   Enable `USB Debugging`:
   1. Goto **Settings** -> **About Phone**
   2. Tap on **Build Number**, *7 times*.
   3. Now open **Developer Options**.
   4. Under **Debugging**, enable **USB debugging**.
3. Android SDK
   Opening `SDK Manager`
   1. Close any open project.
   2. Click on **Configure** -> **SDK Manager**
   3. Download **_all_** the SDK Platforms from **API lvl 23** till **API lvl 28** (**_inclusive_**)
   4. Head over to **SDK Tools** now. which is the *second tab* in the Android SDK tab.
   5. Download the following:
   ```
      Android SDK Build-Tools 29-rc1
      Android SDK Platform-Tools
      Android SDK Tools
      Google Play Instant Development SDK (Optional)
      Google USB Driver
      Google Web Driver
      Support Repository (all)
   ```

### Cloning Project
Close any project if open.
If you have `Chantele` listed in the Left Pane, then open the project.
Else click on `Check out project from Version Control` (GitHub is a version control system)
  1. *Select* **Git** from the drop down.
  2. Now *copy* the URL of this repo in the **URL** field.\
    ```
      https://github.com/z3t4z00k/Chantele.git
    ```
  3. Now **Test** the URL and if it prompts to login, then enter your **GitHub's username and password**.
  4. Then click on **Clone**.
  5. The project will be cloned from the GitHub repo's Master branch in your local machine.
  6. Open the project as you would.

### Working on project
#### - To contribute to the project:
  1. Clone/Update the project from GitHub
  2. *Create* a **New Branch** in your Android Studio:
     1. *Open* **VCS** menu
     2. *Goto* **Git** -> **Branches**
     3. *Create* a **New Branch** and then *enter* the **name of the activity** you will be working on.
     4. Note: Leave the **Checkout Branch** *checked*. Click **OK**.
  3. Work in this branch till it's complete and focus only on that one task.
#### - Point to keep in mind:
   - Create **_different branches for different tasks_**.
   - *Commit* and *Push* your branch regularly. ( *Work. Commit. Push. Repeat.* )
   - To make working with Git easy, download **GitHub Desktop** from [here](https://desktop.github.com/).
#### - Using GitHub for desktop
  1. Login using your GitHub credentials.
  2. Press *Cntl + O* and then navigate to the path of your copy of the project which should be something like\
    ```
    C:\Users\[username]\StudioProjects\[project name]
    ```
  3. Click on **Add Repository**.
  4. Then under **Current branch**, select the branch corresponding to your task.
  5. Now all the changes you do in the project under your working branch, will be reflected in the GitHub for Desktop.
  6. To push all the changes to the GitHub repo,
     1. Enter the summary of the work done till now, with a brief description. Commit.
     2. Then press *Cntl + P* to push all the changes to GitHub repo. And Done!

##  Work Divide
  1. Basic Structure
     - [x] On-Boarding Activity -- [@z3t4z00k](https://github.com/z3t4z00k)
     - [ ] Login/Signup Activity - (TBD)
     - [ ] Main Activity --------- [@z3t4z00k](https://github.com/z3t4z00k)
     - [ ] Search Activity ------- [@z3t4z00k](https://github.com/z3t4z00k)
     - [ ] Settings Activity ----- [@dirag](https://github.com/dirag)
     - [ ] FAQ Activity ---------- [@sanjana2070](https://github.com/sanjana2070)
     - [ ] Song Details Activity - (TBD)
     - [ ] User Profile Activity - [@jainritika1203](https://github.com/jainritika1203)
  2. Back-End
     - [ ] User Profile Data Storage
     - [ ] User Profile Data Fetch
     - [ ] Delete User Data
     - [ ] Manage Songs Database
     - [ ] Searching songs
  3. Finishing touches
     - [ ] Check Workflow
     - [ ] Animations
     - [ ] UI
