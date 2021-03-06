#### This github repo is for sharing templates, scripts & tools, code samples, and playbooks for Service Fabric in China Azure, end users working on China Azure Service Fabric can refer to these materials in the planning, building, releasing and operating phases to ensure they are following the best practices in their projects.

Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and addresses the significant challenges in developing and managing cloud applications. By using Service Fabric, developers and administrators can avoid solving complex infrastructure problems and focus instead on implementing mission-critical, demanding workloads knowing that they are scalable, reliable, and manageable. Service Fabric will run on top of Virtual Machines (ARM based) and host customer application by distributed computing cluster, by that pattern, backend incident like VM outage and customer operation like application upgrade will ideally cause 0 data loss and not impact real time transaction at all.
See more reference at <a href="https://azure.microsoft.com/en-us/documentation/articles/service-fabric-overview/" target="_blank">global Azure Service Fabric</a> and <a href="https://azure.microsoft.com/en-us/documentation/articles/service-fabric-overview/" target="_blank">China Azure Service Fabric</a>

### How to choose from Service Fabric and other PaaS hosting like container service
Azure Service Fabric is more of App focus while Azure Container Service is more of infrastructure focus. 
- Azure Container Service allows to use the open source, industry famous container orchestrators like Docker Swarm and Kubernetes, that gives more openness and flexibility.
- Azure Service Fabric provides its own orchestration, that means Service Fabric provides more integrated, easier to use feature rich model.
- Azure Service Fabric offers several specific programming models, like reliable actor for IoT, reliable service for stateful app, and guest executables/containers for existing apps.
- Service Fabric applications can run on premise, on Azure or even in other cloud platforms.

<img src="http://jianwstorage.blob.core.chinacloudapi.cn/gitpics/sfvsothers.png"></img>

In brief, Service Fabric is a portable PaaS platform for running micro services including Docker container app, it provides managed orchestration mechanism to guarantee service availability, scalability and reliability, which release developers to focus only on business logistics in application modules. See more at <a href="https://github.com/Azure/azureservicefabricchina/tree/master/Playbooks">Playbooks</a> in this repo.


### Frequently used commands and templates for China Azure Service Fabric
- <a href="https://github.com/Azure/azureservicefabricchina/tree/master/ARM%20Templates">ARM templates for China Azure Service Fabric</a></br>
- <a href="https://github.com/Azure/azureservicefabricchina/tree/master/Scripts%20and%20Tools">Scripts and Tools for China Azure Service Fabric</a></br>
- <a href="">Samples for China Azure Service Fabric</a></br>


### Quick Start
- <a href="https://azure.microsoft.com/en-us/documentation/articles/service-fabric-get-started/" target="_blank">Setup local dev environment</a></br>
- <a href="https://azure.microsoft.com/en-us/documentation/articles/service-fabric-create-your-first-application-in-visual-studio/" target="_blank">Create first Service Fabric app</a></br>



### Get started with playbooks</br>
- <a href="https://github.com/Azure/azureservicefabricchina/tree/master/Playbooks">Playbooks for China Azure service fabric</a></br>
- <a href="https://github.com/Azure/azureservicefabricchina/tree/master/Decks">Decks for ramping up</a>


# Contributing
----------------------------------------------------------------------------------------------------------------------------------
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
