### Nodejs http server
```bash
# Install dependencies
npm install

# Serve on localhost:5000
npm start
```

```bash
# Deploy heroku
heroku login
heroku create

heroku git:remote -a app-name

git add .
git commit -am "deploy to heroku"
git push heroku master

```