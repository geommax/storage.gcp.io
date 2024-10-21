# storage.gcp.io
essential config &amp; proxy pass configuration with TailScale Node


### can be used as local web server to be exposed within specific sub domain. 




> $ sudo certbot --nginx -d storage.romdynamics.com

> $ nginx -t

> $ tailscale node on both NAS and GCP Instance

> $ grep -r "romrobots.com" /etc/nginx

> $ sudo certbot --nginx

> $ sudo ln -s /etc/nginx/sites-available/default /etc/nginx/sites-enabled/

### API Test
> curl -u username:password http://100.75.13.11:5000
