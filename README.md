### Landing-page-nginx

A dockerized nginx reverse proxy with persistent storage. 

Used as landing page for my apps on ```<mydomain.com>/```

Each app has its own path on the server eg. ```<mydomain.com>/flaskblog```.

Connects to other docker networks, like ```flask-blog_flask_network```.

Check ```docker-compose``` in [Flask-blog](https://github.com/orestispanago/Flask-Blog) project
