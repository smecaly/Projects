# HitatchProject.json is the CFT which can be reusable 
Hitachi-Para.json is the parameter file which will be used to create the resources for this specific case
Use the below command to all the cloud formation template and the parameter file from the CLI.aws cloudformation create-stack --stack-name Hpwordpres --template-body file://HitachProject.json --parameters file://Hitachi-Para.json
