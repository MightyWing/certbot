1、docker run -it --rm --name certbot \
            -v "/root/openresty/certs/:/etc/letsencrypt" \
            -v "/root/openresty/libcerts/:/var/lib/letsencrypt" \
            certbot/certbot certonly  --manual