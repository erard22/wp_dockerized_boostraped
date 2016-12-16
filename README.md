# Example to develop a wordpress theme using docker and mariadb

As starting theme I added [Bootstrap basic4] (https://github.com/Rundiz/bootstrap-basic4) by [Rundiz] (https://github.com/Rundiz) to the ```theme``` folder.

Assuming you have docker installed and know the basics you just have to execute the following steps to start developing your theme: 

* Clone and star my repo :-)
* Navigate to the project directory - ```cd /to/the/project```
* Start the containers with docker-compose - ```docker-compose up```
* After a fiew seconds when ```mariadb``` has started and ```wordpress``` was able to connect you can start developing your theme.
* Open your browser and got to http://localhost:8080 and start the wordpress installation.
* Choose the theme in wordpress as usual.

Changes made in the theme files (php, css, js, ...) have immediately an effect and you see the changes in the browser.
