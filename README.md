# DevOps-Project-Netflix-Clone-Azure
![image](https://github.com/user-attachments/assets/e107ed31-d016-4965-bd10-6dad5cdbc6bb)

Run below command to install node-exporter in kubernetes. 
```
kubectl create ns prometheus-node-exporter
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm install prometheus-node-exporter prometheus-community/prometheus-node-exporter --namespace prometheus-node-exporter --set service.type=LoadBalancer
```
![image](https://github.com/user-attachments/assets/77cf2a5f-66a7-45c3-a22e-1f526efe7ae4)

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

To see the Azure DevOps Pipeline Rate and Pipeline Duration, please follow the procedure as shown in the screenshots below.
![image](https://github.com/user-attachments/assets/2e4d986c-1667-44d4-86d4-e03321ef252c)
![image](https://github.com/user-attachments/assets/a5da4db5-f8cc-4895-a29e-a7a09116d0f6)
![image](https://github.com/user-attachments/assets/6be30f00-da66-4258-926e-40cec791b9c7)
![image](https://github.com/user-attachments/assets/c8df20f3-236c-47ba-b05f-025db803fb22)
![image](https://github.com/user-attachments/assets/2c5c7601-8d10-4cc8-ad65-278dcad7ddf8)
![image](https://github.com/user-attachments/assets/66d6fdef-262e-41b3-8028-9eb9c64efcba)

```
The netflix-clone-auth secrets for kubernetes can be created using the command below

kubectl create secret docker-registry netflix-clone-auth --docker-server=https://netflixcontainer24registry.azurecr.io --docker-username=netflixcontainer24registry --docker-password=XXXXXXXXXXXXXXXXXXXXXXXXXXXOJ7eXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXMtTc -n netflix
```

<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
For your reference the source code and helm chart is as given below.

source code:- https://github.com/singhritesh85/DevSecOps-Project.git

Helm Chart:-  https://github.com/singhritesh85/helm-repo-for-netflix-clone.git
```

<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://muditmathur121.medium.com/devsecops-netflix-clone-ci-cd-with-monitoring-email-990fbd115102
```
