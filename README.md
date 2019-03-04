# node8-bower-polymer

Docker image to run bower and polymer command
Bower: 1.8.8
Polymer-cli: 19.7
Node 8

# Bower example
docker run -v ${PWD}:/tmp phiu2002/node8-bower-polymer bower install

# Polymer example
docker run -v ${PWD}:/tmp phiu2002/node8-bower-polymer polymer build
