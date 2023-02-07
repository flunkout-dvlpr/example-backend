# Moneta Onboarding Exercise

## AWS SAM Workflow - Serverless Application Model

### **Breakdown**

- **GitHub**
	- Hosts code repository and provides distributed version control
- **Code Pipeline**
	- **Code Commit** - pipeline trigger, when new commit is made repo changes are pulled    
	- **Code Build** - read/complile project code using `buildspec.yaml`
		- **Buildspec**
			- file that defines...
	- **Code Deploy** - convert/render `template.yaml` to CloudFormation json
		- **Template**
			- file that defines...


#### Lambdas
- 
#### API Gateway
- 

### **Excercise**
1. **Create CodePipeline**  
prerequesite: AWS account (free tier) and GitHub repository
	- Pipeline Name: projectName-backend -> `example-backend`
	- Service Role: Select *"New service role"*
	- Role Name: Auto generated
	- Check box: *"Allow AWS CodePipeline to create a service role so it can be used with this new pipeline"*
	- Source Provider: Select *"GitHub (Version 2)"*
	- Connection: Select connection, first time users click *"Connect to GitHub"*
		- Create a connectio (dialog)
			- Connection Name: `aws-codepipeline` or similar
			- Click *"Install a new app"*
			- Select GitHub profile
			- Click *"Authorize AWS Connector for GitHub"*
	- Repository Name: Select desired repo
	- Branch Name: Select master/main or development
	- Check box: *"Start the pipeline on source code change"*

		


### **Bonus**

#### Cognito
- 

