# Getting Set up for Labs

In this first lab we'll make sure that we're all set up with our AWS credentials and access to AWS, and then we'll
create a Cloud9 server/environment where we can run further labs.

1. Log in to AWS using the account ID, username, and password provided to you
1. In the top bar of the AWS Console, in the center, you'll see a search box; click on it, and type "Cloud9" which will filter available services in the search list. Click on "Cloud9" which will take you to where you can create your environment.
1. Click on "Create Environment"
1. Give your environment a unique name (your student alias is suggested) and, optionally, a description. Click "Next step".
1. Keep the settings at their defaults on this screen, then click "Next step"
1. Review your settings on the next screen, and then click "Create environment"
1. Wait for your environment to start. In this step, AWS is provisioning an EC2 instance on which your IDE environment will run. This gives us the distinct advantage of having a consistent and controlled environment for development regardless of client hardware and OS. It also allows us to connect to our instances and AWS's API without worrying about port availability in a corporate office. :-)
1. Once your IDE loads, you should see a Welcome document.
1. When executing the labs, you can run AWS CLI commands (where applicable) in the terminal provided in Cloud9.

Having done all that, we should be ready to move on!
