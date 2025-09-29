# Simple Go Health Check App

Una aplicación web minimalista en Go que implementa un endpoint de health check básico.

## 🚀 Características

- Endpoint `/ping` que responde con `pong`
- Servidor HTTP simple corriendo en el puerto 8080
- Código minimalista perfecto para aprendizaje

## 📋 Requisitos

- Go 1.16 o superior

## 🛠️ Instalación y Uso

1. **Clonar el repositorio**
   ```bash
   git clone <url-del-repositorio>
   cd simple-go-app
   ```

2. **Ejecutar la aplicación**
   ```bash
   go run main.go
   ```

3. **Probar el endpoint**
   ```bash
   curl http://localhost:8080/ping
   ```
   
   O abre tu navegador y visita: `http://localhost:8080/ping`

## 📝 API Endpoints

| Método | Endpoint | Respuesta |
|--------|----------|-----------|
| GET    | `/ping`  | `pong`    |


## 💻 Ejemplo de Respuesta

```bash
$ curl http://localhost:8080/ping
pong
```
