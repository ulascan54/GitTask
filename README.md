# Git and GitHub Task

Welcome to the Git and GitHub Workshop Task!. **To receive certified**, you need to complete the following task. This task will help you understand the basics of Git and GitHub, which are essential tools for software development.

---

## Task Description

Here’s the guide with the task explanations included:

1. **Fork the Repository:** Start by forking the repository.

2. **Clone the Repository:** Clone the repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/repositoryname.git
   cd repositoryname
   ```

3. **Create a New Branch:** Create a new branch with a name that includes your name and surname (e.g., `firstname-lastname`).

   ```bash
   git branch firstname-lastname
   git checkout firstname-lastname
   ```

   OR

   ```bash
   git checkout -b firstname-lastname
   ```

4. **Create a Blank File:** Create a blank text file with the name as your school ID number (e.g., `20210702XXX.txt`) in your branch.

   ```bash
   touch 20210702XXX.txt
   ```

5. **Commit and Push the Branch:** Commit the new file and push your branch to the repository on GitHub.

   ```bash
   git add 20210702XXX.txt
   git commit -m "Add blank file with school ID number"
   git push origin firstname-lastname
   ```

6. **Edit the File:** Open the file you just created and add your name and surname to it. Save the changes. For example, add:

   ```
   John Doe
   ```

7. **Commit and Push:** Commit the changes you made to the file and push them to your branch.

   ```bash
   git add 20210702XXX.txt
   git commit -m "Add name and surname to file"
   git push origin firstname-lastname
   ```

8. **Create a Pull Request:** Finally, create a Pull Request (PR) to merge your changes into the `submission` branch. We'll review your PR.

Go to your repository on GitHub, switch to the `firstname-lastname` branch, and click “Pull Request” to merge into the `submission` branch.

## Tips

- Keep your commit messages clear and concise.

Good luck, and happy coding!

---

#### Created by:

- [@Ulaş Can Demirbağ](https://github.com/ulascan54)
- [@Akif](https://github.com/AkifSahn)
- [@CanCodes](https://github.com/CanCodes)
