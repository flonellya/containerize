For the app server.py the containerized in python 3.9.0 the docker container, containerize_app_1 with Flask 1.1.1 and Gunicorn 19.9.0 install. The application is located in the /home/app/server directory. I spined up an Ubuntu server to run my text. The nginx container uses a docker volume, ssl_certificates, to store the ssl cert. All https requests are redirected to https and strict-transport security is enforced![image](https://user-images.githubusercontent.com/15150177/151907754-46c2adb8-a4a8-4818-b109-653990a882b3.png)