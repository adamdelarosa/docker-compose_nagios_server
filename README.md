# docker-compose_nagios_server

#to access the container please use :

$ docker exec -it container_id  /bin/bash

#to replace password :

$ htpasswd -c /usr/local/nagios/etc/htpasswd.users nagiosadmin
