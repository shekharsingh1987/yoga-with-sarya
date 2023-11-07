# yogawithsaroj
This is a cms system which will host a website with blogs. The idea is that we make an database as api service, which can be later made as another component.
This service must be deployable in
* AWS (Lambda, Api Gateway, DB or Any RDS)
* Azure (Azure Function, ApiGateway, Any DB)
* Docker Compose
* Kubernetes Or K8 

# Api and Admin
This would be the first component which should be up and running. Admin site would help user to define
* Entity and their schema with data type
* roles and permission for an api endpoint

Assumption would be that credential provided at the time of deployment of Api,have enough permissions to create entity. The type of database that it can support.
* dynamodb

# UI Or Blog Site
This is going to be the public site in form of website or blogs. this UI can be customized and can be different and as per the choice of user.