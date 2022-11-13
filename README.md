# MovieListApp-with-Redis-Caching

```
clone Repository
install node modules in client and server
```

1. cd into MovieListApp-with-Redis-Caching

2. setup client 
```
cd client 
npm i
npm start
```
3. setup server
```
cd server
npm i
npm run dev - to run with nodemon
npm start - to start server without nodemon
```
4. To deploy in Heroku
```
1.run npm run build in client
2.copy the build pack contents into servers public folder, create if not present
```
# Now that you have React UI in servers public folder , deploy only the server folder in Heroku



