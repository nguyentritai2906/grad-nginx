# NGINX
Docker alpine image for Nginx (web|reverse proxy) server with some additional stuffs.
* **Configured HTTP/2 TLS**: improve performance and security.
* **PageSpeed**: optimizing the performance of websites.
* **ModSecurity**: web application firewall module.

## Deploy
Copy **env.template** file to **.env** file and edit base on your needs if you decide to run docker-compose.

## Customization
This image use templates folder for customization. You can find its structure in the default templates folder. These 
config templates are applied by default. <br><br>
Of course, you can customize them for your own needs or create different one and pass its 
path to NGINX_TEMPLATE_DIR variable.

## Maintainers
* [Hieu Pham](https://github.com/hieupth) (author)

## License
[MIT License](https://github.com/hieupth/nginx/blob/main/LICENSE) <br>
Copyright &copy; 2021 [Hieu Pham](https://github.com/hieupth). All rights reserved.