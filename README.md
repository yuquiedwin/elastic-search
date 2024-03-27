# EKL-Stack

## Clonar repositorio
Para clonar el repositorio debe abrir una terminal y usar el comando <br>
`git clone https://github.com/yuquiedwin/EKL-Stack.git`

## Crear y configurar el archivo .env en la raiz del proyecto <br>
├── .env <br>
├── .gitignore <br>
├── docker-compose.yml <br>
├── README.md

Dentro del archivo, pegar lo siguiente:
`STACK_VERSION=8.4.0`
`ES_PORT=9200`
`KIBANA_PORT=5601`

# Ejecutar el contenedor
Para ejecutar el contenedor abre una terminal y ejecuta el comando: <br>
`docker compose up`

## Entra a localhost:5601 para entrar al panel de Kibana y a localhost:9200 para corroborar elasticsearch
> Puede tardar unos minutos en cargar

