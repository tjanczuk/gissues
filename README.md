# Welcome to gissues - whiteboard for GitHub issues
===

**Quick start**

- Go to http://gissues.com
- Log in to GitHub using your GitHub credentials and authorize gissues.com to manipulate issues in your public github repositories (using OAuth).
- Choose a repository from the drop-down, then drag & drop your issues across columns in the scrumboard or reorder them within a given column.
- Filter by issue labels, login of the assignee, or login of people mentioned in the issue history.
- The URL in the address bar of the browser is your permalink to the very query you constructed. Sharing that URL allows others to view the same issues as you, as long as they have adequate GitHub permissions (the URL does not capture your authorization information)

**Support**

- [Ask a question or provide feedback](https://github.com/tjanczuk/gissues/issues/new)
- [Review current issues or find an answer to your question](https://github.com/tjanczuk/gissues/issues)
- When filing a bug report, please state your browser and OS make and version

**What you should know about**

- The service is free. 
- The service modifies the description of your GitHub issues by adding a small textual fragment that captures gissues metadata. 
- The service does not otherwise affect any your GitHub projects, issues, comments, wikis, etc. 
- The service is available for private and public repositories.
- It is provided as-is, use at your own risk. 

**Show love**

- If you like the experience provided by gissues, please share it with others.
- You can use the Twitter button, Facebook button, or Google +1 button provided for your convenience in the application in the Recommend drop-down menu.

**Run your own installation of the app**

If you want to run your own installation of the app similar to [http://gissues.com](http://gissues.com), you will need to:

- register the URL of you application as an OAuth application with GitHub [here](https://github.com/settings/applications/new). Use the root of your site for both the URL and Callback URL fields.
- Set the GitHub OAuth client ID and secret using *one* of the following ways:
  - Set the `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET` environment variables to the right value. This is the preferred way when deploying to Azure or AppHarbor sites, so you don't have to commit secrets to your repository.
  - modify the `src/config.json` file with the client_id and client_secret value provided for your application by GitHub.

**Contributions**

I do welcome contributions via pull requests. Thank you for making gissues.com better.

**Acknowledgements**

Special thanks to Starbucks coffee and Tully's coffee for coffee and free WiFi, and King County Library in Sammamish, WA for an inspiring location overlooking the Olympic Mountains (and free WiFi). 