# nodejs-docker-webapp
Following the guide at https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

# Build

```bash
docker build -t node-web-app .
```

# Run

```bash
docker run -p 49160:8080 -d node-web-app
```
