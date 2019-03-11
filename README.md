```sh
# start docker
# httpd (apache) can be seen after that in test1.reviewapp.delfi.net
docker run --rm -d -P --name=example1 -l traefik.frontend.rule=Host:example1.awstest1.kassikas.com httpd
 
# stop docker
docker stop example1 || true
```
