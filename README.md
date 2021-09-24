# Docker Compose para Jenkins y Sonarcube

Docker-compose creado con motivos educacionales en el contexto del Curso DevSecOps USACH.

## Uso

### Iniciar
```bash
git clone https://github.com/rzunigac/docker-compose_jenkins-sonarcube.git

cd docker-compose_jenkins-sonarcube

docker-compose up -d
```

### Obtener clave inicial de administrador de Jenkins
```bash
docker-compose exec jenkins cat  /var/jenkins_home/secrets/initialAdminPassword
```

### Detener (sin eliminar contenedores)
```bash
docker-compose stop
```

### Re-iniciar contenedores detenidos
```bash
docker-compose start
```