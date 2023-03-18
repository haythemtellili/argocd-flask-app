# argocd-flask-app
## Commands:
```
docker build -t simple_flask:v1 .
docker run -p 5000:5000 simple_flask:v1
docker tag simple_flask:v1 haythemtellili/simple_flask:v1
docker push haythemtellili/simple_flask:v1
docker run haythemtellili/simple_flask:v1
```