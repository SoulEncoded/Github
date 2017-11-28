# Github

<a href="https://www.youtube.com/watch?v=pV06kdwutLU&t"><img src="https://img.youtube.com/vi/pV06kdwutLU/0.jpg" width="500" /><a/>

## What is Github
<img src="assets/octocat.gif" width="200"/>

Github may have the coolest mascot in the tech industry. The above image is the famous Octocat. If you ever visit Silicon Valley you will see this cute creature plastered on developers Mac Books. So what exactly is Github and why is it so important for developers.

<strong>Github is a web based git version control service that hosts your repository.</strong>

It short Github lets you put your code online.

There are other services that provide online repository hosting, but learning Github will serve you well on your journey to becoming a software engineer.

Here is also a great video from Github about what Github is. [Link](https://www.youtube.com/watch?v=w3jLJU7DT5E)

## Terminology

- repository: Copy of your code base online.
- origin: This is a alias of the remote address to your Github repository.
- master: This is just a name of a branch. It happens to be called master and it is by convention called master.
- pull request (pr): proposed changes submitted by users.
- forking: is a way for other users to make a personal copy of the entire repository.
- open source: software that can be freely used, modified, and shared in both modified and unmodified form by anyone. Open source is very important in the developer community.

[Official Glossary from Github](https://help.github.com/articles/github-glossary/)

## The Problem

So why do need a repository of our codebase online?

1. A Central place to work off one code base.
2. Allows for easy collaboration with other engineers.
3. Makes open source possible.

## Example Workflow
Below is a simple workflow using Github

Steps:
1. Create online repository on Github.
2. Link online repository with local code base.
3. Push code base to Github.
4. make changes to local repository on a new branch
5. Push new branch up to repository.
6. Create a pull request from new branch to master branch
7. Other developers review the changes and merge the new branch into master
8. On the local branch pull the changes from master.

## The Essentials

- `git fetch`: fetches the latest changes from the online repository.
- `git pull`: fetches the latest changes from the online repository and merges them.
- `git push`: pushes the local committed changes to the online repository.
- `git clone`: copies a online repository to a local directory.
- `git remote`: shows where the online repository is pointed to.

## The Challenge
NOTE: If you haven't already create a Github account. Make sure to choose a username that you won't mind putting on a resume. It's very common practice for employers ask you about your Github account as it is a great place to see your sample work. Treat it like your portfolio.

Steps:
1. create a new repository
2. clone the repository to a local directory
3. make changes and commit those changes
4. push your changes to the Github
5. create and checkout a new branch
6. make changes to your new branch and commit them
7. push the new branch to the Github
8. In Github create a new pull request merging your new branch back into the master branch
9. If there are any merge issues, resolve the conflict then merge the new branch into the master branch
10. on your local directory, pull the new merged in changes

## The Solutions

<a href="https://www.youtube.com/watch?v=yvto-_4aVwU&t">Github Challenge Solutions</a>

## Additional Resources
[Github Guides](https://guides.github.com/)
