mkdir workdir 
cd workdir
git clone https://github.com/haniokasai/docker-minecraft-bedrock-server

git pull
docker build . -t haniokasai/docker-minecraft-bedrock-server
