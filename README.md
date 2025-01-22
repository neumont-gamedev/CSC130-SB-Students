# Student Repository

Welcome to the student repository! Please follow the instructions below to add your name to the `students.txt` file. Be careful not to overwrite anyone else's submission.

---

## Instructions for Submitting Your Name

### Step 1: Clone the Repository
First, clone this repository to your local machine:
```bash
git clone https://github.com/neumont-gamedev/CSC130-SB-Students.git
cd CSC130-SB-Students
```

### Step 2: Open the `students.txt` File
Open the `students.txt` file in your preferred text editor. You’ll see something like this:
```plaintext
# Add your name below this line
# Do not edit or remove any other entries
```

### Step 3: Add Your Name
Add your name to the file on a new line below the placeholder. For example:
```plaintext
# Add your name below this line
# Do not edit or remove any other entries
John Doe
```

### Step 4: Save and Commit Your Change
After adding your name, save the file and commit your changes:
```bash
git add students.txt
git commit -m "Added my name to submissions.txt"
```

### Step 5: Push Your Changes
Push your changes back to the repository:
```bash
git push
```

### Step 6: Verify Your Submission
Go to the repository on GitHub and check the `students.txt` file to confirm that your name has been added correctly.

---

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
