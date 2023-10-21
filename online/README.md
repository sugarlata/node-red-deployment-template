

Generate a certificate

```
sudo docker run -it --rm -p 80:80 --name certbot -v "/etc/letsencrypt:/etc/letsencrypt" -v "/var/lib/letsencrypt:/var/lib/letsencrypt" -v "/var/log/letsencrypt:/var/log/letsencrypt" certbot/certbot certonly -d XXX.sgarlata.com.au
```