# deep-learning

##Start datalab docker 

```
sudo docker run -it -p "127.0.0.1:8081:8080" -v "${HOME}:/content" \
   -e "PROJECT_ID=q-project-x" \
  gcr.io/cloud-datalab/datalab:local

```
