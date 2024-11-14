# Comandos para gestionar el clúster de Docker


### Iniciar el clúster
```bash
docker-compose up -d
```
### Verificar el estado del clúster
```bash
docker ps
```

### Ingresar al contenedor namenode
```bash
docker exec -it namenode /bin/bash
```

### Crear un directorio en HDFS
```bash
hdfs dfs -mkdir /user
```

### Subir un archivo a HDFS
```bash
hdfs dfs -put localfile.txt /user/datos/
```

### Apagar el clúster
```bash
docker-compose down
```
