# Loregon_Docker
Repository responsible for the orchestration and configuration of Docker containers for the Loregon application.

## 🚀 Running in Production

To run **Loregon** with **PostgreSQL** in a production environment, follow the steps bellow:

1. Copy this [Docker Compose](docker-compose.yml)
2. Create a `.env` file from [.env.example](.env.example) in the same folder as the compose file.
3. Run Docker Compose. If everything is correct, the backend environment will be running.

> [!NOTE]
> The best setup to run the server is using Docker with Reverse Proxy

> [!TIP]
> To setup the server on https, I recommend use [NGINX Proxy](https://github.com/nginx/nginx)

> [!WARNING]  
> Make sure to update the environment variables in the Docker Compose file.