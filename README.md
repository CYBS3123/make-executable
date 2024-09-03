
# In-Class Assignment: Execute a Shell Script

## Objective

Your task is to clone a repository that contains a shell script (`script.sh`). This script does not have execute permission when you first download it. Your job is to:

1. Clone the repository.
2. Change the script's permissions to make it executable.
3. Run the script.
4. The script will create a file named `script-ran.txt` or another indicator file that confirms the script has been executed.
5. Stage, commit, and push the changes to your GitHub repository.
6. A GitHub Actions workflow will check if you successfully changed the permissions and executed the script.

## Steps to Complete the Assignment

### 1. Clone the Repository

Open your terminal and clone the repository using:

\```bash
git clone <repository_url>
\```

Replace `<repository_url>` with the actual URL of the repository provided in class.

### 2. Change the Script's Permissions

Navigate to the cloned repository's directory:

\```bash
cd <repository_name>
\```

Use the `chmod` command to make the script executable:

\```bash
chmod +x script.sh
\```

### 3. Run the Script

Execute the script:

\```bash
./script.sh
\```

The script will create a file named `script-ran.txt` or another indicator file that confirms the script has been executed.

### 4. Stage, Commit, and Push Your Changes

Stage all the changes:

\```bash
git add .
\```

Commit the changes with a meaningful message:

\```bash
git commit -m "Executed script.sh and added the output file"
\```

Push your changes to GitHub:

\```bash
git push origin main
\```

---

By following these steps, you will successfully complete the assignment, and the GitHub Actions workflow will verify that you have properly executed the script and committed the changes.
