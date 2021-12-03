# cypress-2-cucumber 🥒
As a Test Automation Engineer working with Cypress.io I've been strugling to find some solutions for my problems. 
I tried to find a way to create a report for my Cypress tests and the best one that I found was using Cucumber, but I had a problem.
All of my code/tests was done and now, using Cucumber, I need to change all the template. It means, no describe() and no it(), etc etc. Like, you know.
So I spend some time creating a batch file that you can run it inside of project folder and this batch file will convert all of your Cypress code to Cucumber.

## Usage
This is basically a `batch`file, so you just need to be using Windows and run this file inside you project.

Location for your cypress-2-cucumber.bat file:
```javascript
$ YOUR_CYPRESS_PROJECT
.
├── cypress
│   ├── fixtures
│   ├── integration
│   ├── plugins
│   └── support
├── cypress.json
├── package.json
└── cypress-2-cucumber.bat
```
