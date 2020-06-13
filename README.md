# test-github-actions--electron
REACT test project to evaluate how GITHUB ACTIONS will handle ELECTRON 

## Steps to reproduce
1. If you have still 'create-react-app' installed globally (=outdated approach) make sure to remove it with: ```npm uninstall -g create-react-app```
2. Install create-react-app locally in your directory: ```npm i create-react-app --save```
3. Create a default app and choose a template, for instance I choose typescript: ```npx create-react-app react-app --template cra-template-typescript```
4. Following this steps will end in having 2 'node_modules' folders as well as 2 'package-lock.json' files. But we do only need the inner ones, which means you can remove the outer ones, if you do not plan to maintain multiple React apps side-by-side.
5. Navigate into 'react-app': ```cd react-app```
6. View your react app in your Chrome browser: ```npm start```. After few seconds your browser should open a new tab and display the content at: ```http://localhost:3000/``` 



