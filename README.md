# SuperKart

SuperKart sales forecasting with a Flask prediction API and a Streamlit frontend.

## Run with Docker Compose

Build both images and start the backend and frontend:

```sh
docker compose up --build -d
```

Open the frontend at <http://localhost:8501>. The API is also available at <http://localhost:7860>.
Compose waits for the backend health check before starting the frontend.

To inspect service status and logs:

```sh
docker compose ps
docker compose logs -f
```

Stop the services with:

```sh
docker compose down
```
