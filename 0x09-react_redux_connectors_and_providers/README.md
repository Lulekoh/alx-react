## 0x09-react_redux_connectors_and_providers

* Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

Redux connectors and how to use them
The different functions you can pass to a connector (mapStateToProps, mapDispatchToPros)
How to map an action creator to a component using a connector
How to map an async action creator to a component with Redux Thunk
What Redux Providers are and how to set up your app’s store
How you can improve a connector’s performance using Reselect
How to use Redux’s dev tools to debug the state of your application

* Requirements
Allowed editors: vi, vim, emacs, Visual Studio Code
All your files should end with a new line
A README.md file, at the root of the folder of the project, is mandatory
All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node 12.x.x and npm 6.x.x
Push all of your files, including package.json and .babelrc
All of your functions must be exported

## Provided files
* dashboard/dist/courses.json
```bash

[
  {
    "id": "1",
    "name": "ES6",
    "credit": 60
  },
  {
    "id": "2",
    "name": "Webpack",
    "credit": 20
  },
  {
    "id": "3",
    "name": "React",
    "credit": 40
  }
]

* dashboard/dist/login-success.json
Click to show/hide file contents

{
  "first_name": "Johann",
  "last_name": "Salva",
  "email": "johann.salva@holberton.nz",
  "profile_picture": "http://placehold.it/32x32"
}

* dashboard/dist/notifications.json
