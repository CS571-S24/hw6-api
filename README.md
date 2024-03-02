build
```bash
docker build . -t ctnelson1997/cs571-s24-hw6-api
docker push ctnelson1997/cs571-s24-hw6-api
```

run
```bash
docker pull ctnelson1997/cs571-s24-hw6-api
docker run --name=cs571_s24_hw6_api -d --restart=always -p 58106:58106 -v /cs571/s24/hw6:/cs571 ctnelson1997/cs571-s24-hw6-api
```

run_fa
```bash
docker pull ctnelson1997/cs571-s24-hw6-api
docker run --name=cs571_fa_s24_hw6_api -d --restart=always -p 59106:58106 -v /cs571_fa/s24/hw6:/cs571 ctnelson1997/cs571-s24-hw6-api
```