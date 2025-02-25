# Contribution Guideline

<br>

## How do I make a contribution in this SSG project?

<br>

Never made an open source contribution before? Wondering how contributions work in the in our project?
Here's a quick rundown!

<br>

## **Here's a quick rundown on how to make a contribution to my project:**

---

<br>

1. Find an issue that you are interested in addressing or a feature that you would like to add.

   <br>

2. Fork the repository associated with the issue to your local GitHub organization. This means that you will have a copy of the repository `underyour-GitHub-username/repository-name.`

   <br>

3. Clone the repository to your local machine using:

   ```
   git clone https://github.com/github-username/simple-ssg1.git.
   ```

4. Add the upstream remote:

   ```
    git remote add upstream https://github.com/mnosov622/todo-list.git
   ```

5. Pull the latest changes from the main repository if you think your fork is behind:

   ```
   git pull upstream main
   ```

6. Create a new branch and switch to it for your issue fix or feature using:

   ```
   git switch -c branch-name-here
   ```

7. Make the appropriate changes for the issue you are trying to address or the feature that you want to add

   <br>

8. Add the changes to the staging are and commit them to the branch you are working on

   <br>

9. Push the changes to the remote repository using:

   ```
   git push origin branch-name-here
   ```

10. Submit a **pull request** to the upstream repository

   <br>

11. Title the **pull request** with a short description of the changes made

   <br>

12. Wait for the pull request to be reviewed by a maintainer

   <br>

13. Make changes to the pull request if the reviewing maintainer recommends them

   <br>

14. Celebrate your success after your pull request is merged!

## <br>

# Prettier

To run the prettier and make your code look better, run the following command:

```
npm run prettier
```

To check if all files are formatted, run:

```
npm run prettier-check
```

# eslint

To run eslint on all files, run :

```
npm run eslint
```

---

# Testing

To test the tool run

```
npm run test
```

To run single test:

replace `test` command with `test.only`

To test single file, run :

```
npm test <name of the file>
```

To run watch mode:

```
npm test --watchAll
```

### WE APPRECIATE YOUR CONTRIBUTION! ❤️
