# s3bucket-cloudformation
Provision a s3 bucket resource using cloudformation and give user access to choose encryption type of SSE or KMS
#  Using pragmatic acccess to provision the resources**
aws cloudformation create-stack --stack-name myteststack --template-body file://S3Bucket.yaml --parameters ParameterKey=BucketName,ParameterValue="Your-Bucket-Name" ParameterKey=EncryptionType,ParameterValue=AES256 ParameterKey=BucketRegion,ParameterValue="Desired-Region"
# Cloud formation provision process of the stack and the s3 Bucket
![image](https://github.com/ufas-001/s3bucket-cloudformation/assets/58775887/cc400fac-e7e4-4a25-a23e-f7c0b69851d2)

# The created S3 Bucket
![image](https://github.com/ufas-001/s3bucket-cloudformation/assets/58775887/da6f7e74-2542-4a86-afe7-9b3c98ddebfb) 
