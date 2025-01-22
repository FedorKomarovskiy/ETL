# ETL-процессы

## Домашнее задание 2 

### Приведение JSON формата к линейной структуре:


```bash
$ docker run --name nifi \
>   -p 8443:8443 \
>   -v C:/Users/Фёдор/Documents/ETL/HW2:/opt/nifi/nifi-current/data \
>   -d \
>   -e SINGLE_USER_CREDENTIALS_USERNAME=admin \
>   -e SINGLE_USER_CREDENTIALS_PASSWORD=ctsBtRBKHRAx69EqUghvvgEvjnaLjFEB \
>   apache/nifi:latest

```

Конфигурация процесса описана в файле JSON.json

