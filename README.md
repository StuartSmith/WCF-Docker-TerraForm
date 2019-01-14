# WCF-Docker-TerraForm
In this example we will be creating a terraform script that installs a simple WCF Docker image

## Step 1: WCF Test Application 

The first thing we need to do is create a simple WCF Aplication that we can use for this example. We will not create this from scratch but go to code Microsoft.com and create the simple WCF calculator which can be found here https://docs.microsoft.com/en-us/dotnet/framework/wcf/samples/getting-started-sample. Then also add the addition function that retrieves the current machine the WCF application is running on. The reason why we require this is so we can be certain the load balancer is working. Evertime we call
