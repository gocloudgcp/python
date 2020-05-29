# python
ref. https://github.com/ACloudGuru-Resources/Course_GKE_Beginner_To_Pro

# notes
docker build -t myapp .
docker images
docker history myapp
docker run -d -p 8888:8888 myapp
docker ps
curl http://localhost:8888
docker logs vibrant_swirles
docker exec -it vibrant_swirles /bin/bash
docker stop vibrant_swirles
docker start vibrant_swirles
docker stop vibrant_swirles
docker rm vibrant_swirles
docker tag myapp gcr.io/playground-s-11-6a568b/myapp
docker push  gcr.io/playground-s-11-6a568b/myapp
