# phpma-docker

`git clone https://github.com/flyingcakes85/phpma-docker`

Put your PHP code inside `php/www`, run `docker compose up -d` and it will be accessible at [http://localhost:8080](http://localhost:8080/).

Before updating your code, run `docker compose down`, change your code, then `docker compose up -d` again.

phpMyAdmin is accessible at [http://localhost:8081](http://localhost:8081).

For Mariadb, the creds are:
- Host: `phpma_maria`
- root user: `root`
- root password: `defaultpassword`
