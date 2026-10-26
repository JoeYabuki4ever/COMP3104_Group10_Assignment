\# COMP3104 Group 10 Assignment



\## Project Description

This project demonstrates collaboration using Git and GitHub for the

COMP3104 DevOps course at George Brown College. Team members use

personal branches, meaningful commits, pull requests and an automated

GitHub Actions workflow to manage their contributions.



\## Team Members



| Name | Student ID | GitHub Profile | Role |

| --- | --- | --- | --- |

| Taharim Haque | 101418321 | To be added | Group Leader |





\## Repository

https://github.com/JoeYabuki4ever/COMP3104\_Group10\_Assignment



\## Setup Instructions

1\. Install Git.

2\. Clone the repository:



&#x20;  git clone https://github.com/JoeYabuki4ever/COMP3104\_Group10\_Assignment.git



3\. Enter the project folder:



&#x20;  cd COMP3104\_Group10\_Assignment



4\. Create your personal branch using your student ID and name:



&#x20;  git checkout -b STUDENTID-Name



5\. Add or update your assignment files, commit your changes and push

&#x20;  your branch to GitHub.



\## Assignment Files

Each member creates three text files in the repository root:



\- STUDENTID\_gb.txt: Information about George Brown College.

\- STUDENTID\_devops.txt: Information about the COMP3104 DevOps course.

\- STUDENTID\_sdlc.txt: The importance of DevOps throughout the software

&#x20; development life cycle.



Each member must make at least 10 meaningful commits.



\## GitHub Actions

The workflow is located at `.github/workflows/ci.yml`.



It runs on pushes and pull requests using an Ubuntu runner and prints

a confirmation message. This demonstrates automated workflow execution;

it does not validate the accuracy of the text files.



Workflow results can be viewed in the repository's Actions tab.



\## Branch Strategy

\- The `main` branch contains the team's merged contributions.

\- Each member works on a branch named `STUDENTID-Name`.

\- Taharim's branch is `101418321-Taharim`.

\- Members submit pull requests from their personal branches into `main`.

\- A teammate reviews the changes before merging.

\- Merge conflicts are resolved before completing the merge.

\- Use "Create a merge commit" to preserve individual commit history.



\## Pull Request Template

The template is located at `.github/PULL\_REQUEST\_TEMPLATE.md`.

Members describe their changes and complete the applicable checklist

items when opening a pull request.

