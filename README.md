# vuejs-nginx-docker
In this project, I am going to use Vue.js as a JS library, NGINX as a web server and docker as a container runtime
Install node.js to use npm command

## Quick Start
* Install Vue CLI via npm 
```sh
npm install --global vue-cli
or 
npm install -g @vue/cli@latest
```

* Check Vue version to make sure the installation was successful
```sh
vue --version
```

* Install and start the dependencies
```sh
npm install
npm run serve
```

* Build the docker image
```sh
docker build -t vue-ui .
```

* Run the app
```sh
docker run -d --name vueui -p 80:80 vue-ui
```
