# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.

Comparing Virtual Machines to App Services 

App Services: 
Azure App Services are used by developers to host websites and does not require them to provision a web server. App Services are Platform as Service (PaaS) requiring developers to only worry about their application and Data. The disadvatage of App Services is the developer has no control of the infrastructure and can only work with what the vendor provides. The advantage of using App Services as opposed to Virtual Machines is workflow and less cost. App Services help the developer to only focus on building, testing, deploying, managing and updating Web Applications. 


Virtual Machines(VM):
VMs are Infrastructure as Service (IaaS) cloud platform which requires the developer to be responsible for Application, Data, Runtime, Middleware and Opearing System. Advantages of Virtual Machines are Scalability and Availabilty. Deploying to VMs is more costly compared to App Services. 

Considering the advantages and disadvantages of Virtual Machines and App Services in terms of Cost, scalabilty, and availabilty, I chose App Services for this project. I chose App Services over VM for this project because this project is more about developing an article web app which requires the developer to focus on the development of the app and not worry about the infrastructure. Secondly, it will be more costly to use a VM which we don't really need for this project than using an App Service which meets the requirement for this project. The article page web site a not critical so I don't have to worry about availabilty if I use App Services. If this is a very critical App that I cannot afford it going down, then I will have to worry about availabilty in case a datacenter goes down. In that case, I will consider using a VM instead of an App Service. Thirdly, interms of scalabilty, I don't have a need to increase resources to maintain good performance of the App. Incase the scenario is such that the performance of the App will be affected in the future due to limited resources, I will then choose VM over App services in other to be able to increase resources in terms of scalabilty.  
