# kevin-humes-memorial
Kevin Humes Memorial Foundation Website


## To Do
1. Create Posts
  - Bench
  - 2021 Walk
  - Baggo Tournament
  - Christmas Donations


## Docker Run Command

```
docker run --rm -it \
  --name kevin-humes-memorial \
  -v $(pwd):/src \
  -p 1313:1313 \
  klakegg/hugo:alpine \
  shell
  ```

