---
path: '/materials/do'
type: 'GitHub'
img: './screenshot.png'
material:
  title: 'do'
  url: 'http://do.1ven.me/'
  github_url: 'https://github.com/1ven/do'
  subscribers_count: '6'
  stargazers_count: '280'
  tags: ['']
  subtitle: '📋 Notes management application built with React and Redux'
  clone_url: 'https://github.com/1ven/do.git'
  ssh_url: 'git@github.com:1ven/do.git'
  pushed_at: '2018-11-30T08:52:36Z'
  updated_at: '2019-02-02T20:47:46Z'
  author:
    name: '1ven'
    avatar: 'https://avatars2.githubusercontent.com/u/12725024?v=4'
    github_url: 'https://github.com/1ven'
  latestRelease:
    tag_name: null
    name: null
    url: null
    created_at: null
---
## Notes management application built with React and Redux.
Try the demo at [do.1ven.me](http://do.1ven.me). Username - `test`, Password - `123456`.  

![preview](https://cloud.githubusercontent.com/assets/12725024/17184860/17f1c93c-5437-11e6-9ec5-fc6b246fb966.png)
## Stack:
| Package | Description |
| --- | --- |
| `react` | Awesome JavaScript library for building ui
| `redux` | Predictable state container for JavaScript apps
| `react-router` | Routing library for React
| `redux-saga` | An alternative side effect model for Redux apps
| `normalizr` | Normalizes nested JSON according to a schema
| `reselect` | Selector library for Redux
| `redux-devtools` | DevTools for Redux library
| `babel` | Compiler for writing next generation JavaScript
| `webpack` | Module bundler

## Installation:
1. This application requires `postgresql` database. To install it, go to this [link](https://www.postgresql.org/download/).  
2. After, you need install all dependencies using this command:
  ```
  npm install
  ```  

3. Next, you should create config `.env.develop` and `.env.production` files:
  ```
  DATABASE_URL='Place here postgres connection string like `postgres://user:password@localhost:5432/database_name`'
  JWT_SECRET='Place here jwt secret string. Can be used any long string'
  NODE_ENV='Should be `development` or `production` according to environment'
  PORT=3000
  ```
  If you want to run tests, also you need to define `.env.test` file.  

4. Before running application, you should run `postgresql` database. In most cases it should be:
  ```
  postgres -D /usr/local/var/postgres
  ```
5. Next, you can run application:  

  #### In development mode:
  ```
  npm run development
  ```
  #### In production mode:
  ```
  npm run production
  ```

## Npm commands:
| Command | Description |
| --- | --- |
| `npm install` | Install project dependencies and build client js file |
| `npm run development` | Run server with webpack in `development` mode |
| `npm run production` | Run server in `production` mode |
| `npm run bundle` | Build client javascript file for production |
| `npm run deploy` | Deploy app to heroku |
| `npm run tests` | Run client and server tests |
| `npm run tests-client` | Run client tests |
| `npm run tests-server` | Run server tests |
## Todo
- Implement drag and drop for Boards, Lists and Cards.
