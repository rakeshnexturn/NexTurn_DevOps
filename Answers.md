# **Mid-Term Assessment Questions & Answers**
## _DevOps_
#### Q1. What is Devops?
    DevOps (Development and Operations) is a software development approach that emphasizes collaboration,communicationOperate,
    and integration between software developers and IT operations professionals.
    
#### Q2.What is Devops life cycle?
    The DevOps lifecycle refers to the stages involved in the development, deployment, and maintenance of software applications
    using a DevOps approach.The typical DevOps lifecycle includes the following stages:Plan,Develop,Test,Deploy,Operate,Monitor,Feedback .

## _Linux_

#### Q1.What do you mean by Linux ?
    Linux is a Unix-like, open source and community-developed operating system (OS) for computers, servers, mainframes, mobile devices and
    embedded devices. It is supported on almost every major computer platform, including x86, ARM and SPARC, making it one of the most widely
    supported operating systems .

#### Q2.Linux Basic 10 command ?
    - pwd Command : The pwd command is used to display the location of the current working directory.
    - mkdir Command : The mkdir command is used to create a new directory under any directory.
    - rmdir Command : The rmdir command is used to delete a directory.
    - ls Command : The ls command is used to display a list of content of a directory.
    - cd Command : The cd command is used to change the current directory.
    - touch Command : The touch command is used to create empty files. We can create multiple empty files by executing it once.
    - cat Command : The cat command is used to create a file, display content of the file, copy the content of one file to another file, and more.
    - cp Command : The cp command is used to copy a file or directory.
    - mv Command : The mv command is used to move a file or a directory form one location to another location.
    - rename Command : The rename command is used to rename files. It is useful for renaming a large group of files.
#### Q3.What is the command for CPU usage?
     mpstat Command command for CPU usage .
#### Q4.What is the command for Disk usage?
    In Linux, you can use the du (disk usage) command to check the disk usage .
#### Q5.What is file system in Linux ?
    A Linux file system is a structured collection of files on a disk drive or a partition. A partition is a segment of memory and
    contains some specific data .
#### Q6.how to see all the current processes?
    You need to use the ps command. It provides information about the currently running processes, including their process 
    identification numbers (PIDs).
#### Q7.What is the commands for listing files?
    Use the ls command to display the contents of a directory .
#### Q8.What is the use of chmod?
    The chmod (CHange MODe) command is used to change permissions for a file or directory on a Unix machine.
#### Q9.What is the Command for creating multiple directories?
    mdkir dir1 dir2
#### Q10.How to write scripting?
    Create a file using a vi editor(or any other editor). Name script file with extension .sh.
    Start the script with #! /bin/sh.Write some code.Save the script file as filename.sh.For executing the script type bash filename.sh.

#### Q11.What is Shell Scripting?
    A shell script is a text file that contains a sequence of commands for a UNIX-based operating system .
## _Git_
#### Q1.What is Git?
    Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating
    work among programmer collaboratively developing source code during software development .
#### Q2.Why we prefer git in it sector?
    It provides access to previous versions of the project. If there is any mistake, we can always roll back or undo the changes 
    without losing any work.GIT is a hero that helps us handle possible problems that may occur while working on a software project.
#### Q3.What is git rebase?
    Rebasing is the process of moving or combining a sequence of commits to a new base commit. Rebasing is most useful and easily
    visualized in the context of a feature branching workflow.
#### Q4.What is the command used to apply changes in git?
    The git add command adds a change in the working directory to the staging area. It tells Git that you want to include updates
    to a particular file in the next commit.
#### Q5.What is the difference between git fetch git pull git merge?
    git fetch updates your local repository with commits that have been added to the server since your last fetch, while git merge
    will try to combine two parallel development paths and git pull fetches from remote repositories .
#### Q6.Why Git branches?
    In Git, branches are a part of your everyday development process. Git branches are effectively a pointer to a snapshot of your changes.
    When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes .
#### Q7.How to copy the git branch to another branch?
    Use the git checkout command

#### Q8.How to clone a git repo and do some change and how to push that changed code to git hub?
    clone the git repo - git clone "Repo URL"
    add the files to that git repo - git add .
    commit the following changes - git commit -m First commit
    now push using git push - git push
#### Q9.What are 3 main components in GitHub ?
    - Workflows
    - Events
    - Jobs
#### Q10.What is the difference between CVCS and DVCS?
    CVCS is slower as every command need to communicate with server. DVCS is faster as mostly user deals with local copy without hitting server everytime.
    If CVCS Server is down, developers cannot work. If DVCS server is down, developer can work using their local copies.
#### Q11.What is git cherry-pick?
    git cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD.
    Cherry picking is the act of picking a commit from a branch and applying it to another.
## _Cloud Computing_
#### Q1.What do you mean by Cloud Computing ?
    Cloud computing is a virtualization-based technology that allows us to create, configure, and customize applications via an internet connection.
#### Q2.What is Iaas,Paas and Saas?
    -> Infrastructure-as-a-Service (IaaS): A set of raw IT resources offered to the user by the cloud service provider. They can be used to virtualise
    an infrastructure, or for resource-intensive projects.
    -> Platform-as-a-Service (PaaS): A platform that a provider offers to its customers via the internet. It enables teams — especially developers — to
    build applications and software on a solution without having to maintain it. Some applications support a wide variety of programming languages, which
    means they deliver more flexibility than an application hosted on a local infrastructure.
    -> Software-as-a-Service (SaaS): This is the most popular cloud service. It is software that runs on a provider’s infrastructure. The user pays for 
    the licence, but does not manage the data storage or physical hardware maintenance.

#### Q3.Example of Iaas,Paas and Saas ?
    -> Iaas : machine learning, big data, hosting, etc.
    -> Paas : AWS Elastic Beanstalk, Google App Engine, and Adobe Commerce, etc.
    -> Saas : Gmail, Slack, and Microsoft Office 365 etc.

## _AWS_
#### Q1.What do you mean by VPC ?
    A virtual private cloud (VPC) is a secure, isolated private cloud hosted within a public cloud. VPC customers can run code, store data, host websites,
    and do anything else they could do in an ordinary private cloud.

#### Q2.What do you mean by Subnet?
    A subnet is a range of IP addresses in your VPC. You launch AWS resources, such as Amazon EC2 instances, into your subnets.
#### Q3.What is loading balancing?
    Load balancing is the method of distributing network traffic equally across a pool of resources that support an application.
#### Q4.Describe s3 service in aws ?
    Amazon S3 is an object storage service that stores data as objects within buckets. An object is a file and any metadata that describes the file.
#### Q5.What is security group ?
    A security group controls the traffic that is allowed to reach and leave the resources that it is associated with. For example, after you associate
    a security group with an EC2 instance, it controls the inbound and outbound traffic for the instance.
#### Q6.What is EC2 ans VPC?
    Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) Cloud. Using Amazon EC2 eliminates
    your need to invest in hardware up front, so you can develop and deploy applications faster.
#### Q7.What is Lambda ?
    AWS Lambda is a compute service that lets you run code without provisioning or managing servers. Lambda runs your code on a high-availability 
    compute infrastructure and performs all of the administration of the compute resources, including server and operating system maintenance, capacity
    provisioning and automatic scaling, and logging.
#### Q8.What is RDS?
    Amazon Relational Database Service (Amazon RDS) is a web service that makes it easier to set up, operate, and scale a relational database in the
    AWS Cloud. It provides cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.
#### Q9.What is EBS?
    Amazon Elastic Block Store (Amazon EBS) is an easy-to-use, scalable, high-performance block-storage service designed for Amazon Elastic Compute Cloud
    (Amazon EC2).
#### Q10.How IAM is useful in AWS?
    AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage
    permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions)
    to use resources.
#### Q11.How to use load balancer?
    Before you begin
    Step 1: Select a load balancer type
    Step 2: Define your load balancer
    Step 3: Assign security groups to your load balancer in a VPC
    Step 4: Configure health checks for your EC2 instances
    Step 5: Register EC2 instances with your load balancer
    Step 6: Tag your load balancer (optional)
    Step 7: Create and verify your load balancer
    Step 8: Delete your load balancer (optional)
#### Q12.What do you mean by Cloud watch?
    CloudWatch enables you to monitor your complete stack (applications, infrastructure, network, and services) and use alarms, logs, and events data
    to take automated actions and reduce mean time to resolution. This frees up important resources and allows you to focus on building applications 
    and business value.
#### Q13.what is s3 bucket used for?
    Amazon S3 is used to store and retrieve any amount of data at any time, from anywhere. To get the most out of Amazon S3, you need to understand
    a few simple concepts. Amazon S3 stores data as objects within buckets. An object consists of a file and optionally any metadata that describes that file.
    
#### Q14.What is  S3 life cycle?
    An S3 Lifecycle configuration is an XML file that consists of a set of rules with predefined actions that you want Amazon S3 to perform on objects
    during their lifetime.

#### Q15.What is CDN?
    A CDN allows for the quick transfer of assets needed for loading Internet content, including HTML pages, JavaScript files, stylesheets, images, and videos.
#### Q16.What are the types of load balancer?
    There are three types of load balancers.They are
    - Application Load Balancers 
    - Network Load Balancers 
    - Classic Load Balancers.
#### Q17.What is S3 life cycle Policy?
    An S3 Lifecycle configuration is a set of rules that define actions that Amazon S3 applies to a group of objects. There are two types of actions:
    - Transition Actions
    - Expiration Actions
#### Q15.How to deploy web servers in Ec2?
    Steps to deploy webservers in Ec2:
     1. Choose AMI
     2. Choose Instance Type
     3. Configure Instance
     4. Add Storage
     5. Add Tags
     6. Configure Security Group
     7. Review
     8.SSH into the EC2 instance and Install a Web Server
#### Q16.What is cloudFront?
    Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, etc .
#### Q17.What is the difference between security group and nacl?
    NACL can be understood as the firewall or protection for the subnet. Security group can be understood as a firewall to protect EC2 instances.
#### Q18.What do you mean by autoscalaing ?
    Autoscaling is a cloud computing feature that enables organizations to scale cloud services such as server capacities or virtual machines up or 
    down automatically, based on defined situations such as traffic ir utilization levels.

#### Q19.what is trigger in lambda ?
    A trigger is a resource you configure to allow another AWS service to invoke your function when certain events or conditions occur. Your function can have
    multiple triggers.

#### Q20.What is  aws resources ?
    In AWS, a resource is an entity that you can work with. Examples include an Amazon EC2 instance, an AWS CloudFormation stack, or an Amazon S3 bucket.
    If you work with multiple resources, you might find it useful to manage them as a group rather than move from one AWS service to another for each task.
#### Q21.what is an availability zone ?
    Availability Zones are distinct locations within an AWS Region that are engineered to be isolated from failures in other Availability Zones. 

#### Q22.Why cant we use other DBs which can be installed in our instances?
    An instance can mount and open only a single database, ever. * A database may be mounted and opened by one or more instances (using RAC) .
    
#### Q23.Whats the advantage of using RDS  rather than other DBs?
    Amazon RDS makes it easy to use replication to enhance availability and reliability for production workloads. Using the Multi-AZ deployment option,
    you can run mission-critical workloads with high availability and built-in automated failover from your primary database to a synchronously replicated
    secondary database.
#### Q24.Difference between ipv4 and ipv6 ?
    IPv4 is a 32-Bit IP address, whereas IPv6 is a 128-Bit IP address. IPv4 is a numeric addressing method, whereas IPv6 is an alphanumeric addressing
    method.IPv4 binary bits are separated by a dot(.), whereas IPv6 binary bits are separated by a colon(:). IPv4 offers 12 header fields, whereas IPv6 offers 8
    header fields.
#### Q25.What are the type of instances?
    Instance types comprise varying combinations of CPU, memory, storage, and networking capacity and give you the flexibility to choose the appropriate
    mix of resources for your applications.
#### Q26.What is the difference between docker swarm and k8s ?
    The major difference between the platforms is based on complexity. Kubernetes is well suited for complex applications. On the other hand, Docker Swarm
    is designed for ease of use, making it a preferable choice for simple applications.

#### Q27.What is aws resources ?
    In AWS, a resource is an entity that you can work with. Examples include an Amazon EC2 instance, an AWS CloudFormation stack, or an Amazon S3 bucket.
    If you work with multiple resources, you might find it useful to manage them as a group rather than move from one AWS service to another for each task.

## _Maven_
#### 1.What is Maven?
    Maven is a popular open-source build tool developed by the Apache Group to build, publish, and deploy several projects at once for better project management.
    The tool provides allows developers to build and document the lifecycle framework.
#### 2.What is manven cycle and maven phases?
    The maven builds lifecycle is the tasks performed when the maven build commands are executed. The maven build lifecycle is divided into stages known as
    build phases. A build phase is made up of objectives. Maven goals are specific tasks that contribute to the creation and management of a project.

#### 3.Explain  maven deploy,install?
    Install the artifact in the local repository. (Not in the server) Deploy - Use it only if you publish your artifacts to remote repository so 
    it can be shared with others to download.
#### 4.What is  package management tool ?
    Package managers help developers install and track dependencies in a project and make it possible for members of a development team to ensure
    that everyone is using the same versions of dependencies.

## _Jenkins_ 
#### Q1.What do you mean by Jenkins?
    Jenkins is an open source continuous integration/continuous delivery and deployment (CI/CD) automation software DevOps tool written in the Java
    programming language. It is used to implement CI/CD workflows, called pipelines.
#### Q2.which java version does jenkins uses?
    Jenkins requires Java 11 or 17 .

#### Q3.What do you mean by CICD pipe line?
    A continuous integration and continuous deployment (CI/CD) pipeline is a series of steps that must be performed in order to deliver 
    a new version of software. 
#### Q4.what is jenkins used for?
    Jenkins is an open source continuous integration/continuous delivery and deployment (CI/CD) automation software DevOps tool written in the 
    Java programming language.
#### Q5.what do you mean by CI/CD ?
    A continuous integration and continuous deployment (CI/CD) pipeline is a series of steps that must be performed in order to deliver a 
    new version of software .
#### Q6.How to set user in jenkins?
    Step 1) Login to Jenkins Dashboard. Login to your Jenkins dashboard by visiting http://localhost:8080/ ...
    Step 2) Choose the option. You will now see options to create and add user in Jenkins and manage current users.
    Step 3) Create a new User .
    Step 4) User is created .

#### Q7.Where do we store our user name and password in Jenkins?
    From the Jenkins home page (i.e. the Dashboard of the Jenkins classic UI), click Manage Jenkins > Manage Credentials. Under Stores scoped 
    to Jenkins on the right, click on Jenkins. Under System, click the Global credentials (unrestricted) link to access this default domain.
    Click Add Credentials on the left.
    
## _Docker_
#### Q1.what is docker?
    Docker is a software platform that allows you to build, test, and deploy applications quickly.
#### Q2.what is dockerfile?
    A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image.
    This page describes the commands you can use in a Dockerfile .
#### Q3.what is docker-compose? 
    Docker Compose is a tool that was developed to help define and share multi-container applications.

#### Q4.what is docker network ?
    Docker networking allows you to attach a container to as many networks as you like. You can also attach an already running container.

#### Q5.how to create a container from docker images?
    The docker container create (or shorthand: docker create ) command creates a new container from the specified image, without starting it.
    When creating a container, the docker daemon creates a writeable container layer over the specified image and prepares it for running 
    the specified command.

#### Q6.What is container?
    A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application :
    code, runtime, system tools, system libraries and settings.

#### Q7.What are container logs?
    The docker logs command shows information logged by a running container. The docker service logs command shows information logged by all 
    containers participating in a service.
#### Q8.What is the use of docker swarm ?
    Docker Swarm is an orchestration management tool that runs on Docker applications. It helps end-users in creating and deploying a cluster
    of Docker nodes. Each node of a Docker Swarm is a Docker daemon, and all Docker daemons interact using the Docker API.
#### Q9.What do you mean by container and containerization?
    Containerization is a type of virtualization in which all the components of an application are bundled into a single container image and 
    can be run in isolated user space on the same shared operating system. Containers are lightweight, portable, and highly conducive to automation.
    
    
    
    
## _Ansible_
#### Q1.What is Ansible?
#### Q2.why ansible is being used?
#### Q3.How to write a playbook?
#### Q4.Explain ansible YAML file ?
#### Q5.What are variables in ansible?
#### Q6.Why Ansible?
#### Q7.What is ansible modules ?
#### Q8.What is ansible roles ?
#### Q9.what is your idea about ansible?
#### Q10.What is Ansible playbook?
#### Q11.Difference between Playbook and Ad hoc?
#### Q12.Write and show a playbook?
#### Q13.What is the location of ansible config file?
    
## _Kubernetes_
#### Q1.What is kubernetes?
#### Q2.What is Helm file?
#### Q3.What is cluster IP in kubernetes?
#### Q4.Why we use kubernates instead of docker swarm?
#### Q5.What is inside master node cluster in kubernetes ?
#### Q6.How are the Docker and Kubernetes related ?
    
## _Terraform_
#### Q1.what is terraform used for?
#### Q2.what is content of provider.tf and main.tf?
#### Q3.What is  Terraform lam?
#### Q4.What is state file in terraform?
#### Q5.What you did in terraform?
#### Q6.What is modules in terraform?
#### Q7.Explain Terraform commands?
#### Q8.What terraform init will do?
    
    
## _Scrum_
#### Q1.What do you mean by scrum?
#### Q2.what is scrum used for?
#### Q3.What is scrum master?
#### Q4.what are the operations/task a scrum master can do/does?
#### Q5.What is scrum? Explain in detail?
    
## _Jfrog_
#### Q1.What is an Artifactory?
#### Q1.What is jfrog artifactory used for?
    

    

