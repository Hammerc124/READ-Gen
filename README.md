# READ-Gen
a READ.ME generator
## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Images](#images) 
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [License](#license)

## Description

When creating an open source project on GitHub, it’s important to have a high-quality README for the app. This should include what the app is for, how to use the app, how to install it, how to report issues, and how to make contributions&mdash;this last part increases the likelihood that other developers will contribute to the success of the project. 
You can quickly and easily create a README file by using a command-line application to generate one. This allows the project creator to devote more time to working on the project.

The task is to create a command-line application that dynamically generates a professional README.md file from a user's input using the [Inquirer package](https://www.npmjs.com/package/inquirer/v/8.2.4). 

The application will be invoked by using the following command:

```bash
node index.js
```

## User Story

```md
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
```

## Images
## The Terminal
![Website Preview Image](./assets/images/input-preview.png)
## The Output
![Website Preview Image](./assets/images/output-preview.png)


## Link To Video Walkthrough

https://drive.google.com/file/d/1hP8R8CLM-FFfl4w8t-HecwBuNYV88CYc/view



## Installation
- To clone the repo: https://github.com/Hammerc124/READ-Gen
- Uses the [Inquirer package](https://www.npmjs.com/package/inquirer/v/8.2.4).

## Technologies Used
Assignment was built with:
- JavaScript
- Inquirer
- Node.js
- VS Code
- Github

