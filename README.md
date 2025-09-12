### **IXI Lab GitHub Onboarding: Your First Contribution**

**Objective:** This is a hands-on tutorial to guide you through the entire process of making a contribution to a project. By the end, you will have practiced every core skill you need for your daily work.

-----

### **Part 1: Preparation (The One-Time Setup)**

If you haven't already, ensure you have completed the following:

  * **VS Code Installed:** The official editor for our lab. [Download here](https://code.visualstudio.com/).
  * **Git Installed:** The core version control software. [Download here](https://git-scm.com/downloads).
  * **Git Configured:** You have run the following commands in your terminal with your information:
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@github.com"
    ```
  * **Logged into GitHub in VS Code:** You have signed in via the "Accounts" icon in the bottom-left corner.

-----

### **Part 2: Getting the Project & Making Your First Edit**

**Step 1: Clone the Demo Repository**
First, get a local copy of the workshop's demo project.

1.  Navigate to the demo repository on GitHub.
2.  Click the green **"\<\> Code"** button and copy the HTTPS URL.
3.  In VS Code, open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`) and run **`Git: Clone`**.
4.  Paste the URL and choose a location on your computer to save the project.
5.  When prompted, click **"Open"** to open the new project.

**Step 2: Switch to the `develop` Branch**
Our work always happens on the `develop` branch. Let's switch to it now.

  * In the bottom-left corner of VS Code, click on the branch name (it should say `main`).
  * From the menu that appears at the top, select **`origin/develop`**. Your status bar will now show `develop`.


-----

### **Part 3: Your First Feature Branch**

Now you will practice the full, correct workflow on your own personal branch.

**Step 5: Create Your Personal Branch**
Create a new branch from `develop`. This will be your safe workspace.

1.  Make sure you are still on the `develop` branch.
2.  Click the branch name (`develop`) in the bottom-left corner.
3.  Select **`+ Create new branch...`**.
4.  Name the branch with your first name (e.g., `bryant`). Press Enter.

**Step 6: Create and Edit a New File**
In your new branch, create a personal file.

1.  In the VS Code file explorer, click the "New File" icon.
2.  Name the file after yourself (e.g., `bryant.md`).
3.  Inside the file, write a sentence or two. For example: "This is my first file on my personal branch."
4.  **Save the file.**

**Step 7: Save and Share Your Work (Add, Commit, Push)**
Now, save this new file and upload it to GitHub.

1.  Go to the **Source Control** panel.
2.  **Stage** your new file by clicking the **`+` icon**.
3.  **Commit** your change with a clear message, like `feat: Create Bryant's personal file`.
4.  **Push** your new branch to GitHub by clicking the **"Publish Branch"** button in the status bar.

-----

### **Part 4: The Review Process**

**Step 8: Open a Pull Request**
Your code is on GitHub, and now you need to ask for it to be reviewed and merged.

1.  Go to the demo repository page on GitHub in your web browser.
2.  You will see a yellow banner with your branch name. Click the green **"Compare & pull request"** button.
3.  On the next page, ensure the settings are correct:
      * **Base repository:** The main demo repo.
      * **Base branch:** `develop`  \<-- **CRITICAL**
      * **Head branch:** `<your-name>` (e.g., `bryant`)
4.  Fill out the Pull Request template in the description box.
5.  On the right side, assign your Team Leader or the workshop instructor as a **Reviewer**.
6.  Click **"Create pull request"**.

**Congratulations\!** You have now completed the entire development cycle, from setting up your computer to submitting your work for review. Your Team Leader will now take over to review your PR.