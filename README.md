# cloudresume_project


Project Overview 
This a developmental fun project for a fully automated deployment pipeline for your resume using Git Hub Actions , AWS S3 , CloudFront , IAM Roles. 

1.Created a GitHub Repository: You set up a private GitHub repository to keep your resume files secure.

2.Configured GitHub Actions: You added a GitHub Actions workflow to automate the deployment of your resume to an S3 bucket whenever changes are pushed to the main branch.

3.Set Up AWS Credentials: You securely managed AWS credentials using GitHub Secrets to ensure that your deployment process is both safe and automated.

4.Automated Deployment: Your workflow checks out the code, configures AWS credentials, and syncs your files to the S3 bucket.

Requirements and tools

Resources needed : GitHub , AWS S3 , IAM CREDENTIALS & policy , Cloud front distribution



Additional Enhancements to consider

Custom Domain: Consider setting up a custom domain with AWS Route 53 and configuring CloudFront for improved performance and security.
Continuous Integration: You can extend your GitHub Actions workflow to include testing or validation steps before deployment
