# Wekan

Wekan is an open-source kanban board which allows a card-based task and to-do management.

## Security Caution

docker-compose.yml is for secure network. (etc. in VPN)
Therefore, don't use insecure network like global network.

## Install

Replace `<<>>` in docker-compose.yml, and run below command.

  ```
  $ docker-compose up -d
  ```

## Backup

Save `<<YOUR DIRECTORY PATH>>` of volumes and docker-compose.yml.

## Restore

1. Deploy `<<YOUR DIRECTORY PATH>>`.
1. Run `$ docker-compose up -d`.
