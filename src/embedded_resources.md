# Embedded Resources
## General Embedded Info
- At the end of each quarter, we’re all required to update our embedded documentation for whatever we worked on in [this repo](https://github.com/Anteater-Electric-Racing/aer-documentation)

    - Great way to get in-depth knowledge of everything embedded (though it can be dense at times)

    - We use Markdown to write this, and you can run it locally on your laptop to see the rendered changes
    - To run the local rendered markdown page and develop first enter: <br>
    ```curl https://sh.rustup.rs -sSf | sh in your terminal```
    - Install mdbook:
    ```cargo install mdbook mdbook-mermaid```
    - Clone the aer-documentation repo (or whichever one we’re using at the time) and then run: <br>
    ```git clone https://github.com/Anteater-Electric-Racing/aer-documentation``` <br>
    ```cd aer-documentation``` <br>
    ```mdbook serve```
        - **git clone** → clones repo in git
        - **cd** → means “change directory” to aer-documentation (or whatever the name of the repo is)
    - Go to [http://localhost:3000/](http://localhost:3000/) to see the rendered changes
## Git Basics:
- [MZ repository](https://github.com/Anteater-Electric-Racing/embedded-mz)

- **Git**: a version control design system that lets us collaborate on code
- We mainly use GitHub (which uses Git) to store all of our files
    - Allows us to see past changes, updated changes, and it’s easy to keep track of who changed what
- **Repository (repo)**: think of it like a container to store all of our car related files
- **Branches**: each repository has branches, and they allow you to make changes to code without changing the main source code
    - Each repo (by default) has a main branch, where the main source code is
    - Every time you make a branch, the main source code is copied
    - You can make edits on the new branch and it won’t affect the code in the main branch, until you “merge” into main
    - Importance of branches: lets you change code without directly affecting the main code base, and is more easily undoable 
- **Pulling changes**: allows you to “pull” changes from the repository and see the updates on your device
- **Pushing changes/committing changes**: means “pushing” your code to a branch, and your changes will show up in that branch with an optional commit message that you enter
- **Pull requests (PR)**: a form you fill out with a quick description of your changes in the code
    - Once approved, your code will be merged to main
    - Reviewers can post comments on the pull request to request changes/fixes to your code
- **General tips**:
    - Create a new branch with the naming format: FirstinitialLastinitial/task (if multiple names, hyphenate the initials)
        - Ex: ag-dt/speaker
        - Make sure to make changes only on that branch, then create a pull request (PR) once you believe your changes are ready to be merged to main
    - Add Anoop as a reviewer and assign yourself + your partner on the PR/task
    - Make sure to fill out the PR according to the PR template (and include any photos/testing that you did for the task)



