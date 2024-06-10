### Create a ECR repository to store the Docker image of monolith threads api
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/bc9131e7-7624-4750-8ef6-3d43b2936ddc)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/db6624f9-dafb-4050-baaa-e86a37cad7df)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/6ef41466-9dd7-404e-8c35-781c3ede2a3b)

### Push the image to ECR repository
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/eba53589-bfe0-4331-a9eb-7dddcc95959a)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/f65d08b9-5579-46d0-8882-696aad32dab0)

### Now we will deploy the containerized monolith Threads api to Amazon ECS 
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/e5c91e95-acfa-41e2-a8fd-a52ed344fa4f)
The following diagram shows the deployment architecture of the containerized application
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/4b0cd3aa-d4a3-46ed-852f-bb1f5325c1ea)

### Creation of ECS Cluster 
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/6af55cc7-19ff-46d8-9846-f8a6b844c683)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/2449688d-2b29-434e-8ae3-e32f35b67679)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/7525bc4b-e724-4533-89da-b77d8a18c520)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/676db136-4fee-47f4-93e5-7b7ca92e368a)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/fa0762fe-22fa-486d-af36-369f9fd9fda0)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/fed62577-d790-4c56-a365-77ca1bc7726b)

### Create an ECS service
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/439ece9f-4f0e-40cf-a84f-0e85e4407a72)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/e8f82ad7-372a-43ff-8d5e-af9913ac97fb)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/ddf7a974-0628-44bd-9d2a-5d5393166fc6)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/012a44a8-12fc-47f8-b3a1-32408115bfe8)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/a23ab141-bb05-40fb-b563-6b6b2c449064)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/9a2bd5f0-16f1-47bc-b8b8-ad00c3c1ae65)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/1ef101f2-f33b-487b-9c21-dcf434f79187)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/994f476f-1750-4632-b83f-db164a92310b)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/f3bde2aa-3c5a-4263-9534-2627574462c5)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/1b2dbbab-e1c7-4ff7-b4ee-b0aa7a560120)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/0755e1fd-5bd9-475e-86f7-817679c82a0a)

## Now we will deploy the threads ai appliation that follows microservice architecture 
### Create an ECR repository for each microservice (users, threads, posts) 
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/4ca9e156-2512-4dd9-a79a-3a4dbab7b5c7)

### Build and Push the images of users, threads and post microservice to its repective ecr repository
#### users microservice
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/caef3f53-dc68-4ace-a7f8-eaf3eaa09a79)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/2c4c18d6-22b6-454e-963c-03fd11a18cfe)
#### threads microservice
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/8af0e51a-33f9-4fdc-bcba-b6ff4444b3f4)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/35c7f036-408a-4590-917f-eddd0cc29cc8)
#### posts microservice
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/faaecbd4-dc4f-4859-b7c7-eca49d5b7289)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/cbc9a4d4-d96f-4515-9345-cfe18a13e84c)

### Deploy the containerized microservices to the same ecs cluster 
### The following diagram shows the deployment architecture of the containerized microservices
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/cc532ab0-ec8b-4161-b42e-3827d6365baa)

### Creation of users microservice task definition
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/4c51e271-ee8d-4664-a9e5-05db66b5a695)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/34b8a4aa-a244-454b-8c25-f55d353ffd99)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/86f021a2-7d97-4a3a-b645-4df8b68a5966)

### Creation of posts microservice task definition
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/a225681d-df72-47e4-898a-4c0c35d72502)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/ce30a617-ed08-4db7-a2dc-af22885178c9)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/a34f1a85-d5d1-4d73-9a20-1eeba24f6e80)

### Creation of threads microservice task definition
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/e54a53d8-972d-40fe-83ee-e3c14ef8c346)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/13911623-cb5b-4c62-b574-4b6c207829bb)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/62440ac1-8524-4162-8983-d3f99f36995c)

![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/0494cf6d-d073-489f-b135-2c17fcedd773)

### Creating and deploying the services in ECS

#### Create service for users microservice
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/fe49af7f-da2c-40c3-ba55-ba6190529812)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/9ff132f7-51ae-42f6-a6bb-2cec1f1235e4)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/be0227d0-2ac1-476f-823d-d4acd9e34cc7)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/4e322b50-9fa5-4abc-a11d-303cf02126b1)

#### Create service for posts microservice
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/e681a4eb-f992-4a3a-a3b3-e300aab455b9)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/f8a6e534-434d-4ff0-8b50-19803ccb197d)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/7c4c42d9-683f-4e26-a5ae-12665cd773ed)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/93d4760f-0602-4251-8f55-5daf9f55b1e7)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/f6af8826-2e12-42bf-9e17-f41de5f5791e)

#### Create service for threads microservice
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/997f3fb4-d019-4f5a-8b5b-f68f3265f960)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/f068859a-d83d-4d43-a57d-c3bfbdf48e94)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/518ec4b7-ae1b-4861-beda-863eb8cf7287)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/9f4cd13b-2eff-4ee3-8a11-f7dd18affdb4)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/e4bd29bf-6b4a-4d51-a4dd-1e55823c45e4)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/6f7ac1c8-f8cf-42a6-9123-86fa9799315c)


![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/0800d405-bbd4-4279-a237-c33d552cd279)

![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/2269eb60-247e-493a-8835-9deda37a26e3)

![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/34fb99ff-9700-47bb-a662-fab0b2efe054)

![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/f5ce32fd-00e8-43c8-895a-ca002fb6821a)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/b748d81a-a54b-4a24-b5ed-7dd5b1c73ceb)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/155702bc-988e-48d2-adae-de72c13b9a64)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/fc468857-9dec-4563-a613-9ec4b0993a93)
![image](https://github.com/jayeshrajputtech/threads-api-ecs/assets/166933906/86eacc23-fe9d-488f-9454-b2b9546a2a79)





























































