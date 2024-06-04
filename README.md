# cloudresume_project


Project Overview 
This a developmental fun project for a fully automated deployment pipeline for your resume using Git Hub Actions , AWS S3 , CloudFront , IAM Roles. 

1.Created a GitHub Repository: You set up a private GitHub repository to keep your resume files secure.

2.Configured GitHub Actions: You added a GitHub Actions workflow to automate the deployment of your resume to an S3 bucket whenever changes are pushed to the main branch.

3.Set Up AWS Credentials: You securely managed AWS credentials using GitHub Secrets to ensure that your deployment process is both safe and automated.

4.Automated Deployment: Your workflow checks out the code, configures AWS credentials, and syncs your files to the S3 bucket.

Requirements and tools

Resources needed : GitHub , AWS S3 , IAM CREDENTIALS & policy , Cloud front distribution

![image](https://github.com/Navilina/cloudresume/assets/136193317/05da5695-f9f4-439d-81d5-b901cd538a1b)


Additional Enhancements to consider

Custom Domain: Consider setting up a custom domain with AWS Route 53 and configuring CloudFront for improved performance and security.
Continuous Integration: You can extend your GitHub Actions or use AWS CodePipeline workflow to include testing or validation steps before deployment



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Cloud Resume

This is a static resume website hosted on AWS S3 and deployed via CloudFront. Changes to the resume are automatically deployed using GitHub Actions.

## Features

- Static website with resume
- Hosted on AWS S3
- Served via CloudFront for better performance and security
- CI/CD pipeline using GitHub Actions

## Setup Instructions

### Prerequisites

- Git
- AWS account

### Steps

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/cloudresume.git
    cd cloudresume
    ```

2. **Prepare resume files:**
    - Update `index.html`, `styles.css`, and `script.js` with your content.

3. **Set up AWS S3:**
    - Create an S3 bucket and enable static website hosting.

4. **Configure GitHub Actions:**
    - Add AWS credentials as secrets in the GitHub repository.

5. **Deploy:**
    - Push changes to GitHub to trigger the deployment.

## Usage

- View the resume at the CloudFront URL.
- Update `index.html` and push changes to GitHub to update the resume.

## Contributing

- Contributions are welcome. Please submit a pull request.

## License

- This project is licensed under the MIT License.

