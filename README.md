# elk-docker
file for elk deploy with docker

## Назначение файлов
create-certs.yml - Файл создает сертификаты на нод согласно файлу **instances.yml**.

Folder structure example:
>.
>>**certs**
>>>**es01**
>>>>*es01.crt*
>>>>
>>>>*es01.key*
>>>
>>>**es02**
>>>>*es02.crt*
>>>>
>>>>*es02.key*
>>>
>>>**kib01**
>>
>>**conf**
>>>*logstash.conf*
>>>
>>>*logstash.yml*
>
>*docker-compose.yml*
