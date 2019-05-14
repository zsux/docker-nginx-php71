# res

- https://hub.docker.com/r/dockerphp/nginx/
- https://github.com/OsLab/docker-php-nginx


# install 

- python3
- php7
- nginx

### Build
    
    docker build -t pt_nginx_php_fpm_prod_1:latest . && docker images | grep pt_nginx_php_fpm_prod_1

    docker run -it eagle2019/nginx-php71 \
        bash -c "boot.py --init='ls -al' --boot='nginx,php-fpm,shell,sshd'"


	eagle2019/nginx-php71:[镜像版本号]

                
# tag
	
	git tag
	git tag -a version-1.1 -m 'my version 1.1' 
	git push origin version-1.1