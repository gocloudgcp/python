# python
ref. https://github.com/ACloudGuru-Resources/Course_GKE_Beginner_To_Pro

# notes
docker build -t myapp .<br />
docker images<br />
docker history myapp<br />
docker run -d -p 8888:8888 myapp<br />
docker ps<br />
curl http://localhost:8888<br />
docker logs vibrant_swirles<br />
docker exec -it vibrant_swirles /bin/bash<br />
docker stop vibrant_swirles<br />
docker start vibrant_swirles<br />
docker stop vibrant_swirles<br />
docker rm vibrant_swirles<br />
docker tag myapp gcr.io/playground-s-11-6a568b/myapp<br />
docker push  gcr.io/playground-s-11-6a568b/myapp<br />
