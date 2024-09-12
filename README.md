# DevOps-Project-Netflix-Clone-Azure
![image](https://github.com/user-attachments/assets/e107ed31-d016-4965-bd10-6dad5cdbc6bb)

For Prometheus do the configuration in the file **/etc/prometheus/prometheus.yml** as shown below.
![image](https://github.com/user-attachments/assets/70af5539-64ed-4ca0-83e5-482f6f59c677)

The dashboard of prometheus can be seen as below.
![image](https://github.com/user-attachments/assets/9a1a864f-8e2f-4645-a9d2-c6e55285191e)
![image](https://github.com/user-attachments/assets/7a8f8cc3-8fbd-4ee9-b773-461d4f2eb98b)


```
The netflix-clone-auth secrets for kubernetes can be created using the command below

kubectl create secret netflix-clone-auth --docker-server=https://netflixcontainer24registry.azurecr.io --docker-username=netflixcontainer24registry --docker-password=XXXXXXXXXXXXXXXXXXXXXXXXXXXOJ7eXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXMtTc -n netflix
```
