# Strong-Password-Generator

_Note: This project has a MIT License so feel free to clone it and use it as you wish to._

**If you find any bugs in the code or wish to add improvments to this project, please clone a fork and a create pull request. The stpes for the same are outlined below.**

## Submitting Pull Requests to Improve 
_Note: You need a GitHub account to submit a pull request._

### 1. Fork the Repository
- Navitage to the GitHub repositiriy you wish to contribute to.
- Click on the "Fork" button that is located at the top right corner of the page. This creates a copy of the repository in your GitHub account

### 2. Clone the Repository
- After you have forked the repository, go to your profile and open the forked repository.
- Click on the green "Code" button and copy the URL provided.
- Open your preferred Git command-line tool or Git GUI.
- Use the `git clone` command followed by the copied URL to clone your forked repository to your local machine:
    ```bash
    git clone <link_to_the_repository>
    ```

### 3. Create a New Branch
- Change your repository directory on your local machine using the `cd` command on your terminal:
    ```bash
    cd <repository_name>
    ```
- Create a new branch for your proposed new feature or bug fix. Use a descriptive branch name:
    ```bash
    git checkout -b feature/proposed_feature_name
    ```

### 4. Make and Commit Your Proposed Changes
- Make the necessary code changes on your local branch.
- Use the `git add` command to add the changes to the branch: 
    ```bash
    git add .
    ```
- Commit your code changes with a descriptive commit message:
    ```bash
    git commit -m "Descriptive commit message of the changes proposed"
    ```

### 5. Push Changes to Your Fork
- Push your committed chanes to your forked repository on GitHub:
    ```bash
    git push origin feature/proposed_feature_name
    ```

### 6. Create a Pull Request 
- Once you have sucessfully pushed your proposed code changes, navigate to your forked repository on GitHub.
- You should then be able to see a banner at the top indicating that you have recently pushed a new branch. Click on the "Comapre & pull request" button that is next to it.

### 7. Open a Pull Request
- On the Pull Request page:
    - Select the base repository and the base branch (base repository is the respository you originally forked from and the main branch).
    - Select your forked repository and the branch you created (this is the repository of your proposed code changes).
- Fill in the title and description for your pull request. Be sure to provide context and adequate information about the changes you have proposed.

### 8. Review and Submit Your Improvements
- Provide tests and documentation for the changes and add labels to categorie your pull request.
- Once done, click on the "Create pull request" button.

### 9. Merging the Pull Request
- If the maintainers of the original repository need more information or clarification, they may comment on your pull request. You should make necessary changes based on the comments. 
- Once approved, your pull request will be merged into the main branch of the original repository.
- If your changes are merged, you will officialy become a contributor to the original repository. 


**You can read more about contributing to projetcs, forking and submitting a pull request in the GitHub documentation: https://docs.github.com/en/get-started/quickstart/contributing-to-projects** 
