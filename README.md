NodeJS blog using MongoDB
=========================
In the project, you will find a blogging platform, backed by `MongoDB`.

Blog project for M101JS
-----------------------
```
./app.js - entry point
./package.json - npm package description
./posts.js - Posts Data Access Helper
./sessions.js - Sessions Data Access Helper
./users.js - Users Data Access Helper
./views/ - html templates
```

# Getting started

Install all requested packages (libraries, modules etc.) from package.json
```
npm install
```

Importing posts
---------------
If you want to have some posts in your blog, you can upload them using posts.json
There are 1000 entries with lots of comments and tags. You must load this dataset to complete the problem.

from the a mac or PC terminal window
```
mongoimport -d blog -c posts < posts.json
```


Starting app
------------
 - After that, start NodeJS application

```
node app.js
```
Note that this requires Node.js to be correctly installed on your computer. After you run the blog, you should see the message:

Express server listening on port 3000. If you goto `http://localhost:3000` you should see the front page of the blog. Here are some URLs that must work when you are done.

---------------------------------------
Visit my [website](http://grafo.in.ua/)
