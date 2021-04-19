# react and redux todo app

https://redux-todo-localstorage.netlify.app/todo

## project
This is a simple project to practice using redux for state management with react. I wanted to make a simple CRUD application to get used to working with redux, I added react-router so you can see that state persists, and also that the redux store can be used to generate more dynamic urls. 

## technologies
The project uses react, redux, react-redux for the very useful hooks, redux-devtools-extension and react-router-dom. 
**redux-todo-api** also uses redux-thunk for asynchronous actions.

**todo-backend** provides a simple express API and Postgres database for the project

**todo-demo** temporarily stores the redux store with localstorage - you can try the demo at the above link

## to run
See submodules for instructions - **redux-todo-api** relies on **todo-backend** so you will need to run them at the same time.
