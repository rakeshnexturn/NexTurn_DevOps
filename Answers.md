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
#### 4.What is the command for Disk usage?
    In Linux, you can use the du (disk usage) command to check the disk usage .
#### 5.What is file system in Linux ?
    A Linux file system is a structured collection of files on a disk drive or a partition. A partition is a segment of memory and
    contains some specific data .
#### 6.how to see all the current processes?
    You need to use the ps command. It provides information about the currently running processes, including their process 
    identification numbers (PIDs).
#### 7.What is the commands for listing files?
    Use the ls command to display the contents of a directory .
#### 8.What is the use of chmod?
    The chmod (CHange MODe) command is used to change permissions for a file or directory on a Unix machine.
#### 9.What is the Command for creating multiple directories?
    mdkir dir1 dir2
#### 10.How to write scripting?
    Create a file using a vi editor(or any other editor). Name script file with extension .sh.
    Start the script with #! /bin/sh.Write some code.Save the script file as filename.sh.For executing the script type bash filename.sh.

#### 11.What is Shell Scripting?
    A shell script is a text file that contains a sequence of commands for a UNIX-based operating system .
## _Git_
#### 1.What is Git?
    Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating
    work among programmer collaboratively developing source code during software development .
#### 2.Why we prefer git in it sector?
    It provides access to previous versions of the project. If there is any mistake, we can always roll back or undo the changes 
    without losing any work.GIT is a hero that helps us handle possible problems that may occur while working on a software project.
#### 3.What is git rebase?
    Rebasing is the process of moving or combining a sequence of commits to a new base commit. Rebasing is most useful and easily
    visualized in the context of a feature branching workflow.
#### 4.What is the command used to apply changes in git?
    The git add command adds a change in the working directory to the staging area. It tells Git that you want to include updates
    to a particular file in the next commit.
#### 5.What is the difference between git fetch git pull git merge?
    git fetch updates your local repository with commits that have been added to the server since your last fetch, while git merge
    will try to combine two parallel development paths and git pull fetches from remote repositories .
#### 6.Why Git branches?
    In Git, branches are a part of your everyday development process. Git branches are effectively a pointer to a snapshot of your changes.
    When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes .
#### 7.How to copy the git branch to another branch?
    Use the git checkout command

#### 8.How to clone a git repo and do some change and how to push that changed code to git hub?
    clone the git repo - git clone "Repo URL"
    add the files to that git repo - git add .
    commit the following changes - git commit -m First commit
    now push using git push - git push
#### 9.What are 3 main components in GitHub ?
    - Workflows
    - Events
    - Jobs
#### 10.What is the difference between CVCS and DVCS?
    CVCS is slower as every command need to communicate with server. DVCS is faster as mostly user deals with local copy without hitting server everytime.
    If CVCS Server is down, developers cannot work. If DVCS server is down, developer can work using their local copies.
#### 11.What is git cherry-pick?
    git cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD.
    Cherry picking is the act of picking a commit from a branch and applying it to another.
## _Cloud Computing_
    1.What do you mean by Cloud Computing ?
    2.What is Iaas,Paas and Saas?
    3.Example of Iaas,Paas and Saas ?
## _AWS_
    1.What do you mean by VPC ?
    2.What do you mean by Subnet?
    3.What is loading balancing?
    4.Describe s3 service in aws ?
    5.What is security group ?
    6.What is EC2 ans VPC?
    7.What is Lambda ?
    8.What is RDS?
    9.What is EBS?
    10.How IAM is useful in AWS?
    11.How to use load balancer?
    12.What do you mean by Cloud watch?
    13.what is s3 bucket used for?
    14.What is  S3 life cycle?
    15.What is CDN?
    16.What are the types of load balancer?
    17.What is S3 life cycle Policy?
    15.How to deploy web servers in Ec2?
    16.What is cloudFront?
    17.What is the difference between security group and nacl?
    18.What do you mean by autoscalaing ?
    19.what is trigger in lambda ?
    20.What is  aws resources ?
    21.what is an availability zone ?
    22.Why cant we use other DBs which can be installed in our instances?
    23.Whats the advantage of using RDS  rather than other DBs?
    24.Difference between ipv4 and ipv6 ?
    25.What are the type of instances?
    26.What is the difference between docker swarm and k8s ?
    27.What is aws resources ?
## _Maven_
    1.What is Maven?
    2.What is manven cycle and maven phases?
    3.Explain  maven deploy,install?
    4.What is  package management tool ?

## _Jenkins_
    1.What do you mean by Jenkins?
    2.which java version does jenkins uses?
    3.What do you mean by CICD pipe line?
    4.what is jenkins used for?
    5.what do you mean by CI/CD ?
    6.How to set user in jenkins?
    7.Where do we store our user name and password in Jenkins?
    
## _Docker_
    1.what is docker?
    2.what is dockerfile?
    3.what is docker-compose?
    4.what is docker network ?
    5.how to create a container from docker images?
    6.What is container?
    7.What are container logs?
    8.What is the use of docker swarm ?
    9.What do you mean by container and containerization?
    
    
    
    
## _Ansible_
    1.What is Ansible?
    2.why ansible is being used?
    3.How to write a playbook?
    4.Explain ansible YAML file ?
    5.What are variables in ansible?
    6.Why Ansible?
    7.What is ansible modules ?
    8.What is ansible roles ?
    9.what is your idea about ansible?
    10.What is Ansible playbook?
    11.Difference between Playbook and Ad hoc?
    12.Write and show a playbook?
    13.What is the location of ansible config file?
    
## _Kubernetes_
    1.What is kubernetes?
    2.What is Helm file?
    3.What is cluster IP in kubernetes?
    4.Why we use kubernates instead of docker swarm?
    5.What is inside master node cluster in kubernetes ?
    6.How are the Docker and Kubernetes related ?
    
## _Terraform_
    1.what is terraform used for?
    2.what is content of provider.tf and main.tf?
    3.What is  Terraform lam?
    4.What is state file in terraform?
    5.What you did in terraform?
    6.What is modules in terraform?
    7.Explain Terraform commands?
    8.What terraform init will do?
    
    
## _Scrum_
    1.What do you mean by scrum?
    2.what is scrum used for?
    3.What is scrum master?
    4.what are the operations/task a scrum master can do/does?
    5.What is scrum? Explain in detail?
    
## _Jfrog_
    1.What is an Artifactory?
    1.What is jfrog artifactory used for?
    

    

