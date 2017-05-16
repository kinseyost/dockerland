# Dockerland
This is just a docker-compose.yml for running [immutable-redux](https://github.com/kinseyost/immutable-redux)
[immutable-redux-server](https://github.com/kinseyost/immutable-redux-server)
and mongodb in docker.

## Setup
clone the appropriate repos
```
cd ~/<Whereever you want>
git clone https://github.com/kinseyost/dockerland.git # this repo
git clone https://github.com/kinseyost/immutable-redux.git
git clone https://github.com/kinseyost/immutable-redux-server.git
cd dockerland
docker-compose up
```
# Use
* navigate to [localhost:3000](http://localhost:3000) in a couple of browsers
* Any users added to the list will be updated in all instances in Users tab.
