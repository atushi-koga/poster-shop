# Vue.js Poster Shop

#### Pre-installation
```
Git
Docker, Docker Machine, Docker Compose
Node.js >=4
NPM
```

#### developing Environment
get source code
```
git init
git clone <this repository URL>
```

create environment
```
docker-machine create --driver virtualbox poster-shop
eval $(docker-machine env poster-shop)
docker-compose up -d
docker-compose exec web bash
```
install package
```
npm install
npm i -S vue@2.5.17
npm i -S vue-resource@1.5.1
npm i -S scrollmonitor@1.2.0
```
run node js server
```
npm run serve
```
Your site will be available at *localhost:3000*.