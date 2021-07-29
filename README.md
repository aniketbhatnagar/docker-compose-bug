# Repo to reproduce ctrl+c not working

Steps:
1. Start using `docker-compose run server`
2. Press `ctrl + c` and notice it doesn't work

Note: If the container was started using `docker-compose up server` OR `docker run duluca/minimal-node-web-server`, ctrl + c works.
