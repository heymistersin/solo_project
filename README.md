mkdir frontend backend

nom install mongodb

npm install -D eslint
npm init @eslint/config

Need to install the following packages:
  @eslint/create-config@0.4.6
Ok to proceed? (y) y
✔ How would you like to use ESLint? · problems
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · react
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser
✔ What format do you want your config file to be in? · JSON
The config that you've selected requires the following dependencies:

eslint-plugin-react@latest
✔ Would you like to install them now? · No / Yes
✔ Which package manager do you want to use? · npm
Installing eslint-plugin-react@latest

added 93 packages, and audited 204 packages in 7s

90 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
Successfully created .eslintrc.json file in /home/daniel/Codesmith/solo_project

touch webpack.config.js
npm install -D webpack webpack-cli
npm install -D webpack-dev-server
