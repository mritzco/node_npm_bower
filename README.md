# docker_node

Builds on docker_node which runs a script mounted on src.
This docker is for running production code from dist folder:
- Copies the from /dist folder code
- installs bower and npm packages as required
- Runs as production
- runs index.js by default but can be overriden by passing a parameter
- Pass bash as parameter to start in terminal instead of running node (useful for debugging)
