# docker-build-react-env


* `./build-nodejs-image`   

Generating a nodejs v10 docker image, named `nodejs_v10:latest`.

* `./build-react-image`   

Generating a docker image based on previous one, this image owns [create-react-app](https://github.com/facebook/create-react-app) and [nwb](https://github.com/insin/nwb). (No harms from the warnings while installing nwb, ignore them)

* `./build-react-container [container name] [mounting directory] [port forwarding]`   

Generating a container.

ex: `./build-react-container react_env /Users/Apple/Development/ReactApp 3333` 