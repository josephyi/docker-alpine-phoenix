# docker-alpine-phoenix
Dockerized Phoenix Framework in Alpine Linux

```` sh
# Create new app
docker run -it --rm -v $(pwd):/app -v $(pwd)/.hex:/root/.hex josephyi/alpine-phoenix mix phoenix.new /app --app=your_app_name

# Running server
docker run -it --rm -v $(pwd):/app -v $(pwd)/.hex:/root/.hex josephyi/alpine-phoenix mix phoenix.server
````
