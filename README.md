# Gitea

This repository contains some essential files that can be used for deploy the Gitea container (standalone mode).

## Preparations

Rename the **env/gitea.env_example** and **env/mysql_gitea.env_example** files to **env/gitea.env** and **env/mysql_gitea.env** and change the parameters correctly.

## Deploy

To deploy the containers, just follow the command below:

```shell
docker compose up -d
```