docker run --name nginx-odoo -p 80:80 -v $(pwd)/nginx.conf:/etc/nginx/conf.d/default.conf:ro -d nginx

in Windows

docker run --rm --name nginx-odoo -p 80:80 -v C:\Users\jamshidk\PycharmProjects\nginx-docker\nginx.conf:/etc/nginx/conf.d/default.conf:ro -d nginx

# with custom nginx with more
 docker run --name nginx-odoo -p 80:80 -v C:\Users\jamshidk\PycharmProjects\nginx-docker\nginx-tunnel-external-app.conf:/etc/nginx/conf.d/default.conf:ro -d jboesl/docker-nginx-headers-more
