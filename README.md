# Profile in Terminal Tutorial
---
> ## Pre-Requisites
- Must have ```Node.js``` installed.
- Must have ```Git``` installed. 
- Must have an [npm](https://www.npmjs.com/) account. If you don't have one, just login and create one. 
> ## Step 1
1) Create a Github Repo and clone it on your local pc. 
2) Open it with your favourite IDE/Text Editor. 

> ## Step 2
1) Create an index.js file. 
2) Open up the terminal in that directory. 
3) Enter the command 
```bash
npm init
```
This will initialise the index file with a `package.json` file.

> ## Step 3
1) Edit the `package.json` file just like I did. In accordance to the package name i.e., command name for your npx intro. 
Make sure you have bin defined in the file. 
```json
"bin": {
  "my-npx-command": "index.js"
},
```
2) Edit the `index.js` file according to your preference. You can take help of my template. 
> ## Step 4 
1) Make your file an executable script by enterring the following command. 
```powershell
git update-index --chmod=+x index.js
```
> ## Step 5
1) Login into your npm account via the terminal with the following command. 
```bash
npm login
```
2) After logging in simply publish your package to your account using the following command.
```bash 
npm publish
```
VOILLA ! You ARE SET. 

Open up you command prompt and ask your friends to explore this as well. 

