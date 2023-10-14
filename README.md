# kevin-humes-memorial
Kevin Humes Memorial Foundation Website


## To Do


## Docker Run Command

1. This will start a shell where you can launch the development server

```
docker run --rm -it \
  --name kevin-humes-memorial \
  -v $(pwd):/src \
  -p 1313:1313 \
  klakegg/hugo:0.93.2-alpine \
  shell
```

2. Push updates to main branch and netlify will build and deploy the site