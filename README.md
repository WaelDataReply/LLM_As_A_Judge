# LLM_As_A_Judge
This repository contains the notebook to detect vulnerabilities of Claude-V2 on AWS Bedrock using GPT4 and Giskard open-source library.
Prerequisites:   
- An AWS Account  
- An access to Anthropic models on AWS Bedrock:
![alt text](https://github.com/WaelDataReply/LLM_As_A_Judge/blob/main/AccessGrantedClaude.png)  
- A notebook instance on SageMaker (used instance: ml.c5.4xlarge) with a Full Access Role to Bedrock:
```json   
{
	"Version": "2012-10-17",
	"Statement": [
		{
			"Sid": "FullAccessBedrock",
			"Effect": "Allow",
			"Action": "bedrock:*",
			"Resource": "*"
		}
	]
}
```
[Results]:  
![alt text](https://github.com/WaelDataReply/LLM_As_A_Judge/blob/main/%5BResults%5DClaudeVsGPT4_1.png)
![alt text](https://github.com/WaelDataReply/LLM_As_A_Judge/blob/main/%5BResults%5DClaudeVsGPT4_2.png)
