# vuejs-nginx-docker
In this project, I am going to use Vue.js as a JS library, NGINX as a web server and docker as a container runtime
Install node.js to use npm command

Install Vue VLI via npm 
npm install --global vue-cli
or 
npm install -g @vue/cli@latest
Check Vue version to make sure the installation was successful
vue --version
// install and start the dependencies
npm install
npm run serve

// build the docker image
docker build -t vue-ui .
// run the app
docker run -d --name vueui -p 80:80 vue-ui
