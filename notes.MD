```
npm init 

npm install server 

create folder static
- app.js
- index.html 


cd static 
npx serve -p 5050 static


```

- Create  npm shell command to be recognized inside package json

```
"scripts": {
    "static": "serve -p 5050 static",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```

than use
```
npm run static
```

- Fetching data from api 

```
   const res = await fetch(API)
   const data = await res.json()
```

- creating small server for api 

```
<!-- Main folder -->

server.mjs

and execute:

node server
```

- Using Fasify for mock server 

```
npm add fastify fastify-cli

```

generate fasify folder project 

```
npx fastify generate . --esm
npm install  --> instal dependency
```