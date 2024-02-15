# Serverless LLM apps with Amazon Bedrock

## Learn how to deploy a large language model-based application into production using serverless technology.

Learn how to prompt and customize your LLM responses using Amazon Bedrock.
Summarize audio conversations by first transcribing an audio file and passing the transcription to an LLM.
Deploy an event-driven audio summarizer that runs as new audio files are uploaded; using a serverless architecture.

- *Time : 1 Hour*
- *Level : Intermediate*
- *Mike Chambers*

[Link for the Course](https://www.deeplearning.ai/short-courses/serverless-llm-apps-amazon-bedrock/)

**Lesson 1:**
 - Your first generation with Amazon Bedrock
   
**Lesson 2:**
- Import necessary Packages
- Setup S3 client and Transcribe Client
- Upload audio file to S3
- Create the unique job name
- Build the transcription response
- Access the needed parts of the transcript
- Setup Bedrock runtime
- Create the Prompt Template
- Configure the model response
- Generate a summary of the audio transcript.

**Lesson 3:**
- Enable Logging

**Lesson 4:**
- Deploy an AWS Lambda function
  - Setup -> Import packages and Helper Functions
  - Build the Prompt template
  - Create the Lambda function -> Lambda handler, Extract transcript from text and summarizaton using bedrock
  - Deploy the Lambda function
  - Perform some testing
