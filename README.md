# Experiment: Source Code Management on GitHub

## Aim
Practice Source code management on GitHub. Experiment with the source code written in exercise 1.

## Description
To practice source code management on GitHub, follow these steps:

1. **Create a GitHub Account:** If you don't already have one, [create a GitHub account](https://github.com/).

2. **Create a New Repository on GitHub:** 
   - Log in to your GitHub account.
   - Click on the "+" sign at the top right and select "New repository."
   - Fill in the repository name, description, and other details as needed.
   - Choose your repository's visibility (public or private).
   - Optionally, select a license and add a README file.
   - Click "Create repository."

3. **Clone the Repository to Your Local Machine:** 
   - On your GitHub repository's main page, click the green "Code" button.
   - Copy the repository URL (usually in the form `https://github.com/your-username/repository-name.git`).
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to clone the repository.
   - Run the following command, replacing `<repository-url>` with the URL you copied:
     ```
     $ git clone <repository-url>
     ```

4. **Move to the Repository Directory:** 
   - Use the `cd` command to navigate to the newly created directory:
     ```
     $ cd <repository-name>
     ```

5. **Create a New File in the Repository and Add the Source Code Written in Exercise 1.**

6. **Stage the Changes:** 
   - Use the following command to stage the changes for commit:
     ```
     $ git add <file-name>
     ```

7. **Commit the Changes:** 
   - Commit the staged changes with a meaningful message:
     ```
     $ git commit -m "Added source code for a simple user registration form"
     ```

8. **Push the Changes to the Remote Repository:** 
   - Push your committed changes to GitHub:
     ```
     $ git push origin master
     ```

9. **Verify on GitHub:** 
   - Visit your GitHub repository in a web browser, and you should see the changes reflected there.

These steps demonstrate how to use GitHub for source code management. You can use the same steps to manage any source code projects on GitHub. Additionally, you can also explore GitHub features such as pull requests, code review, and branch management to enhance your source code management workflow.
