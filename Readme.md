# create-easy-react

## How to run "<em>Linux users only</em>"

1. first you need to clone the repository.
2. go to the directory of the repository that you cloned through your terminal.
3. type `pwd` , copy the output using CTRL+SHIFT+V
4. type `cd` to navigate to your home directory, then open the .bashrc file using and command-line text-editor "i prefer nano so i'll use it but you can use whatever you want"
5. type `nano .bashrc`
6. go to the end of the file and add the following: `PATH=$PATH:CLONED_REPO_PATH`, replace "CLONED_REPO_PATH" with the copied text in your clipboard by clicking CTRL+SHIFT+V in the temrinal.
7. click CTRL+S to save if you are using nano then CTRL+X to close, or :wq! in command mode for vim or whatever your text-editor saving shortcut and then exit.
8. restart your terminal.
9. now go to the directory you want to save your react project to, and run the script by typing `. create-easy-react project_name` and wait for it :wink:


---


<em>**create-easy-react**</em> is a shell script that prepare your react project. it installs all the common packages for your project such as:

- Bootstrap
- Axios
- Redux
- Redux DevTools *you need to install the Redux DevTools chrome extension for this to take effect, download it [here](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en)*
- React Router
- maybe more soon! :smile:

---


<em>**create-easy-react**</em> generates this project structure for you :

```bash
.
└── /src
    .
    ├── /components
    ├── /css    
    ├── /pages                           
    ├── /actions
    ├── /reducers
    ├── index.js
    └── App.js
```

1. components: Add here any standalone component.
2. css: Add here all your css files.
3. reducers: Add all your reducer files there with same syntax of reducerExample and then add their names in src/reducers/index.js to make them visible to your redux store.
4. actions: Add all your actions in src/actions/index.js with same syntax as the example and import it wherever you want.
5. pages: Add here your main pages that goes in the src/App.js file.

---

<em>**create-easy-react**</em> imports everything. redux store is initialized in App.js .
All you need to do is to import the hooks you will use, import axios wherever you will use it, customize your routes in App.js file and you are good to go!
