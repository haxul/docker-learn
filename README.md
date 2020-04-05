# docker-learn

# create image

docker build -t image_name from_catalog_path

#r un container

docker run --name container_name -d -p 8080:8080 image_name
-d in background
--rm remove container after it stops
-p ports our_machine:container
