# moviesapp-assignment01-2022



## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

- [ ] [Create](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://github.com/keithbutler-wit/moviesapp-assignment01-2022.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/project/integrations/)

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Automatically merge when pipeline succeeds](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing(SAST)](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://docs.gitlab.com/ee/user/clusters/agent/)

***

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!).  Thank you to [makeareadme.com](https://gitlab.com/-/experiment/new_project_readme_content:66f52974c694a0a5196c76dfd303a95f?https://www.makeareadme.com/) for this template.

## Moviesapp-assignment02-2022

## Description
A react app that utilizes the [TMDB](https://www.themoviedb.org/) api to view movies, tv shows and actors.

### Features

## Badges
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

## Usage
To install the dependencies use the command:
``` sh
npm install
```

To start the development server run the following command from inside the project directory:
``` sh
npm start
```

To run the storybook of the project use:
``` sh
npm run storybook
```

## Roadmap
* [x] UI - New Views/pages
  * [x] Actors
  * [x] Most Popular Movies
  * [x] Tv Series
* [x] Routing
  * [x] One additional parameterized URL (Tv Show details)
* [x] Extensive data hyperlinking 
* [x] Data model - Full Caching Support
* [ ] Routing - Basic authentication
  * [ ] Private and Public Routes 
  * [ ] Premium functionality
* [x] Storybook support
  * [x] Actors Page
  * [x] Tv Shows Page
  * [x] Tv Show Details
* [ ] Functionality
  * [x] Favourite Actors
  * [ ] Extended Filtering and/or Sorting
  * [ ] Ordered Favourites
  * [x] Movie Playlists
* [ ] Pagination
* [ ] 3rd party authentication e.g. Firebase
* [ ] Backend persistence - e.g. TMDB Lists, Firebase
* [ ] Rich Feature Set

## License
For open source projects, say how it is licensed.
