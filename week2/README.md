# Labs

## Steps to login to AWS Account provided by the instructor.

1. Click the [URL](https://dashboard.eventengine.run/login)
2. Enter the AWS provided hash code in the text box and click "Accept Terms and Login"
3. Select "Continue With Login with Amazon" in following screen 
    ![Amazon login](../images/aws-account-login/amazonretaillogin.png)
4. Enter your Amazon retail account credetials to login in the next screen
    ![Amazon login2](../images/aws-account-login/amazonretiallogin2.png)
5. Follow below screen instructions to get to AWS Console
    ![awscosnole](../images/aws-account-login/AWSConsole.png)
    
    ![awscosnole2](../images/aws-account-login/openawsconsole.png)
    
## Setting up the SageMaker Studio

1. Open pen SageMaker Service from AWS Console

2. Open SageMaker Studio

    ![Open Studio](../images/studio-instance/click-studio.png)
    
3. Choose create new role

    ![ima-role](../images/studio-instance/iam-role.png)
    
4. Choose default S3 permissions

    ![s3 perm](../images/studio-instance/s3-perm.png)
    
4. Once the Studio is ready click "Open Studio"

    ![open studio](../images/studio-instance/open-studio.png)
    
5. Open Terminal in Studio

    ![studio terminal](../images/studio-instance/studio-terminal.png)
    
6. Clone the git repository 

    git clone https://github.com/saidababu/ai-ml-bb
    
## Setting up the SageMaker Instance

1. Open pen SageMaker Service from AWS Console.

2. Select "Notebook Instances" on the left navigation and click "Create Notebook Instance".

    ![Open Studio](../images/studio-instance/1.nb1.png)
    
3. Select ml.m5.xlarge instance type, choose "Create a new Role" and then "Create notebook Instance"

    ![ima-role](../images/studio-instance/2.nb.png)
    
4. Choose default S3 permissions when this window pops up in the previous step.

    ![s3 perm](../images/studio-instance/s3-perm.png)
    
4. Once the Notebook Instance is ready click "Open JupyterLab"

    ![open studio](../images/studio-instance/3.nb.png)
    
5. Open Terminal in notebook instance

    ![studio terminal](../images/studio-instance/4.nb.png)
    
6. Clone the git repository 

    cd ~/SageMaker

    git clone https://github.com/saidababu/ai-ml-bb

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
