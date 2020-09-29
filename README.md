# Def Hacks Learn - CS Outreach Website

## Instructions:

To install on your local machines

- git clone 'the url.git'
- cd repo
- npm install

# To start making actual changes:

If you are not added as a contributor, you won't be able to make actual changes, therefore,
once you are done installing all the dependencies, to start out making changes create a .env file in the root directory

- "on bash": touch .env
- "on cmd": echo '' > .env

and ask for environment variables from the project lead and then you can start making actual changes to the deployed site

# Before pushing code or submitting a PR

To run linting and tell you what is wrong with your code

- npm run lint

To format all the code based on prettier and linting configuration

- npm run format

# File structure

Most files are configuration related on the root folder. The public folder includes the static files
to be served for hosting, but pre-build process. All components, styles, pages can be found inside the
src folder.

## Quick Map

  - def-hacks-learn/
    - public/
        - index.html
        - favicon.ico
        - assets/
            - images/
    - src/
        - firebase/
        - components/
        - styles/
        - pages/
        - App.js
        - Index.js
   - package.json
   - README.md
        


