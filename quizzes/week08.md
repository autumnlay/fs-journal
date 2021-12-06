# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Records important metadata about a project which is required before publishing to NPM and defines functional attributes of a project that npm uses to install dependencies, run scrips, and identify the entry point to our package.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
When you are using Node.js
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
Bundling in your NODE_ENV environment variables set to "porduction". Also doing an NPM i. CDN package on the page.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Database Connections
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
The CLI or in your app's acitvity dashboard
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
CLone your github and commit the changes and push to heroku
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branches allow contributors to isolate changes without destabilizing the codebase, for example, fixes for bugs, new features, and versions integration. These changes may be later merged (resynchronized) after testing.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
after automated checks (tests, style, other CI) have completed successfully, but before the code merges to the repository's mainline branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```