# Homework: GitHub Collaboration & Pull Requests

## Objective
Learn to use the **Pull Request (PR)** workflow to add new content, receive peer feedback, and resolve suggestions before merging code into a main project.

---

## Part 1: Setup & Feature Branching
For this assignment, we are ignoring your previous work. You will create a brand-new file on a separate branch.

1.  **Switch to Main:** Ensure you are on your main branch:
    `git checkout main`
2.  **Create a New Branch:** Create a branch specifically for this task:
    `git checkout -b add-resource-list`
3.  **Create a New File:** Create a file named `resources.md`.
4.  **Add Content:** In `resources.md`, create a list of 3–5 helpful websites, tools, or books related to this course. Each item must have:
    * A heading (using `#` or `##`)
    * A 1-sentence description
    * A clickable Markdown link
5.  **Push:** Stage, commit, and push your branch to GitHub:
    ```bash
    git add resources.md
    git commit -m "Add initial resource list"
    git push origin add-resource-list
    ```

---

## Part 2: Open a Pull Request (PR)
1.  Navigate to your repository on GitHub.com.
2.  Click the **Compare & pull request** button.
3.  **Reviewers:** On the right sidebar, click the gear icon next to "Reviewers" and select your assigned partner.
4.  Click **Create pull request**.

---

## Part 3: The Peer Review Cycle
*Now, go to your partner's repository to review their work.*

1.  Navigate to their **Pull Requests** tab and open their active PR.
2.  Click the **Files changed** tab.
3.  **Leave Comments:** Hover over a line of their code and click the **plus (+)** icon to leave a comment. You must leave at least two:
    * **Formatting Suggestion:** (e.g., "You should use a bulleted list here for better readability.")
    * **Content Question:** (e.g., "Why do you prefer this tool over others?")
4.  **Submit Review:** Click the green **Finish your review** button at the top right. Select **Request changes** and click Submit.

---

## Part 4: Resolving Feedback & Merging
*Return to your own repository to address the feedback you received.*

1.  **Respond:** In the **Conversation** tab of your PR, reply to your partner’s comments.
2.  **Fix:** Make the requested changes in your local file on your computer.
3.  **Update:** Commit and push the changes.
    * *Note: You do not need to open a new PR. The existing PR will update automatically when you push!*
4.  **Resolve:** Click the **Resolve conversation** button on each comment thread on GitHub.
5.  **Merge:** Once your partner gives the final **Approval**, click the green **Merge pull request** button.

---

## Submission Checklist
* [ ] A new file named `resources.md` exists in your `main` branch.
* [ ] The PR history shows a back-and-forth conversation with your partner.
* [ ] All conversations are marked as "Resolved."
* [ ] The PR was successfully merged.
