================ INTRO =========================
The project included are:
-   diagram: diagram image
-   template: cloudformation templates for deployment
-   script files


================ RUN ===========================
Create network-template: create.sh network-template template/network.yml  template/network-parameters.json
Create webapp-template: create.sh webapp-template template/udagram.yml  template/udagram-parameters.json

Update network-template: update.sh network-template template/network.yml  template/network-parameters.json
Update webapp-template: update.sh webapp-template template/udagram.yml  template/udagram-parameters.json

Delete network-template: delete.sh network-template
Delete webapp-template: delete.sh webapp-template


================ TEST ============================
Load Balancer URL: http://webapp-webap-7ohiqzyzzrve-1546386546.us-east-1.elb.amazonaws.com/