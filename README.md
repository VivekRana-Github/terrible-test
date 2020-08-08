# terrible-test
Terribly Tiny Tales Test Website

# Details
A Node.js app using [Express](http://expressjs.com/).
The application fetches a list of top N frequent words from a .txt file [file](http://terriblytinytales.com/test.txt).

The running demo of the web application is available on this link [https://terribly-tiny-tales-app.herokuapp.com//](https://terribly-tiny-tales-app.herokuapp.com//).

## How to run locally
```sh
git clone https://github.com/VivekRana-Github/terrible-test
cd terrible-test
npm install
npm start
```
Your app should now be running on [localhost:3000](http://localhost:3000/).

## Test Cases Screenshots
![](public/t1.png)

![](public/t2.png)

![](public/t3.png)

![](public/t4.png)

## Deploying to Heroku

```
heroku create
git push heroku master
heroku open
```

Alternatively, you can deploy your own copy of the app using the web-based flow:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


## NodeJS Libraries
    
    "body-parser": "^1.18.2",
    "consolidate": "^0.15.0",
    "express": "^4.16.2",
    "path": "^0.12.7",
    "request": "^2.83.0"
    

