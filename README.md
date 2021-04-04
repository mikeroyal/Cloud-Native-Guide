
<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/90199045-6a7ba400-dd88-11ea-96d6-81b90d370946.png">
  <br />
 Cloud Native Guide
</h1>

#### A guide for understanding the Cloud Native Architecture, Cloud Native tools, and building Cloud Native applications.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

# Table of Contents

1. [Cloud Native Development](https://github.com/mikeroyal/Cloud-Native-Guide/blob/master/README.md#cloud-native-development)

2. [Cloud Native Learning Resources](https://github.com/mikeroyal/Cloud-Native-Guide/blob/master/README.md#cloud-native-learning-resources)


<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110991307-55202580-8329-11eb-9de4-31aba0a2daff.png">
  <br />
  Cloud Native Architecture
</p>


# Cloud Native Development

[Back to the Top](https://github.com/mikeroyal/Cloud-Native-Guide/blob/master/README.md#table-of-contents)

## DevOps

**Application Framework**

[Spring Boot](https://spring.io/projects/spring-boot) is an open-source micro framework maintained by Pivotal, which was acquired by VMware in 2019. It provides Java developers with a platform to get started with an auto configurable production-grade Spring application.

[Apache Mesos](http://mesos.apache.org/) is a cluster manager that provides efficient resource isolation and sharing across distributed applications, or frameworks. It can run Hadoop, Jenkins, Spark, Aurora, and other frameworks on a dynamically shared pool of nodes.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning and graph processing.

[Apache Hadoop](http://hadoop.apache.org/) is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures.

**Runtime Platform**

[BOSH](https://www.cloudfoundry.org/bosh/) is a tool that prepares your infrastructure for what needs to be managed. BOSH espouses software engineering best practices, such as continuous delivery, by making it easy to create software releases that automatically update complex distributed systems with simple commands.Due to the flexibility and power of BOSH, Google and VMware made it the heart of the Kubo project, now called the Cloud Foundry Container Runtime, based on Kubernetes.

**Infrastructure Automatation**

[Maven](https://maven.apache.org/) is a build automation tool used primarily for Java projects. Maven can also be used to build and manage projects written in C#, Ruby, Scala, and other languages. The Maven project is hosted by the Apache Software Foundation.

[Gradle](https://gradle.org/) is an open-source build-automation system that builds upon the concepts of Apache Ant and Apache Maven and introduces a Groovy-based domain-specific language instead of the XML form used by Apache Maven for declaring the project configuration.

[Chef](https://www.chef.io/) is an effortless Infrastructure Suite offers visibility into security and compliance status across all infrastructure and makes it easy to detect and correct issues long before they reach production.

[Puppet](https://puppet.com/) is an open source tool that makes continuous integration and delivery of your software on traditional or containerized infrastructure easy by pulling together all your existing tools and giving you flexibility to deploy your way. 

[Ansible](https://www.ansible.com/) is an open-source software provisioning, configuration management, and application-deployment tool. It runs on many Unix-like systems, and can configure both Unix-like systems as well as Microsoft Windows.

[Salt](https://www.saltstack.com/) is Python-based, open-source software for event-driven IT automation, remote task execution, and configuration management. Supporting the "Infrastructure as Code" approach to data center system and network deployment and management, configuration automation, SecOps orchestration, vulnerability remediation, and hybrid cloud control. 

[Terraform](https://www.terraform.io/) is an open-source infrastructure as code software tool created by HashiCorp.It enables users to define and provision a datacenter infrastructure using a high-level configuration language known as Hashicorp Configuration Language (HCL), or optionally JSON.

**Cloud Infrastructure**

[Amazon web service(AWS)](https://aws.amazon.com) is a platform that offers flexible, reliable, scalable, easy-to-use and cost-effective cloud computing solutions. The AWS platform is developed with a combination of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings.

[Microsoft Azure](https://azure.microsoft.com/en-us/) is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers.

[Azure DevOps](https://azure.microsoft.com/en-us/services/devops/?nav=min) is a set of services for teams to share code, track work, and ship software; CLIs Build, deploy, diagnose, and manage multi-platform, scalable apps and services; Azure Pipelines Continuously build, test, and deploy to any platform and cloud; Azure Lab Services Set up labs for classrooms, trials, development and testing, and other scenarios.

[Azure Draft](https://draft.sh/) is a tool for developers to create cloud-native applications on Kubernetes. 

[Google Cloud Platform](https://cloud.google.com/) integrates industry-leading tools(data management, hybrid & multi-cloud, and AI & ML) with Cloud Storage for enhanced support with everything from security and data transfer, to data backup and archive. Expand all . Backup, archival, and disaster recovery. Along with File systems and gateways.

[OpenStack](https://www.openstack.org/) is a free and open-source software platform for cloud computing, mostly deployed as infrastructure-as-a-service that controls large pools of compute, storage, and networking resources throughout a datacenter, managed through a dashboard or via the OpenStack API. OpenStack works with popular enterprise and open source technologies making it ideal for heterogeneous infrastructure.

[Cloud Foundry](https://www.cloudfoundry.org/) is an open source, multi cloud application platform as a service that makes it faster and easier to build, test, deploy and scale applications, providing a choice of clouds, developer frameworks, and application services. It is an open source project and is available through a variety of private cloud distributions and public cloud instances. 


## Continuous Integration/Continuous Delivery

[Bamboo](https://www.atlassian.com/software/bamboo) is a continuous integration (CI) server that can be used to automate the release management for a software application, creating a continuous delivery pipeline.

[Drone](https://drone.io/) is a Continuous Delivery system built on container technology. Drone uses a simple YAML configuration file, a superset of docker-compose, to define and execute Pipelines inside Docker containers.

[Travis CI](https://travis-ci.org/) is a hosted continuous integration service used to build and test software projects hosted at GitHub.

[Circle CI](https://circleci.com/) is a continuous integration and continuous delivery platform that helps software teams work smarter, faster.

[Team City](https://www.jetbrains.com/teamcity/) is a build management and continuous integration server from JetBrains.

[Shippable](https://www.shippable.com/) simplifies DevOps and makes it systematic with an Assembly Line platform that is heterogeneous, flexible, and provides complete visibility across your DevOps workflows. 

[Spinnaker](https://www.spinnaker.io/) is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.

[Prow](https://jenkins-x.io/docs/reference/components/prow/) is a Kubernetes based CI/CD system. Jobs can be triggered by various types of events and report their status to many different services. In addition to job execution, Prow provides GitHub automation in the form of policy enforcement, chat-ops via /foo style commands, and automatic PR merging. Prow has a microservice architecture implemented as a collection of container images that run as Kubernetes deployments.

## Microservices

[AWS ECS](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines.

[AWS CodeBuild](https://aws.amazon.com/codebuild/) is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers.

[CFEngine](https://cfengine.com/) is an open-source configuration management system, written by Mark Burgess.Its primary function is to provide automated configuration and maintenance of large-scale computer systems, including the unified management of servers, desktops, consumer and industrial devices, embedded networked devices, mobile smartphones, and tablet computers.

[Octpus Deploy](https://octopus.com/) is the deployment automation server for your entire team, designed to make it easy to orchestrate releases and deploy applications, whether on-premises or in the cloud.

[AWS CodeDeploy](https://aws.amazon.com/codedeploy/) is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.

[AWS Lambda](https://aws.amazon.com/lambda/) is an event-driven, serverless computing platform provided by Amazon as a part of the Amazon Web Services. It is a computing service that runs code in response to events and automatically manages the computing resources required by that code.

[Traefik](https://traefik.io/traefik/) is an open-source Edge Router that makes publishing your services a fun and easy experience. It receives requests on behalf of your system and finds out which components are responsible for handling them. What sets Traefik apart, besides its many features, is that it automatically discovers the right configuration for your services.

## Containers

[Kubernetes](https://kubernetes.io/) is an open-source container-orchestration system for automating application deployment, scaling, and management. It was originally designed by Google, and is now maintained by the Cloud Native Computing Foundation.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for deploying containerized applications.

[OpenShift](https://www.openshift.com/) is focused on security at every level of the container stack and throughout the application lifecycle. It includes long-term, enterprise support from one of the leading Kubernetes contributors and open source software companies.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[Docker](https://www.docker.com/) is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. All containers are run by a single operating-system kernel and are thus more lightweight than virtual machines.

[Rook](https://rook.io/) is an open source cloud-native storage orchestrator for Kubernetes that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[Rkt](https://coreos.com/rkt/) is a pod-native container engine for Linux. It is composable, secure, and built on standards. 

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io)is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521413-2ffc8c80-954e-11eb-9d19-b9c996bc524b.png">
  <br />
</p>

**Container Architecture. Source: [Containerd.io](https://containerd.io)**

## Cloud Native Learning Resources

[Back to the Top](https://github.com/mikeroyal/Cloud-Native-Guide/blob/master/README.md#table-of-contents)

[CNCF Cloud Native Interactive Landscape](https://landscape.cncf.io/)

[Build Cloud-Native applications in Microsoft Azure](https://azure.microsoft.com/en-us/overview/cloudnative/)

[Cloud-Native application development for Google Cloud](https://cloud.google.com/solutions/cloud-native-app-development?hl=he)

[Cloud-Native development for Amazon Web Services](https://aws.amazon.com/blogs/apn/journey-to-being-cloud-native-how-and-where-should-you-start/)

[Cloud Native Computing Foundation Training and Certification Program](https://www.cncf.io/certification/training/)

[Cloud Foundry Developer Training and Certification Program](https://www.cloudfoundry.org/get-started/)

[Cloud-Native Architecture Course on Pluralsight](https://www.pluralsight.com/courses/cloud-native-architecture-big-picture)

[AWS Fundamentals: Going Cloud-Native on Coursera](https://www.coursera.org/learn/aws-fundamentals-going-cloud-native)

[Developing Cloud-Native Apps w/ Microservices Architectures course on Udemy](https://www.udemy.com/course/developing-cloud-native-applications-microservices-architectures/)

[How load balancing works for cloud native applications with Azure Application Gateway on Linkedin Learning](https://www.linkedin.com/learning/azure-for-developers-optimize-with-azure-application-gateway/how-load-balancing-works-for-cloud-native-applications)

[Developing Cloud Native Applications course on edX](https://www.edx.org/course/developing-cloud-native-applications)

[Cloud Native courses from IBM](https://www.ibm.com/cloud/learn/cloud-native)


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Cloud-Native-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Cloud-Native-Guide/blob/master/README.md#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
