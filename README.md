# hello-world
> Vue example app. Can be served via docker-nginx and locally via node

App available at `localhost.8080`

# Running the app over Node.js
## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Lints and fixes files
```
yarn run lint
```

### Run your unit tests
```
yarn run test:unit
```

### Run your end-to-end tests
```
yarn run test:e2e
```

# Running the app over docker + nginx
## Build docker image
```
docker build -t vuejs-cookbook/dockerize-vuejs-app .
```
## Run containers
```
docker run -it -p 8080:80 --rm --name dockerize-vuejs-app-1 vuejs-cookbook/dockerize-vuejs-app
```


### Info
[Vue-cli](https://cli.vuejs.org/guide/creating-a-project.html#vue-create)    
[Docker+nginx](https://vuejs.org/v2/cookbook/dockerize-vuejs-app.html)
