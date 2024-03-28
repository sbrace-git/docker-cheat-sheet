## MySQL  
`docker run -itd --name mysql-test -p 3306:3306 -v /d/vm/docker/mysql/8/data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=xxxxxx -e TZ=Asia/Shanghai mysql`