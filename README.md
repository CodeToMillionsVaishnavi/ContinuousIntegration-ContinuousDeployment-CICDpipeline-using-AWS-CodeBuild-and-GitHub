# ContinuousIntegration-ContinuousDeployment-CICDpipeline-using-AWS-CodeBuild-and-GitHub
### Here’s a clearer version of the process:

## step 1) 
You have a GitHub repository that contains the source code for your static website. This repository is the input for AWS CodeBuild.

## step 2) 
When you make changes to your website’s source code and push these changes to your GitHub repository, AWS CodeBuild is triggered.

## step 3)
AWS CodeBuild then builds the project based on the build specifications defined in the " buildspec.yml" file in your repository. It generates artifacts as a result of this build process.

## * creating a EC2 instance :
![project1](https://github.com/CodeToMillionsVaishnavi/ContinuousIntegration-ContinuousDeployment-CICDpipeline-using-AWS-CodeBuild-and-GitHub/assets/151943307/b9415abd-3bf3-4a9d-92eb-2f2e23ed43d8)

## * build the project :
![project2](https://github.com/CodeToMillionsVaishnavi/ContinuousIntegration-ContinuousDeployment-CICDpipeline-using-AWS-CodeBuild-and-GitHub/assets/151943307/42cfe818-1d45-4462-a1fe-35a318cff945)

## * checking all phases are succeeded :
![project3](https://github.com/CodeToMillionsVaishnavi/ContinuousIntegration-ContinuousDeployment-CICDpipeline-using-AWS-CodeBuild-and-GitHub/assets/151943307/16183511-e783-46a4-8606-992fdd7743fc)
##  bucket name : " my-staticwebsite-bucket-demo " , copy the public hosting address :


These artifacts, which now contain the updated version of your static website, are then stored in an Amazon S3 bucket.


![image](https://github.com/CodeToMillionsVaishnavi/ContinuousIntegration-ContinuousDeployment-CICDpipeline-using-AWS-CodeBuild-and-GitHub/assets/151943307/5a24d9fc-e06c-4ef3-9797-4ae7810273a2)

![image](https://github.com/CodeToMillionsVaishnavi/ContinuousIntegration-ContinuousDeployment-CICDpipeline-using-AWS-CodeBuild-and-GitHub/assets/151943307/7af432dc-38d4-4c01-b6be-62edca512077)

 ## step 4) 
 As a result, any changes you make to your website’s source code in the GitHub repository will automatically get reflected in the final output stored in the S3 bucket.

![project4](https://github.com/CodeToMillionsVaishnavi/ContinuousIntegration-ContinuousDeployment-CICDpipeline-using-AWS-CodeBuild-and-GitHub/assets/151943307/729a15a3-35b0-4046-aecf-47bf1d25cb54)
