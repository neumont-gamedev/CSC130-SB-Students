# Student Repository

# Fork and Submit Your Name to the Student Repository  

Welcome to the student repository! Please follow these instructions to add your name to the `students.txt` file. You will first **fork the repository**, work on your forked copy, and then create a pull request to submit your changes. This approach ensures smooth collaboration and keeps the repository organized.

---

## **Instructions for Submitting Your Name**

### **Step 1: Fork the Repository**
1. Go to the original repository on GitHub:  
   [CSC130-SB-Students Repository](https://github.com/neumont-gamedev/CSC130-SB-Students).  
2. Click the **Fork** button in the top-right corner of the page to create your own copy of the repository.

---

### **Step 2: Clone Your Forked Repository**
1. Navigate to your forked version of the repository on GitHub.
2. Copy the repository’s URL (via the green "Code" button).  
3. Clone your forked repository to your local machine using the following command:  
   ```bash
   git clone <your-forked-repo-url>
   cd CSC130-SB-Students
   ```

### **Step 3: Open the students.txt File**

Open the students.txt file in your preferred text editor. You’ll see something like this:
```
# Add your name below this line
# Do not edit or remove any other entries
```
### Step 4: **Add Your Name**

Add your name to the file on a new line below the placeholder. For example:
```
# Add your name below this line
# Do not edit or remove any other entries
John Doe
```

### Step 5: Save and Commit Your Change
After adding your name, save the file and commit your changes:
```bash
git add students.txt
git commit -m "Added my name to submissions.txt"
```

### Step 6: Push Changes to Your Fork
Push your committed changes to the main branch of your forked repository:
```bash
git push
```

### Step 7: Create a Pull Request
Go to your forked repository on GitHub.
+ Click the Pull Request button to create a new pull request.
+ Make sure to compare your forked repository's main branch with the original repository’s main branch.
+ Add a descriptive title (e.g., "Added John Doe to students.txt") and click Create Pull Request.

## Important Notes
- **Do not edit or remove other students' entries.** Only add your name below the placeholder.
- **Pull the latest changes before adding your name** to avoid conflicts:
  ```bash
  git pull origin main
  ```
- If you encounter a merge conflict, carefully resolve it, ensuring all names are preserved, and then commit the resolution:
  ```bash
  git add students.txt
  git commit -m "Resolved merge conflict in students.txt"
  git push
  ```
---
