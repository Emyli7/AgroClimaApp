# AgroClimaApp 🌦️

Aplicación desarrollada en **Python (Flask)** que permite consultar el clima actual por ciudad a través de la API de OpenWeatherMap y almacenar los resultados en una base de datos **PostgreSQL**, ambos ejecutados en contenedores **Docker** conectados mediante `docker-compose`.

## 🚀 Ejecución

1️⃣ Copia el archivo `.env.example` como `.env` y agrega tu clave de API de OpenWeatherMap.

2️⃣ Ejecuta el siguiente comando desde la raíz del proyecto:
```bash
docker-compose up --build
```

3️⃣ Prueba en el navegador o con `curl`:
```
http://localhost:5000/clima/Bogota
```

## 🧠 Componentes

| Servicio | Tecnología | Descripción |
|-----------|-------------|-------------|
| app | Python + Flask | API REST que consulta el clima |
| db | PostgreSQL | Base de datos para almacenar las consultas |
