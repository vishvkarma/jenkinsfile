# jenkinsfile
Dxc credentials :- vishvkarma.ankur@yahoo.com ,   TCS User Name - ankurvis88@gmail.com Pass - Aws@12345
Adhar password :- Ankur@12345 User name :- 100099874878
 
Aws Credentials :- vishvkarma.ankur@yahoo.com
Password :- aws@12345
Aws -Waf
Aws -D Dos                                            </authorizationStrategy>
Aws Refrence Architectr

Git hub user name - vishvkarma
Email id - vishvkarma.ankur@yahoo.com
password - aws@12345#

Jenkins User Name - ankur
password - ankur12


interview questions for Aws:-

1. what are the hosted zoned in aws route 53.

Ans :- Hosted zones are the containers for holding the record informations for a specific domain.

2. How many typed of hosted zoned can create.

Ans:- Public and Private

Public :- internet facing  
Private :- for internally

3. when we setup hosted zones then we get 2 points.

1. Ns --> Dns Servers
2. SOA --> Authority

4. then create a record set.

Ans:- Record set is to map domain name with ip address.
Types of record set.
1. A- ipv4 (mapping domain name with ip address)
2. MX - use to point mail server
3. AAAA - (mapping domain name with ip address with ipv6)
4. CNAME - maping host name like:- one host name to another host name
5. Alias - any aws service genrate end points able to map it.
1. map domain name with load balancer


Route 53 Routing Policy:-

1. Simple Routing Policy :-  i. ideal for single resource application.               
                             11. No special routing configuration is required for simple routing policy.
                             111. its uses simple round robin policy technique
                             
2. Weighted Routing Policy:- i. Route traffic to different resources in specific prpperties.
                             ii. used when there are multiple resources.

3. Latency based routing (LBR) policy:- i. sends traffic to the server which has lowest network latecny
                                        ii. used when there are multiple resources performing same action
                                        
4. Geolocation Routing Policy :- i. Based on geolocation it redirect the traffic.
                                 ii. for same location two geolocation record can not be created
                                 
5. Failover routing policy :- i. Allows active-passive failover configuration.
                              ii. Resource takes all traffic when its healthy and available.
                              iii. Backup resource takes all traffic when the primary resource goes down.
                              iv. health chaeck agent continously monitors application locations sepratly to gurantee its available.
                              v. Only public hosted zones can have failover routing policy.


Ec2 Imp questions:

By default, when you create an EC2 account with Amazon, your account is limited to a maximum of 20 instances per EC2 region with two default High I/O Instances (hi1

Difference between s3 & ebs.

Amazon S3 can be accessed from anywhere. AWS EBS is only available in a particular region, while you can share files between regions on multiple EFS instances. EBS and EFS are both faster than Amazon S3, with high IOPS
 and lower latency. EBS is scalable up or down with a single API call

Ebs is a block level storage and S3 is object level storage.



Aws Cloud front:-

Cloud front is a content delivery contant . it can reduce the latency of static/dynamic website.

Types of cloud front:-

1. Web - > speed up distrubtion of static and dynamic content for example , html, css, php, and graphic files.

2. RTMP - > like media files , streaming , etc.

3. Edge locations - > aws servers

4. caches - > kind of middelaters 

5. invalideters - > if we want to change something in a file or update something use this option.

6. restrctions - > we can block countrie 



 Imp Question - difference between region and availability zone.

Answer -  Each Region is a separate geographic area. Availability Zones are multiple, isolated locations within each Region. Local Zones provide you the ability to place resources, such as compute and storage, in multiple locations closer to your end users



What is listeners :-

Answer :- A Listener is a process that checks for connection requests using the protocol and port that you configured.


Application Load balancer configuration :-

Answer :- 1 have to setup target group first to use application load balancer.
          2. Confogure Load Balancer
          3. Configure Security group
          4. Configure routing
          5. Register targets
          6. Can register the targets groups from targets groups

 Components of Application LB:-
1. Listeners
2. rules
3. Target Groups
4. Health Checks


Q. How many subnets can I create per VPC? Currently you can create 200 subnets per VPC. If you would like to create more, please submit a case at the support center.
Answer :-  200 subnets



Q. default How many instance can create in aws
Answer :-  20 instances



Q:- default How many buckets in s3 can create in aws
Answer :- By default, you can create up to 100 buckets in each of your AWS accounts.
if need more By default, you can create up to 100 buckets in each of your AWS accounts



Q:- Aws Ami (Amazon Machine Image):- Create a new machine by using Ami.

Answer :-     Imp things :- Device root volume for window instance /dev/sda1
              Root volume for linux /dev/xvda

after creating ami in other region will not take latest password will be using old password which was used in old machine.


Q:- how to connect linux machine:-
Answer :- ssh ec2-user@IP -i keypair



Q:- what is root device in aws.

Answer :- so by default Amazon EC2 instance, takes an EBS volume as a root device. A root device is a virtual device that holds the partition.


Q:- What is block device in AWS?
Answer :- Amazon EC2 to describe block devices. The block device mapping is used by Amazon EC2 to specify the block devices to attach to an EC2 instance.



Q:- what is the difference between root and block device in AWS?

Answer :- The Root device is the EBS volume for the AMI in which your instance is based on. 
additional Block device entries optionally to mount additional volumes on the instance, besides the root volume.


Q:- What is Reserve instance in Aws.

Answer :- 
A Reserved Instance is a reservation of resources and capacity, for either one or three years, for a particular Availability Zone within a region. 
Unlike on-demand, when you purchase a reservation, you commit to paying for all of the hours of the 1- or 3-year term; 
in exchange, the hourly rate is lowered significantly


Q:- What is spot instance in Aws.

Answer :- A Spot Instance is an unused EC2 instance that is available for less than the On-Demand price. 
Because Spot Instances enable you to request unused EC2 instances at steep discounts, you can lower your Amazon EC2 costs significantly. 
The hourly price for a Spot Instance is called a Spot price.



From Member ID PUPUN15629170000010520  , Establishment id PUPUN1562917000 





 to Member Id MRNOI00584000005840324, Establishment id MRNOI0058400000


UPBLY13346620001121336







i am using git just now this is the new way to learn things for our project



https://www.udemy.com/course/devops-ci-cd-with-jenkins-maven-git-and-pipeline/

