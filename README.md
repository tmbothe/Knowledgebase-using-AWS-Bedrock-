# Knowledgebase-using-AWS-Bedrock

![image](https://github.com/tmbothe/Knowledgebase-using-AWS-Bedrock-/blob/main/bedrock.jpg)

## Project Summary
In this project, we will leverage Amazon Bedrock to create an intelligent document querying system, showcasing the real-world applications of generative AI. We will combine this with other AWS services to build a GenAI RAG solution:

<b>AWS Bedrock </b> is our project's cornerstone, where we will implement and interact with large language models.
<b>Aurora Postgres Serverless</b>: A scalable, serverless database to efficiently store and manage your data.
<b>Amazon S3</b>: Object storage for housing your document corpus.

The challenge is to construct a system that can:

- Ingest and store documents
- Process and index this information for AI consumption
- Use Bedrock's language models to understand and respond to queries about the stored information
- Apply measures to secure the GenAI pipeline
