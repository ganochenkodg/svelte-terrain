# Perlin Terrain generator
[Simple web-app](https://svelte-terrain.netlify.app/) to generate terrains from perlin noise functions.

![](https://github.com/ganochenkodg/svelte-terrain/blob/master/images/map1.png)

![](https://github.com/ganochenkodg/svelte-terrain/blob/master/images/map2.png)

![](https://github.com/ganochenkodg/svelte-terrain/blob/master/images/map3.png)

## Getting started

Clone this repo and switch to the directory where this project has been cloned...

```
git clone https://github.com/ganochenkodg/svelte-terrain.git
cd ./svelte-terrain
```

...install all project dependencies...

```
npm install
```

...and run it for developing...

```
npm run dev
```
...then open [http://localhost:5000](http://localhost:5000)...
...or build the application.

```
npm run build
```

Also it have Dockerfile for dockerize your app.

```
docker build -t terrainapp ./
docker run -p 80:80 terrainapp
```
...then open [http://localhost:80](http://localhost:80).
