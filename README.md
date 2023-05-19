# Install Elasticsearch + Kibana + Filebeat - v(8.7.1)

### Build Docker-compose

- [x] docker-compose --env-file=.env up --build

- [x] docker compose --env-file=.env up --build


### Permission Elastic users

- [x] Dentro do container:
```
    - Este comando faz vc digitar as senhas:
        command: bin/elasticsearch-setup-passwords interactive

        Changed password for user apm_system      
            PASSWORD apm_system = V9TGL4VbU4IGtBOClFdK

            Changed password for user kibana_system      
            PASSWORD kibana_system = V9TGL4VbU4IGtBOClFdK

            Changed password for user kibana
            PASSWORD kibana = V9TGL4VbU4IGtBOClFdK

            Changed password for user logstash_system
            PASSWORD logstash_system = V9TGL4VbU4IGtBOClFdK

            Changed password for user beats_system
            PASSWORD beats_system = V9TGL4VbU4IGtBOClFdK

            Changed password for user remote_monitoring_user
            PASSWORD remote_monitoring_user = V9TGL4VbU4IGtBOClFdK

            Changed password for user elastic
            PASSWORD elastic = V9TGL4VbU4IGtBOClFdK
```