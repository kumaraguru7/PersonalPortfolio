
## A clean, beautiful and responsive portfolio template for Developers!

## Sections 
✔️ Summary and About me\
✔️ Skills\
✔️ Work Experience\
✔️ Open Source Projects Connected with Github\
✔️ Big Projects\
✔️ Achievements And Certifications 🏆\
✔️ Blogs\
✔️ Talks\
✔️ Podcast\
✔️ Contact me\
✔️ Twitter Timeline\
✔️ Github Profile


## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer or use [Docker](https://www.docker.com/products/docker-desktop).

```
node@v10.16.0 or higher
npm@6.9.0 or higher
git@2.17.1 or higher
```



## How To Use 🔧

```bash
# Clone this repository

# Go into the repository
$ cd developerFolio

# Install dependencies
$ npm install

#Start's development server
$ npm start
```
## Github Setup For Open Source Projects

Generate a Github personal access token using these [Instructions](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line) `Make sure you don't select any scope just generate a simple token`

1. Create a file called .env in the root directory of your project.

```bash
- DeveloperFolio
  - node_modules
  - public
  - src
  - .env         <-- create it here
  - .gitignore
  - package-lock.json
  - package.json
```

2. Inside the .env file, add key `REACT_APP_GITHUB_TOKEN` and assign your github token like this.

```javascript
 // .env

  REACT_APP_GITHUB_TOKEN = "YOUR GITHUB TOKEN HERE"

};
```

Set `showGithubProfile` to true or false to show Contact Profile using Github, defaults to false.

## Change and customize every section according to your need.

#### Personalize page content in `/src/portfolio.js` & modify it as per your need.

#### Using Emojis

For adding emoji 😃 into the texts in `Portfolio.js`, use the `emoji()` function and pass the text you need as an argument. This would help in keeping emojis compatible across different browsers and platforms.

