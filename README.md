# Nodeapp test

`This repo is part of Jenkins_pipeline repo, but we can still use it independently'

## Nodeapp runs on port 3000

### To run docker image
`docker run -d -p 3000:3000 abdullahhafeez/nodeapp`

### To create a new image
`docker build -t [docker-user-id/name:anytag] .`

#### K8s configuration files will used in Jenkins_pipelien repo