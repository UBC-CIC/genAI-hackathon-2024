# CIC genAI Hackathon 2024

## Introduction ☁️

**About Cloud Computing and Generative AI** <br>
Cloud Computing is the practice of using a network of remote servers hosted on the internet to store, manage, and process data, rather than a local server or a personal computer. It allows you to focus on developing, rather than having to worry about providing all the hardware. One of the biggest cloud service providers out there is AWS. <br>
Generative AI refers to a type of artificial intelligence designed to generate new content, data, or outputs that are not explicitly programmed in advance. It involves models that 
can create new examples or samples within a given domain, such as images, text, music, or other types of data.

## Event Overview 😄
### General Schedule

* 8:00AM: Check in + Breakfast
* 8:30AM: Introduction
* 8:40AM: Icebreaker
* 9:10AM: Hacking commences
* 12:00PM: Lunch (provided) 
* 5:00PM: Dinner (provided)
* 6:00PM: Hacking ends
* 6:10PM: Judging starts
* 7:45PM: Closing ceremony
* 8:00PM: End of Hackathon!

### Rules

* No plagiarism
* Code must be on GitHub and open sourced
* Any private datasets used must not contain personally identifiable information
* Project design and development must start at the hackathon’s beginning, but preprocessed and structured data is allowed

### Submission Guidelines

- Total 5 minutes (3 min presentation, 2 min Q&A)
- **REQUIRED**: To judge the technical details of your solution, you must nclude an architecture diagram (try out draw.io, or any other tool)
- We also recommend talking about your motivation for choosing this project, and its potential impact

### Criteria

- Creativity and Originality: How innovative and unique is the generated solution? 
- Technical Implementation: The complexity and effectiveness of the AI model and its integration with the user interface. 
- User Interaction: The intuitiveness and effectiveness of the user interface in influencing the generated solution. 
- Cloud deployment: The choices and efficient deployment of cloud services for their solution.  
- Presentation: The clarity, coherence, and persuasiveness of the final presentation.

  
### FAQs

For frequently asked questions and tips, please visit [FAQs](docs/FAQs.md)

---

## Getting Started 🎧

[Getting Started With AWS Workshop Studio](https://docs.google.com/document/d/1Xst57-bCp3enGVE6tNUdMyf_JzRMoJjjGsm8OS5sznE/edit#heading=h.l5zr9hk1rgza)

_The link to the AWS Workshop will be provided closer to the Hackathon_

## Resources ⭐️

### Gen AI Fundamentals

- [Introduction to Generative AI - Art of the Possible](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17176/introduction-to-generative-ai-art-of-the-possible)
- [Planning a Generative AI Project](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17256/planning-a-generative-ai-project)
- [Foundations of Prompt Engineering](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17763/foundations-of-prompt-engineering)
- [Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms)
- [Introduction to LangChain](https://python.langchain.com/docs/get_started/introduction) - LangChain is a framework for developing applications powered by language models
- [Serverless LLM apps with Amazon Bedrock](https://www.deeplearning.ai/short-courses/serverless-llm-apps-amazon-bedrock/) - (Course) Enroll for free. Learn how to deploy a large language model-based application into production using serverless technology.
- [Generative AI with Large Language Models](https://www.coursera.org/learn/generative-ai-with-llms) - (Course) Enroll for free. Excellent intro course. Gain foundational knowledge, practical skills, and a functional understanding of how generative AI works.
- [Prompt Engineering Best Practices](https://www.youtube.com/watch?v=jlqgGkh1wzY) - Prompt engineering best practices for LLMs on Amazon Bedrock.
- [General Prompt Engineering using Party Rock](https://partyrock.aws/u/js2222/zEj353AmT/Prompt-Engineering-Guide-Introduction) - Learn General Prompt Engineering using Party Rock (free to use).
- [Anthropic Claude on Party Rock](https://partyrock.aws/u/schuylr/proiDgYx9/Claude-Prompt-Engineering-Interactive-Tutorial-Chapter-1) - Learn Anthropic Claude Interactive Prompt Engineering tutorial on Party Rock (free to use).
- [Anthropic’s Official Documentation](https://docs.anthropic.com/claude/docs/guide-to-anthropics-prompt-engineering-resources) - Anthropic’s Official Prompting Documentation

---

### Data (extending the LLM)

#### Retrieval-augmented generation (RAG)

Retrieval-augmented generation (RAG) for large language models (LLMs) aims to improve prediction quality by using an external datastore at inference time to build a richer prompt that includes some combination of context, history, and recent/relevant knowledge

- [What Is Retrieval Augmented Generation (RAG)](https://aws.amazon.com/what-is/retrieval-augmented-generation/)

- More in-depth intro [Retrieval Augmented Generation (RAG) for LLMs](https://www.promptingguide.ai/research/rag)

#### Implementing RAG applications on AWS

##### RDS / pgVector:

- [Building AI-powered search in PostgreSQL using Amazon SageMaker and pgvector (Blog post)](https://aws.amazon.com/blogs/database/building-ai-powered-search-in-postgresql-using-amazon-sagemaker-and-pgvector/)
- AWS Samples (GitHub) - [RAG with Amazon Bedrock and PGVector on Amazon RDS](https://github.com/aws-samples/rag-with-amazon-bedrock-and-pgvector)

##### Knowledge Base:

- [Knowledge Bases now delivers fully managed RAG experience in Amazon Bedrock](https://aws.amazon.com/blogs/aws/knowledge-bases-now-delivers-fully-managed-rag-experience-in-amazon-bedrock/)
- [Knowledge Base for Amazon Bedrock](https://aws.amazon.com/bedrock/knowledge-bases/) - [Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/knowledge-base.html)

##### OpenSearch:

- [Amazon OpenSearch Service’s vector database capabilities explained](https://aws.amazon.com/blogs/big-data/amazon-opensearch-services-vector-database-capabilities-explained/)
- [Build scalable and serverless RAG workflows with a vector engine for Amazon OpenSearch Serverless and Amazon Bedrock Claude models (Blog post)](https://aws.amazon.com/blogs/big-data/build-scalable-and-serverless-rag-workflows-with-a-vector-engine-for-amazon-opensearch-serverless-and-amazon-bedrock-claude-models/)

---

### Agents for Bedrock

Enable generative AI applications to execute multistep tasks across company systems and data sources

- [User Guide](https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html)
- [Demo Video - Agents for Amazon Bedrock ](https://www.youtube.com/watch?v=UcehCSSOMQA)
- [Amazon Bedrock Agents Quickstart](https://github.com/build-on-aws/amazon-bedrock-agents-quickstart) - Functional code example
- [Build a foundation model (FM) powered customer service bot with agents for Amazon Bedrock](https://github.com/aws-samples/agentsforbedrock-retailagent)

### AWS Basics

- [AWS Cloud Essentials](https://aws.amazon.com/getting-started/cloud-essentials/)
- [AWS Security Essentials](https://assorted-market-2d4.notion.site/AWS-Security-Essentials-97e1020385564db4a59fe41cd0ce5929)
- [AWS Networking Essentials](https://assorted-market-2d4.notion.site/AWS-Networking-Essentials-cb0e377177eb4bfbbeebc58c8ca180cd)
- [AWS Technical Essentials](https://assorted-market-2d4.notion.site/AWS-Technical-Essentials-612efb1dde3c4ac1a8a68969b7fd8d5b)
- [Architecting on AWS - Online Course Supplement](https://explore.skillbuilder.aws/learn/course/external/view/elearning/8319/architecting-on-aws-online-course-supplement)


## Examples / Ideas 🤔

### Amazon Bedrock Series

- GitHub Link: [RAG-Bedrock-Titan](https://github.com/janakiramm/rag-bedrock-titan)
- Video: [Implementing RAG with Amazon Bedrock and Amazon Titan - Part 1](https://www.youtube.com/watch?v=RIw_Ivvrp8g)

From the creator: "In this tutorial, we will build a chatbot based on the Retrieval Augmented Context generation technique. Amazon OpenSearch Serverless is used as the vector database, Amazon Titan is used for generating text embeddings and as an LLM, and Amazon Bedrock API is used for invoking the Titan model."

### ICBC Chatbot

A chatbot that uses the ICBC website information as its knowledge base to answer questions that are asked by the users who want to learn more about driving licenses, insurance, and anything ICBC-related. This website can be hosted on an EC2 instance. This chatbot can be based on the [Flask Framework](https://flask.palletsprojects.com/), which provides a light-weight python-based web framework. 

### Course Textbook Chatbot

A chatbot generates responses to students’ prompts about content in a course textbook. This chatbot can be created using Amazon Bedrock to generate responses to prompts and Streamlit for the user interface. A Knowledge Base can also be used to implement Retrieval-Augmented Generation (RAG) to generate responses based on information retrieved from a specified data source, such as a course textbook PDF. 
