# Privacy-Protective Synthetic Data Generation Algorithm [(Secludy PII-Free Synthetic Text Replicas)](https://aws.amazon.com/marketplace/pp/prodview-2nwsnaa5zuqce)

## Overview
This algorithm provides a secure and efficient solution for generating high-quality synthetic data while preserving the privacy of your original dataset. It's designed to help organizations create realistic synthetic datasets that maintain statistical properties and patterns of the source data while ensuring privacy compliance.

## Deployment 
the container will be delivered to your env w/o internet access. NO data sent out of your VPC. 
![image.png](asset/image.png)

## Key Features
- Privacy-preserving synthetic data generation
- Maintains statistical properties of original data
- Scalable processing with GPU acceleration
- Compatible with various data formats
- Easy integration with existing AWS workflows

## Prerequisites
- Active AWS account
- IAM role with appropriate SageMaker permissions
- Basic understanding of AWS SageMaker
- Python environment with required packages:
  - boto3
  - sagemaker

## Quick Start Guide

### 1. Set Up AWS Credentials
Ensure your AWS credentials are properly configured:

Configure through AWS CLI
```
aws configure
```
Or set environment variables
```
export AWS_ACCESS_KEY_ID='YOUR_ACCESS_KEY'
export AWS_SECRET_ACCESS_KEY='YOUR_SECRET_KEY'
export AWS_DEFAULT_REGION='YOUR_REGION'
```
### 2. follow example notebook and instructions inside

### 3. parameters to consider for your customized use case
1. input file uploaded to S3
2. output file on S3 folder
3. smaller epsilon, stricter privacy guranteee
   

## Best Practices
1. Start with a small dataset to test the workflow, i.e, example input file and defualt setting
2. Ensure input data is properly formatted
3. Monitor resource usage to optimize costs
4. Validate synthetic data quality before scaling up
5. Currently, the base model is by default as SMALL LLM
6. Please reach out to us if you have complex use cases
7. We are happy to deploy BIGGER and more POWERFUL LLM to meet your specific needs

## Support
- Technical Support: support@secludy.com


## Legal and Privacy Considerations
- Compliant with data privacy regulations, meeting GDPR, CCPA, HIPPA etc
- Synthetic data maintains statistical utility while protecting individual privacy

## License
This algorithm is available through AWS Marketplace. Usage is subject to AWS Marketplace terms and conditions.

---
