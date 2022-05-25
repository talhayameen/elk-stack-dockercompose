# elk-stack-dockercompose
By this you can make your elk stack in one command

Just Pull this via

sudo git pull https://github.com/talhayameen/elk-stack-dockercompose.git

cd to the folder,

run :

docker-compose up

NOte: this command will be running without detached mode, when you will press ctrl+c all containers of elk will be closed
if your get all containers ok and runing now you will have to run:

docker-compose up -d....

First check in machine"

docker ps

All container should be running

Now check your browser : localhost:port

Note: Port which I have mentioned in yml file..... I am not telling your so that you will explore it or ask me in comment.
