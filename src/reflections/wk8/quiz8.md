# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This declares all of the node packages an application needs to function
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
top level, as this is one of the first things that needs to be read.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
In cmd, and on the heroku application.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Since we deploy through github, just updating the branch that heroku watches is enough.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
By having multiple branches you can prevent breaking a live version of the site from breaking by bad code by pushing potentially bad code to a deveelopment branch, and making sure the development branch is working before merging with the live(main) branch.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Always/ at the end of a sprint
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merge
```
