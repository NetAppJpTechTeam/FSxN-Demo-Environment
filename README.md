# FSxN-Demo-Environment
Using CloudFormation to create Demo Environment of FSxN on the AWS
The main template is fsxn_demo_environment_initial.yaml.
# Architecture
The architecture is following：
![Architecture01](https://user-images.githubusercontent.com/104124762/204095898-9ffb664e-2380-46ac-a465-a14ed075d69e.png)
![Architecture02](https://user-images.githubusercontent.com/104124762/204095906-ccf145ea-97b3-4140-9ed9-6f63d2563b51.png)
## Notice
The windows instance and SVMAD are only automatically created when you choose "Create an AD for me" at the parameter setting page of CloudFormation stack.
