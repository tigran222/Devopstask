1. Python  application that listens on port 8080 is app.py

2. Second is Dockerfile which makes app.py into docker image and uploads it to my dockerhub reposotory

3. Third my_app_chart directory is Helm chart which will download that image install it on k8s with helm


to tun them you have to run 

helm install *release ./my_app -f values.yaml

changing release number
