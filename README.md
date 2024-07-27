# Developer Profiles

Welcome to the Developer Profiles project! This repository is intended to help you learn how to handle creating branches and pull requests (PRs) on GitHub. Follow the instructions below to create your profile and contribute to the project.

## Instructions for Submission

1. **Clone the Repository:** Clone the repository to your local machine.

   ```
   git clone https://github.com/Isaac-Zimba-J/ProjectTrial.git
   ```

2. **Create a New Branch:** Create a new branch with your name.
   ```
   git checkout -b [your-name-branch]
   ```
3. **Create Your Profile:** In the developers folder, create a new file named `[your-github-username].md` and fill it with the Profile `template profile.md` provided.

4. **Commit Your Changes:** Commit your changes with a meaningful commit

   ```
   git add developers/[your-github-username].md
   git commit -m "Add profile for [Your Full Name]"
   ```

   Alternatively you can do this in vscode if you downloaded the extensions.

5. **Push Your Branch:** Push your branch to the remote repository.
   ```
   git push origin [your-name-branch]
   ```
6. **Create a Pull Request:** Open a pull request from your branch to the main branch on GitHub.

   Go to the repository on GitHub.
   Click on the "Pull Requests" tab.
   Click on the "New Pull Request" button.
   Select your branch from the "compare:" dropdown.
   Click on the "Create Pull Request" button.

7. **Add Reviewers:** Add your team members as reviewers to your pull request.

   In the "Reviewers" section on the right side of the pull request page, select your team members from the list.

8. **Request Reviews:** Ask your team members to review your pull request and provide feedback.

9. **Merge Your Pull Request:** Once your pull request has been reviewed and approved by your team members, you can merge it into the main branch.

   Click on the "Merge pull request" button.
   Confirm the merge by clicking on the "Confirm merge" button.

# IMPORTANT NOTE

## Pull Request Template

To ensure that all pull requests are consistent and provide the necessary information, we use a pull request template. When you create a new pull request, the template will automatically populate the description field with the following information:

1. **Description** - A summary of the changes and the related issue.
2. **What does this PR do?** - A brief description of the changes made.
3. **What issue does this PR address?** - Link to the issue this PR resolves, if applicable.
4. **Testing Instructions** - How to test the changes, including any relevant steps or commands.
5. **Screenshots** - Optional section for screenshots of the changes.
6. **Additional Notes** - Any extra context or notes about the PR.

Please make sure to fill out all sections of the template when creating a pull request. This helps maintain clarity and consistency in the contributions to the repository.

## Instructions for Reviewing Pull Requests

As a reviewer, your role is to ensure that pull requests meet the quality standards of the repository. Follow these steps to review pull requests effectively:

1. **Navigate to the Pull Request:**

   - Go to the repository on GitHub.
   - Click on the "Pull Requests" tab.
   - Select the pull request you want to review from the list.

2. **Review the Pull Request Description:**

   - Read the pull request description to understand the changes being proposed.
   - Ensure that the description is complete and follows the provided pull request template. It should include a summary of changes, the issue it addresses, testing instructions, and any additional notes.

3. **Examine the Changes:**

   - Click on the "Files changed" tab to review the code changes.
   - Carefully inspect the modifications, additions, and deletions. Check for correctness, adherence to coding standards, and potential bugs.
   - Verify that the code follows best practices and aligns with the project’s style guide.

4. **Test the Changes:**

   - If possible, pull the changes to your local environment and run any tests to ensure that the code works as intended.
   - Validate that the changes do not introduce any new issues or regressions.

5. **Leave Comments:**

   - If you identify any issues or have suggestions for improvement, leave comments directly on the lines of code or in the "Conversation" tab.
   - Be specific and constructive with your feedback. Explain why changes are needed and provide suggestions for improvement.

6. **Approve or Request Changes:**

   - If the pull request is satisfactory and meets the repository’s standards, click the "Review changes" button and select "Approve."
   - If you believe changes are necessary, select "Request changes" and provide detailed feedback on what needs to be adjusted.

7. **Review Other Comments:**

   - Check any comments left by other reviewers and ensure that they have been addressed.
   - If additional changes are requested, review the updates and ensure that they resolve the feedback provided.

8. **Merge the Pull Request:**

   - Once the pull request has been approved and all feedback has been addressed, you or the pull request creator can merge it into the `main` branch.
   - Click on the "Merge pull request" button and confirm the merge by clicking "Confirm merge."

9. **Verify Post-Merge:**
   - After merging, verify that the repository remains stable and that the changes have been correctly integrated into the `main` branch.
   - Check that all automated tests (if any) pass and that the repository is functioning as expected.

By following these instructions, you ensure that contributions are thoroughly reviewed and meet the quality standards of the project. Thank you for your diligence and attention to detail in maintaining the repository’s integrity.
