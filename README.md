[![Build Status](https://travis-ci.org/cljs-machine/hello-lambda-jakarta.svg?branch=master)](https://travis-ci.org/cljs-machine/hello-lambda-jakarta)

1. Clone the repo
2. `lein npm install`
3. `lein cljsbuild once`

Try `lein npm run uname` and `lein npm run whoami` 

4. `sudo $(which lein) npm link`

Try `lj-whoami` and `lj-uname`


if you want start with docker container, you can do [docker pull sofianhw/cljs-docker](https://hub.docker.com/r/sofianhw/cljs-docker/) from your terminal.
