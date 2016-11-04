# NGINX Docker Reverse Proxy

* Add app1.localhost and app2.localhost in your /etc/hosts
* Run `docker-compose up`

The results

```bash
$ curl app1.localhost
hello APP1
$ curl app2.localhost
hello APP2
```
