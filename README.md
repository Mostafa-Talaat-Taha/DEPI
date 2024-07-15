2- Create a pod with the name redis and with the image redis 
![image](https://github.com/user-attachments/assets/73e265a1-69e3-4ab5-ab09-f631215faab4)

3- Create a pod with the name nginx and with the image “nginx123” Use a pod-definition YAML file. 
![image](https://github.com/user-attachments/assets/b9ceefc8-f1e9-4f88-8f6f-ec950affda1f)
![image](https://github.com/user-attachments/assets/8e9c20ee-8a91-49bc-8199-10b206129561)

5- Change the nginx pod image to “nginx” check the status again 
![image](https://github.com/user-attachments/assets/6b8bdaaa-cae7-4329-8daf-fe53de8aff74)
![image](https://github.com/user-attachments/assets/d19abf1e-554a-4e20-839f-dce8f58e0e59)

6- How many ReplicaSets exist on the system? 
![image](https://github.com/user-attachments/assets/7c3c049f-19af-4966-82ea-93ab6ee44d7f)

7- create a ReplicaSet with name= replica-set-1 image= busybox replicas= 3 
![image](https://github.com/user-attachments/assets/187f78d0-c761-4c48-b541-abb4dba30456)
![image](https://github.com/user-attachments/assets/fff0d36f-28a3-4ad0-9f97-5fd8b0395b74)

8- Scale the ReplicaSet replica-set-1 to 5 PODs. 
![image](https://github.com/user-attachments/assets/1b75acec-c11c-47ca-a74f-14988909ecd0)

10- Delete any one of the 5 PODs then check How many PODs exist now? Why are there still 5 PODs, even after you deleted one? 
![image](https://github.com/user-attachments/assets/9d065d5e-4658-4b39-948c-7a902911a0f6)

11- How many Deployments and ReplicaSets exist on the system? 
![image](https://github.com/user-attachments/assets/5b8aa0c4-d69b-4f26-aaf2-074c5d7ff8e1)

12- create a Deployment with name= deployment-1 image= busybox replicas= 3 
![image](https://github.com/user-attachments/assets/1cd44b66-43e9-4335-abd0-f2c4d3a1e3ed)

13- How many Deployments and ReplicaSets exist on the system now? 
![image](https://github.com/user-attachments/assets/6076cb9c-bdf3-48f3-a477-5c0e960c4b36)

14- How many pods are ready with the deployment-1? 
![image](https://github.com/user-attachments/assets/7bdef436-5f36-4c58-b4f2-5bc51fc3f783)

15- Update deployment-1 image to nginx then check the ready pods again 
![image](https://github.com/user-attachments/assets/5876ae34-8d9d-4982-bb68-eb06f1c86c2f)
![image](https://github.com/user-attachments/assets/188260b1-c667-4c50-b526-4855142a080e)
 
16- Run kubectl describe deployment deployment-1 and check events What is the deployment strategy used to upgrade the deployment-1? 
![image](https://github.com/user-attachments/assets/5528b60b-018a-4761-aad4-0d31b805999a)
 
17- Rollback the deployment-1 What is the used image with the deployment-1? 
![image](https://github.com/user-attachments/assets/984d0996-67b7-46a4-95c6-76e122764a02)

18- Create a deployment using nginx image with latest tag only and remember to mention tag i.e nginx:latest and name it as nginx-deployment. App labels should be app: nginx-app and type: front-end. The container should be named as nginx-container; also make sure replica counts are 3. 
![image](https://github.com/user-attachments/assets/f023e23d-c1cb-4019-ab10-45fd88b15347)
![image](https://github.com/user-attachments/assets/be38414f-c4a7-4d2e-9bbd-608e6f91ed3c)
