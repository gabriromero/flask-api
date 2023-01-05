# CONTRIBUTING

## How to run Dockerfile in local

```
docker run -dp 5005:5000 -w /app -v "$(pwd):/app" IMAGE_NAME sh -c "flask run"
```