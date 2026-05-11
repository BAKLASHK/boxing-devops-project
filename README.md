# Boxing DevOps Project

My first DevOps pet project using:

- AWS EC2
- Ubuntu Server
- Docker
- Nginx
- GitHub

## Run project

```bash
docker run -d -p 80:80 -v $(pwd):/usr/share/nginx/html nginx1~
