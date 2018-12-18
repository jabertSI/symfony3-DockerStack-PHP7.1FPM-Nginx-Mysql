<h1>Symfony3 Docker Stack - PHP-FPM7, Nginx and MySql</h1>
This stack create 4 containers :
<br>

    -PHP7.1 FPM
    -Nginx
    -Mysql
    -PhpMyadmin

You can change the host conf into Docker/nginx/symfony.conf

Put this repo into the racine of your symfony project
and run :
<br>
<code>
$ docker-compose up -d
</code>
<br>
<br>
<strong>
NOTE : 
</strong>
<br>
This stack create a network so 
the mySql server's ip is **'mysqldb'** <br>
You must change the '**database_host**' parameter of your **app**
