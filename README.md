# docker-learn

#create image
docker build -t image_name from_catalog_path

#run container

docker run --name container_name -d image_name
-d in background
--rm remove container after it stops
