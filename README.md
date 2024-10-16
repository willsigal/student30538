# PPHA 30538: Data and Programming in Python
## Fall 2024
## University of Chicago Harris School of Public Policy
## Peter Ganong and Maggie Shi

Welcome to the **new** student repository for PPHA 30538: Data and Programming in Python. 

## Repository Structure

Lectures are in both the `before_lecture` and `after_lecture` folders. `before_lecture` does not contain answers to in-class exercises, while `after_lecture` does. Within each folder ,each lecture will have its own folder with the following materials:
- **Quarto code**: `.qmd` files that are the source of the lecture slides.
- **Supporting materials**: Any images, data files, or external resources referenced in the slides.
- **Slides**: knitted PDF or HTML files that contain the slides used during the lecture.

Each problem set and mini-lesson will have their own folders within their respective folders. Kickoff slides (slides discussed before lecture starts) are all contained in `kickoff`.


## Getting Started

### GitHub Desktop

1. **Ensure you are logged in to GitHub**:
   - Open GitHub Desktop.
   - Navigate to `File > Options` (on Windows) or `GitHub Desktop > Preferences` (on Mac).
   - Check the `Accounts` tab to make sure you're logged into your GitHub account.

2. **Clone the repository**:
   - Open GitHub Desktop.
   - Click on `File > Clone Repository`.
   - Enter the repository URL: https://github.com/uchicago-harris-dap/student30538_new.
   - Choose the location on your computer to save the repository and click `Clone`.
   

### Git Command Line

1. **Ensure you are logged in to GitHub**:
   - In your browser, navigate to [GitHub](https://github.com) and log in to your account.

2. **Clone the repository**:
   - Open your terminal.
   - Run the following command to clone the repository:
     ```bash
     git clone https://github.com/uchicago-harris-dap/student30538_new
     ```
   - Navigate into the cloned repository folder:
     ```bash
     cd student30538_new
     ```

## Updating the Repository
### GitHub Desktop
1. **Commit Changes**  
   - In the **"Changes"** tab, select files to commit by checking their boxes.  
   - Add a **Summary** message and click **"Commit to [branch-name]"**.  

2. **Pull Latest Changes**  
   - Click **"Fetch origin"** to check for updates.  
   - If updates are available, click **"Pull origin"**.  

3. **Resolve Merge Conflicts (If Needed)**  
   - Conflicting files appear with a red exclamation mark in **"Changes"**.  
   - Click the file to review both **"Current"** (yours) and **"Incoming"** (theirs) changes.  
   - Keep or edit changes, then click **"Mark as Resolved"**.  
   - Click **"Commit Merge"** to finalize.  

 
### Git Command Line
1. **Commit any changes**
    - Check what changes you made since the last pull to show `name-of-file-you-changed`
     ```bash
     git status
     ```
    - Add any changes you made you want to keep 
     ```bash
     git add name-of-file-you-changed
     ```
     - Commit those changes with a message
     ```bash
     git commit -m "this commit message explains more about what changes I'm committing"
     ```
 2. **Pull Latest Changes**  
   - Pull the latest changes from the remote branch:  
     ```bash
     git pull
     ```
     
 3. **Resolve Merge Conflicts (If Needed)**  
   - If there are conflicts, Git will list the conflicting files after the pull.  
     ```bash
     git status
     ```
   - Open the conflicting files in a text editor to resolve conflicts:  
     - Look for markers like `<<<<<<<`, `=======`, and `>>>>>>>` to review **your changes** (current) and **their changes** (incoming).  
     - Edit the file to keep or merge changes as needed.

   - Once resolved, add the modified file:  
     ```bash
     git add <file-name>
     ```

   - Commit the merge:  
     ```bash
     git commit -m "Resolved merge conflict in <file-name>"
     ```
    


Feel free to reach out via EdDiscussion if you have any questions or run into any issues. Happy coding!
