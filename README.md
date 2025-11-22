# Aplicación Web CNN para Clasificación de Cáncer

## Requisitos

- Docker

## Cómo ejecutar

1. Clonar el repositorio (con submódulos):

```bash
git clone --recurse-submodules https://github.com/manuelmartinezr/cnn-cancer-classification.git
cd cnn-cancer-classification
```

2. Construir y levantar los contenedores:
```bash
docker compose up --build
```

3. Abrir el navegador:
```bash
Frontend: http://localhost:8080
Backend FastAPI (opcional, docs): http://localhost:8000/docs
```
