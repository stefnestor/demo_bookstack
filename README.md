## demo_bookstack

https://www.bookstackapp.com

### setup

1. create parent folder with
	- listed `docker-compose.yml`
	- empty folders `db`, `u`, `su` (or preferred naming if you edit `docker-compose`)
1. in directory, run `docker-compose up`
	- if bookstack errors out but mysql doesn't, `docker-compose down` & then re-run
1. navigate to localhost:8080 & login as `admin@admin.com`:`password`
1. edit/change as desired, data will be stored to these three folders

**Disclaimer**: not a good setup for multiple user updates inducing git `MERGE CONFLICT`

### inspiration

- https://github.com/Sermanes/bookstack-docker-k8s/blob/master/docker-compose.yml.dist
- https://gist.github.com/mry/89a93f4f777a277e3b6039972823ca9a
- https://github.com/solidnerd/docker-bookstack