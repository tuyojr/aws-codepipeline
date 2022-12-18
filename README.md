#

![deployment_architecture](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/static_web_deployment_automation_architecture.png)

## Automate static website deployment to Amazon S3

All steps are provided by AWS Docs [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/automate-static-website-deployment-to-amazon-s3.html)

### Step 1

Create an Amazon S3 bucket and upload content

![create_bucket](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/create_bucket.png)

![upload_files](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/upload_files.png)

### Step 2

Configure the S3 bucket for website hosting

![enable_static_hosting](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/enable_static_hosting.png)

### Step 3

Create a bucket policy

![update_bucket_policy](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/update_bucket_policy.png)

### Step 4

Create a pipeline

![create_pipeline](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/create_pipeline.png)

![setup_github](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/setup_github.png)

![setup_github](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/setup_github_II.png)

![deploy](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/deploy_stage.png)

![skip](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/skip.png)

![set_s3](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/set_s3.png)

![pipeline](https://github.com/tuyojr/aws-codepipeline/blob/main/steps/pipeline.png)
