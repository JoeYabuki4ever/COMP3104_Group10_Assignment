# COMP3104 Group 10 Assignment — Individual Submission

## Project Description

This repository is for the COMP3104 DevOps assignment at George Brown College. Although the repository retains the assigned **Group 10** name, **Taharim Haque is completing the project individually with the instructor's permission**. This is not a multi-member submission, and no other students are associated with this assignment submission.

The project demonstrates Git version control, a personal developer branch, meaningful commits, pull requests into `main`, and a basic continuous integration (CI) workflow using GitHub Actions.

## Student / Sole Contributor

| Student | Student ID | GitHub profile | Submission role |
| --- | --- | --- | --- |
| Taharim Haque | 101418321 | [JoeYabuki4ever](https://github.com/JoeYabuki4ever) | Sole contributor / submitter |

**Individual-work arrangement:** The instructor has permitted this assignment to be completed by one student. Requirements about gathering files, commits, or screenshots from *other* group members therefore do not apply to this submission. The remaining technical requirements, including creating three files and at least 10 authentic commits, still apply unless the instructor separately waived them.

## GitHub Repository

[COMP3104_Group10_Assignment](https://github.com/JoeYabuki4ever/COMP3104_Group10_Assignment)

## Setup Instructions

1. Install Git, then clone the repository:

   ```bash
   git clone https://github.com/JoeYabuki4ever/COMP3104_Group10_Assignment.git
   cd COMP3104_Group10_Assignment
   ```

2. Switch to the individual development branch:

   ```bash
   git fetch origin
   git switch 101418321-Taharim
   # If the branch exists only on GitHub, use:
   # git switch --track origin/101418321-Taharim
   ```

3. Edit the three assignment files in the repository **root** and create genuine, descriptive commits whenever meaningful work is completed:

   ```bash
   git add 101418321_gb.txt 101418321_devops.txt 101418321_sdlc.txt
   git commit -m "Improve research and explanations"
   git push -u origin 101418321-Taharim
   ```

   Run `git status` before committing. Git will not create a commit when there are no changes. Do **not** fabricate or backdate commit history.

4. Open a pull request from `101418321-Taharim` into `main`, inspect the diff and CI results, resolve conflicts if necessary, then merge. Retain the GitHub record as submission evidence.

## Assignment Files

The sole contributor, Taharim Haque, maintains these three root-level files:

| File | Required content |
| --- | --- |
| `101418321_gb.txt` | Information about George Brown College |
| `101418321_devops.txt` | Information about the COMP3104 DevOps course |
| `101418321_sdlc.txt` | The importance of DevOps in the software development life cycle |

The assignment asks for **at least 10 descriptive commits per participating student**. Since this is approved individual work, this means **10 genuine commits by Taharim**, unless otherwise directed by the instructor. Commit history is stored in Git/GitHub and is not contained in a downloaded ZIP.

## CI/CD Setup — GitHub Actions

The CI workflow is stored at [`.github/workflows/ci.yml`](.github/workflows/ci.yml).

- Triggers on pushes and pull requests.
- Uses GitHub's `ubuntu-latest` runner.
- Checks out the repository and confirms that the README, pull request template, and Taharim's three assignment text files exist and are non-empty.
- Prints success information to demonstrate an operational pipeline.
- This is a basic CI demonstration; it does not test factual research accuracy, count commits, or deploy an application.

See real run results in the [GitHub Actions tab](https://github.com/JoeYabuki4ever/COMP3104_Group10_Assignment/actions).

## Branch Strategy and Pull Requests

- `main`: integration branch containing completed changes.
- `101418321-Taharim`: Taharim's individual development branch (format `STUDENTID-Name`).
- Work is committed to the individual branch and proposed to `main` with a pull request.
- The pull request template is located at [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md).
- Since the instructor approved individual completion, Taharim can self-review and check the CI result; any additional approval or branch-protection rule set by the instructor still applies.

## Step 9 — Final Submission Evidence

Prepare **one PDF or DOCX**, submitted by Taharim through the designated D2L assignment folder. Include:

1. The GitHub repository URL.
2. One screenshot of **Taharim's local repository setup**.
3. One screenshot of **Taharim's Git commit history**, showing the authentic commits.
4. One screenshot of **the `main` and `101418321-Taharim` branch structure**.
5. One screenshot of **the GitHub Actions CI pipeline status**.
6. A short explanation that this is an **instructor-approved individual submission**. No other group members need to be listed as non-contributors because this submission has no other members.

Capture the screenshots from the actual Git Bash environment/GitHub site. This ZIP contains source files and cannot itself prove prior Git activity or completed CI runs.
