 build Docker Image
docker build -t pdf-loader .

Run Container Again
docker run -d -p 8000:8000 pdf-loader

Check Running
docker ps

Check All Containers (Including Stopped)
docker ps -a