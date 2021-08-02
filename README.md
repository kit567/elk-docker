# elk-docker
file for elk deploy with docker

## Назначение файлов
create-certs.yml - Файл создает сертификаты на нод согласно файлу **instances.yml**.

Folder structure example:
.
*__**certs**
|   * **es01**
|=       |=      |=_*es01.crt*
|=       |=      |=_*es01.key*
|=       |=__**es02**
||       ||      ||_*es02.crt*
||       ||      ||_*es02.key*
||       ||__**kib01**
|        ...
|__**conf**
|       |_*logstash.conf*
|       |_*logstash.yml*
|__*docker-compose.yml*
