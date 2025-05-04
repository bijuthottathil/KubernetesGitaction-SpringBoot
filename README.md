# Running Kubernetes on Github Actions
![image](https://github.com/user-attachments/assets/d4034ab2-f10b-4345-9036-61741c49690b)

1. Here I am using Minikube to deploy Spring Boot Application

2. Minikube is running now ![image](https://github.com/user-attachments/assets/ffbfb95e-50e1-4db3-942e-dc2af42e1883)
3. To deploy containers in Minikube, we have to Configure Self Host runner in Github. I already configured it

4. ![image](https://github.com/user-attachments/assets/0ff43838-3afd-41cd-9e74-a96f916b639a)
5. ![image](https://github.com/user-attachments/assets/20a8d00a-98e4-44e6-b62c-aff84386580d) proper steps to setup self host runner are explained in github
6. In my repository I have a springboot java CRUD  application![image](https://github.com/user-attachments/assets/a1be6c73-33c5-4cac-b68a-9e94aec2f091)

7. This demo, I will be showing only to run all yaml files in the solution and deploy to minikube.
8. in workflows folder, I have created action file![image](https://github.com/user-attachments/assets/9fccc7e6-ca74-4b10-ad8f-9b69d180683f)
9. At present I set this workflow to execute manually ![image](https://github.com/user-attachments/assets/6d9ce62e-2227-4a23-8734-765455ab3781)
10. Before deployment, making sure that no deployments available in minikube![image](https://github.com/user-attachments/assets/434ecadf-a419-4d60-a2bf-52e72d2e571d)
11. No PODs are available![image](https://github.com/user-attachments/assets/4a5f8abe-cf8b-4a3c-a2ed-ed3c90cca5ac)
12. ![image](https://github.com/user-attachments/assets/57eb9a4d-18af-4739-bba4-5ac517d6d7be)
13. Now I will execute Action workflow file manually ![image](https://github.com/user-attachments/assets/829c7af2-b2b5-4eba-a1f2-121389496028)
14. ![image](https://github.com/user-attachments/assets/54982407-7498-4197-9c10-4e1e6d638d6e)
15. ![image](https://github.com/user-attachments/assets/929d71d8-5935-478c-a837-53d304709bab)
16. Job successfully completed ![image](https://github.com/user-attachments/assets/877b2972-4a95-4262-9961-8e11602d9dbd)

17. Now we will validate result in Minikube dashboard and terminals![image](https://github.com/user-attachments/assets/d3da3fe2-4ae8-4eb3-b665-d0dbe1e87b01)![image](https://github.com/user-attachments/assets/17f98806-3a32-4784-a08d-a08d28a4173c)
18. ![image](https://github.com/user-attachments/assets/017056e1-403c-4117-a94f-639cba2bb964)

19. So we could successfully deploy containers in Kubernetes

20. Note- You can see another repository in my git, showing the way I setup Springboot application and running it in MiniKube













 

