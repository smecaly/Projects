# HitatchProject.json is the CFT which can be reusable 
The CFT will create a VPC, Subnet, Internet gateway, route table, security group and 02 instances to for use. The master instance is the main instance which ansible will be configured on. The server instance is the host instance. 
Hitachi-Para.json is the parameter file which will be used to create the resources for this specific case. The parameter values can be changed to suit the specifications of any environment. 
Use the below command to all the cloud formation template and the parameter file from the CLI.aws cloudformation create-stack --stack-name Hpwordpres --template-body file://HitachProject.json --parameters file://Hitachi-Para.json
Run book contains the steps required to configure ansible. These commands can be included in a script and automated using systems manager. 
To install wordPress, 
