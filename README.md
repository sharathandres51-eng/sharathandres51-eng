<div align="center">

# Sharath Raveendran

**Technology delivery specialist**
Barcelona, Spain

<a href="https://www.linkedin.com/in/sharath-raveendran/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:sharathandres51@gmail.com"><img src="https://img.shields.io/badge/Email-C5221F?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
<img src="https://img.shields.io/badge/AWS%20Certified-Developer%20Associate-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS Certified Developer Associate">

</div>

<br>

> Four years embedded as the only external engineer inside a financial services client's teams, owning end to end delivery across multiple production systems on AWS. Now an MSc Business Analytics student at Esade, applying the same delivery approach to AI systems deployed for public sector customers.

Most of the work below comes down to the same problem: getting a system into someone's operations and making it trustworthy enough that they keep using it.

<br>

## Client engagements

<table>
<tr><td width="50%" valign="top">

### Benefits Eligibility Agent
**Generalitat de Catalunya** · via CTTI

Scans citizen profiles, identifies who qualifies for social benefits, and routes eligible cases to a caseworker for approval. Nothing sends automatically, because a human always decides.

Built neuro-symbolically on purpose: the LLM handles reasoning and language, a pure Python rule engine makes every eligibility decision. That keeps the legal criteria auditable under the EU AI Act.

`LangGraph` `Mistral` `LangSmith` `Python`

**[Repository →](https://github.com/sharathandres51-eng/eligibility-agent-ctti)**

</td><td width="50%" valign="top">

### Procurement Evaluation Workbench
**Generalitat de Catalunya** · via CTTI

AI assisted tender evaluation implementing the Spanish 3 envelope PCAP model. Evaluators keep all scoring authority; the system surfaces evidence from supplier proposals, applies the deterministic price formulae, and maintains a regulatory compliant audit trail.

Team project. See the repository for the team and my role.

`FastAPI` `LangGraph` `pgvector` `React` `TypeScript`

**[Repository →](https://github.com/sharathandres51-eng/procurement-agent-ctti)** · **[Live demo →](https://procurement-agent-ctti.vercel.app)**

</td></tr>
</table>

<br>

## Coursework and personal projects

<table>
<tr>
<th align="left" width="28%">Project</th>
<th align="left">What it does</th>
</tr>

<tr><td valign="top">

**[Forging Line Cycle Time](https://github.com/sharathandres51-eng/cloud-final-project-0.11.11)**

`XGBoost` `SageMaker` `Postgres` `Docker`

</td><td valign="top">

Predicts quench bath time on a steel forging line after the 2nd strike, 18s into a 58s process, so delays can be flagged while there is still time to act. Postgres and Flyway, medallion pipeline, SageMaker endpoint, ECS/Fargate.

**MAE 0.65s (±1.1%)**, tuned for multi second alerting rather than sub second precision.

</td></tr>

<tr><td valign="top">

**[Bank Marketing Propensity](https://github.com/sharathandres51-eng/bank-marketing-AI2)**

`XGBoost` `CatBoost` `scikit-learn`

</td><td valign="top">

Term deposit subscription prediction across 41k records with heavy class imbalance.

The interesting part is the cost sensitive threshold analysis: at €5 per call and €100 margin, **breakeven precision is 5%**, so the optimal threshold lands near 0.33 rather than the default 0.5.

</td></tr>

<tr><td valign="top">

**[Portfolio Risk Monitoring](https://github.com/sharathandres51-eng/portfolio-manager-group14-s3-lambda)**

`AWS Lambda` `DynamoDB` `SES` `S3`

</td><td valign="top">

Event driven daily risk pipeline on AWS. CloudWatch to Lambda to S3 to DynamoDB streams to SES, with deduplicated alerting when a client's portfolio drifts outside their agreed risk band.

Group project.

</td></tr>

<tr><td valign="top">

**[Tactical Breakdown Prototype](https://github.com/sharathandres51-eng/sharath-sofascore-prototype)**

`FAISS` `RAG` `GPT-4o-mini` `Streamlit`

</td><td valign="top">

Conversational football analyst over event level match data, grounded in a tactical knowledge base.

A cheap 5 token scope classifier runs first, so out of scope questions never trigger the expensive retrieval path.

</td></tr>
</table>

> These are Esade coursework, built on course provided scaffolding and against set rubrics. The repository structure, starter environment and some documentation came with the assignment. The analysis, models, services and deployments are mine.

<br>

## Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**Cloud and backend**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)

*Lambda · Aurora · S3 · DMS · EventBridge · SQS · SNS · CloudFormation · ECS · Fargate · SageMaker*

**AI and data**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square)
![Mistral](https://img.shields.io/badge/Mistral-FA520F?style=flat-square)
![OpenAI](https://img.shields.io/badge/GPT--4o--mini-412991?style=flat-square&logo=openai&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

*RAG · agentic workflows · LLM API integration · evaluation instrumentation*

**Ways of working**

*Agile (Scrum, Jira, Confluence) · Git · Liquibase · n8n · pytest · Boto3*

**Working familiarity**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

*Used on the procurement workbench front end alongside teammates; my own work there was backend and domain logic.*

<br>

## Also worth knowing

| | |
|---|---|
| **Certifications** | AWS Certified Developer Associate · AWS Certified Cloud Practitioner |
| **Spoken languages** | English (fluent) · Hindi (intermediate) · Spanish (learning, enrolled at Esade) |
| **Currently** | MSc Business Analytics at Esade, graduating October 2026 |
