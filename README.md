# Full-stack livechat example

This repository contains a [slack](https://slack.com) clone made with [PostgreSQL](https://www.postgresql.org/), [Go](https://golang.org/), and [Docker Compose](https://docs.docker.com/compose/install/)

This demo is visible at [slonk.cidemo.co](https://slonk.cidemo.co)

To deploy:
```
ssh -i ./slonk_machine_key -o StrictHostKeyChecking=no root@51.222.87.188 "rm -rf /tmp/build 2>/dev/null; git clone https://github.com/layerdevopsdemo/livechat-example.git /tmp/build && cd /tmp/build && docker-compose build --parallel && docker-compose up -d --force-recreate --remove-orphans"
```
