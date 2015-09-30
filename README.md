NodeJS blog using MongoDB
=========================


# Blog project for M101JS

`./app.js - entry point`
`./package.json - npm package description`
`./posts.js - Posts Data Access Helper`
`./sessions.js - Sessions Data Access Helper`
`./users.js - Users Data Access Helper`
`./views/ - html templates`

# Getting started

```
npm install
```

# Importing posts
If you want to have some posts in your blog, you can upload them using posts.json
There are 1000 entries with lots of comments and tags. You must load this dataset to complete the problem.

from the a mac or PC terminal window
```
mongoimport -d blog -c posts < posts.json
```


# Starting app
 - After that, start NodeJS application

```
node app.js
```


Visit my [website](http://grafo.in.ua/)