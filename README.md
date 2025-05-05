### Deploy Maven Application to AKS using Azure DevOps Pipelines ###

### After successful build using pipelines, it will generate Build Artifact ###

![image](https://github.com/user-attachments/assets/97c527d3-6db7-4dba-a3ee-47ca51535d4d)

### Below are the files and folders publiched to drop Artifact ###

![image](https://github.com/user-attachments/assets/60fafceb-0cd1-46df-8950-0603877d292d)


### Self hosted Agnet and configured Sonar Qube self hosted Agent itself
![image](https://github.com/user-attachments/assets/b83b3edb-af7d-4180-83d8-c7afaadd49d0)


### Sonar Qube Results
![image](https://github.com/user-attachments/assets/ba15d3d7-7b1e-4d35-9340-b16935457637)


### Go to Releases and configure deploy pipeline using classic pipelines.
### Choose your Artifact and click on Add stages.

![image](https://github.com/user-attachments/assets/f9379976-ddb5-4d67-b838-872d926173c6)

### Start configuring stage and choose Agent pool as self hosted Agent

![image](https://github.com/user-attachments/assets/08e04882-1993-4b02-be2e-8958ec109022)

### Install Latest Kubectl

![image](https://github.com/user-attachments/assets/9afb68e7-f170-4f60-87ad-0fa15a5f4650)

### Kubectl apply

![image](https://github.com/user-attachments/assets/c0fbb1bd-d2cc-4b67-aee7-cc75e62a25a0)

![image](https://github.com/user-attachments/assets/87c786e9-8633-4925-9fd7-d5a7f012716e)

![image](https://github.com/user-attachments/assets/6db1c51a-1514-44ff-81d0-09fa7e82db5f)

Below one is the Frontend IP created on Kubernetes Standard Load Balancer

![image](https://github.com/user-attachments/assets/773dde8a-f310-44d4-baba-c5ddd169df3e)


Result: Browse with Public IP of K8S Load Balancer Front end IP

![image](https://github.com/user-attachments/assets/e027ec89-af95-432d-b95b-d6b0822cc484)

