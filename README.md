## Usage
http://localhost:8080/?url=github.com/facebook/react

## Demo 
https://circumlocution.herokuapp.com/?url=example.com
 
## Deployment
1. Add buildpack for Puppeteer
```
heroku buildpacks:add https://github.com/jontewks/puppeteer-heroku-buildpack
```

2. Push to heroku
```
git push heroku master
```
