# Deploy voting application

Deploy an example of voting application with docker swarm
1. Requirements: docker swarm install
`git clone https://github.com/dockersamples/example-voting-app.git`
2. Launch the creation of the stack 
- docker stack deploy -c file_name.yml name_stack:`docker stack deploy -c docker-stack.yml vote-stack`
- test: `docker stack ls`, `docker stack ps vote-stack`

