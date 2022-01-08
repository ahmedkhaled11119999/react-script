# create-easy-react

<em>create-easy-react</em> is a linux command that prepare your react project , install all the common packages for your project such as:

- Bootstrap
- Axios
- Redux
- Redux devtools
- React Router

---

<em>create-easy-react</em>  generates a project structure for you like the following :

.
└── /src
    ├── /components
    ├── /pages
    ├── /actions
    ├── /reducers
    ├── index.js
    └── App.js
    
1.components: Add here any standalone component.
2.reducers: Add all your reducer files there with same syntax of reducerExample and then add their names in src/reducers/index.js to make them visible to your redux store.
3.actions: Add all your actions in src/actions/index.js with same syntax as the example and import it wherever you want.
4.pages: Add here your main pages that goes in the src/App.js file.

---

<em>create-easy-react</em> imports everything. redux store is initialized in App.js
All you need to do is to import the hooks you will use, import axios wherever you will use it, customize your routes in App.js file and you are good to go!
