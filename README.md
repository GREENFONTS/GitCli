# RepoHelper

A CLI tool that utilizes Github Ouath flow and Octokit Pakage to allow users to perform some Github actions such as creating, deleting repos, creating issues and viewing the list of repos owned by the user.

The commands available in the tool:

- getRepos -- lists all the public repos of the user
- createRepo {repoName} -- creates a new repo for the user with the inputted repoName
- delRepo {repoName} -- deletes a public repo for the user with the inputted repoName
- getUserUrl -- gets the user's github url
- repoCloneUrl {repoName} -- gets the user's public repo clone url for the inputted repoName
- createIssue {repoName} -- creates and issue on the public repo of the user with the inputted repoName

The tool is published via .Net Package Installer - Nuget

To install the tool globally, Dotnet CLI will be used:

```
dotnet tool install --global Repo-Cli --version 1.1.1
```

To run the tool on any terminal: `repocli`

### Technologies Used

- [Octokit.net](https://github.com/octokit/octokit.net)
- [Github oauth Device Flow](https://docs.github.com/en/developers/apps/building-oauth-apps/authorizing-oauth-apps#device-flow)
- .Net Console App

### Note

This CLI tool works on only windows OS and must have .NET installed already in the PC. For Contributors, the project was written with version 5 & 6 of .NET

### Contribution

This project is open to codntributors who will like to improve the project
