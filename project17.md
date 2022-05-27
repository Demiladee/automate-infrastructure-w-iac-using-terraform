- created private and public subnets
- added the variables in the variables.tf file
- populated the information in tfvars file
- ran the terraform plan command to see what my output is

![](images/privatesubnets1.png)

![](images/subnetsvariablestypedesc2.png)

![](images/tfvarssubnets3.png)

![](images/fmtvalidateplan4.png)

![](images/fmtvalidateplan44.png)

![](images/fmtvalidateplan444.png)

- added tags to the subnets
- populated the variables in tfvars and variables.tf
- ran the plan command to see the output

![](images/tagsmain5.png)

![](images/tagvariables55.png)

![](images/tagstfvars555.png)

![](images/terraformplan6.png)

![](images/terraformplan66.png)

![](images/terraformplan666.png)

- created igw and nat-gateway resources
- added their tags
- populated the variables
- plotted a graph of the infrastructure
- ran the plan command 

![](images/natgweip7.png)

![](images/igw77.png)

![](images/variablestf777.png)

![](images/tfvars7777.png)

![](images/graphpreview7.png)

![](images/terraformplan77777.png)

![](images/terraformplann77777.png)

![](images/terraformplannn77777.png)

- created private and public rtbs
- ran the terraform plan and apply command
- confirmed my resources were created

![](images/rtb8.png)

![](images/rtb88.png)

![](images/terraformplan9.png)

![](images/terraformplan99.png)

![](images/terraformplan999.png)

![](images/terraformplan9999.png)

![](images/terraformplan999999.png)

![](images/terraformapply10.png)

![](images/terraformapply1010.png)

![](images/terraformapply101010.png)

![](images/terraformapplyvpc10.png)

![](images/terraformapplyeip10.png)

![](images/terraformapplyigw10.png)

![](images/terraformapplynatgw10.png)

![](images/terraformapplyrtb10.png)

![](images/terraformapplysubnets10.png)

- created route53 hosted zones
- requested a certificate from aws certificate manager
- created internet facing and internal load balancers
- created security groups
- created target groups
- populated the variables in the necessary files
- ran the plan and apply command

![](images/route53hostedzone11.png)

![](images/certtf11.png)

![](images/certtff11.png)

![](images/securitytf111.png)

![](images/albtf1111.png)

![](images/terraformplan11.png)

![](images/terraformplan111.png)

![](images/terraformapply11.png)

![](images/terraformapply111.png)

![](images/awscertificatemanager11.png)

![](images/loadbalancers11.png)

![](images/loadbalancersrules11.png)

![](images/securitygroups11.png)

![](images/targetgroup11.png)

- created nginx, webserver and bastion auto scaling group
- created their launch templates and target groups
- created bastion, wordpress, tooling, etc script files
- created roles for them
- populated the variables
- ran plan and apply command

![](images/asgnginxwebserver12bfeorevariables12.png)

![](images/asgwebserveraftervariablesnginx12.png)

![](images/rolestf12.png)

![](images/variabletfbeforeasgnginx121.png)

![](images/variabletfvarsbeforeasgnginx1212.png)

![](images/wordpressaftereverythingbutinapply12.png)

![](images/toolingaftereverythingbutinapply12.png)

![](images/nginxhaftereverythingbutinapply12.png)

![](images/outputstfafterwebserverstgt12.png)

![](images/bastionshaftereverythingbutinapply12.png)

![](images/terraformplan12.png)

![](images/terraformplan1212.png)

![](images/terraformapply12.png)

![](images/terraformapply1212.png)

![](images/autoscalinggroups12.png)

![](images/instances12.png)

![](images/launchtemplates12.png)

- created efs file
- created rds
- generated kms key
- created rds subnet group and efs mount point
- populated the variables
- ran the plan and apply command 

![](images/efstf13.png)

![](images/rdstf13.png)

![](images/variablestfiamaccountnumbermasterpassword13.png)

![](images/tfvarsaccountnumber13.png)

![](images/terraformplan13.png)

![](images/terraformplan131.png)

![](images/terraformapply13.png)

![](images/terraformapply131.png)

![](images/efs13.png)

![](images/efsaccesspoint13.png)

![](images/rdsdb13.png)

![](images/rdssubnetgroup13.png)