# pinger

network pinger with UI

usage:
screenshot
<img width="1244" alt="image" src="https://github.com/dyipon/pinger/assets/35313394/9c9b38eb-601a-4f2a-9f5b-e20e47245a68">

## to run

```sh
docker build -t pinger .
docker run -p 8080:8080 -e PINGER_IPS="1.1.1.1,8.8.8.8" pinger
```

or just

```sh
docker-compose up
```
