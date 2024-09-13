# DevOps-Project-Netflix-Clone-Azure
![image](https://github.com/user-attachments/assets/e107ed31-d016-4965-bd10-6dad5cdbc6bb)

For Prometheus do the configuration in the file **/etc/prometheus/prometheus.yml** as shown below.
![image](https://github.com/user-attachments/assets/70af5539-64ed-4ca0-83e5-482f6f59c677)

The dashboard of prometheus can be seen as below.
![image](https://github.com/user-attachments/assets/9a1a864f-8e2f-4645-a9d2-c6e55285191e)
![image](https://github.com/user-attachments/assets/7a8f8cc3-8fbd-4ee9-b773-461d4f2eb98b)

For grafana the DataSource is Prometheus and to configure the same see the below screenshots.
![image](https://github.com/user-attachments/assets/3f18935b-4cd7-4bd2-9372-30f5b6015053)
![image](https://github.com/user-attachments/assets/b5d7b140-952c-4fff-8880-d004ac856647)
![image](https://github.com/user-attachments/assets/bbd94e12-d070-47b8-8b96-997a4a558447)

The source code was present in Azure Repo as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/4f414885-8f88-4fe9-b448-4075b5c2e740)

After running the Azure DevOps Pipeline the screenshot of SonarQube is as shown below.
![image](https://github.com/user-attachments/assets/29a29615-e73a-415c-9770-f62fb0d1ac01)
![image](https://github.com/user-attachments/assets/41ee2c38-ee5d-4ed7-9365-fffefc1f7c6b)

I have created service connection for Azure Container Registry as shown in the screenshot below.
![image](https://github.com/user-attachments/assets/ba756971-a242-43d4-9b48-2f369431de5b)

For Build notification the Email ID will be configured as shown in the screenshot below.
![image](https://github.com/user-attachments/assets/473bb0de-f760-462c-9f0c-907036f1e7ef)
![image](https://github.com/user-attachments/assets/3ce217da-4868-4796-8542-5ab7205b7a6f)
![image](https://github.com/user-attachments/assets/7d777843-6c52-4ed2-b603-fd204d97a0ee)

After completion of Azure DevOps Pipeline Job the email will be triggered to the Email Id as shown in the screenshot below.
![image](https://github.com/user-attachments/assets/64482dfb-0f36-4447-8ffe-92900ba0a796)

The TMDB API Key is taken as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/b297381b-31ea-4640-bb74-001a17199c17)

The entry for DNS Zone is shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/703f1c41-4392-4f48-9e9a-390435a84c73)

Finally you can access the application as shown below.
![image](https://github.com/user-attachments/assets/71877608-f647-4737-818c-2d05b8829319)


```
The netflix-clone-auth secrets for kubernetes can be created using the command below

kubectl create secret netflix-clone-auth --docker-server=https://netflixcontainer24registry.azurecr.io --docker-username=netflixcontainer24registry --docker-password=XXXXXXXXXXXXXXXXXXXXXXXXXXXOJ7eXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXMtTc -n netflix
```
