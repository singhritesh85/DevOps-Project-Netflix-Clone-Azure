# DevOps-Project-Netflix-Clone-Azure
![image](https://github.com/user-attachments/assets/e107ed31-d016-4965-bd10-6dad5cdbc6bb)

For Prometheus do the configuration in the file **/etc/prometheus/prometheus.yml** as shown below.
![image](https://github.com/user-attachments/assets/70af5539-64ed-4ca0-83e5-482f6f59c677)



```
The netflix-clone-auth secrets for kubernetes can be created using the command below

kubectl create secret netflix-clone-auth --docker-server=https://netflixcontainer24registry.azurecr.io --docker-username=netflixcontainer24registry --docker-password=XXXXXXXXXXXXXXXXXXXXXXXXXXXOJ7eXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXMtTc -n netflix
```
