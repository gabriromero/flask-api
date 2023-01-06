# CONTRIBUTING

## How to run Dockerfile in local

```
docker build -t rest-api-flask:latest . 

docker run -dp 5005:5000 -w /app -v "$(pwd):/app" rest-api-flask sh -c "flask run --host 0.0.0.0"
```