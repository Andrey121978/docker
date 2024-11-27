docker build -t my_nginx_image .
docker run -d -p 8080:80 my_nginx_image
