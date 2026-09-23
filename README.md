# Sharath Raveendran

**Technology delivery specialist.** Four years embedded as the only external engineer inside a financial services client's teams, owning end to end delivery across multiple production systems on AWS. Now an MSc Business Analytics student at Esade, applying the same delivery approach to AI systems deployed for public sector customers in Barcelona.

The work below is mostly about the same thing: getting a system into someone's operations and making it trustworthy enough that they keep using it.

---

## What I've been building

### Client engagements

**[Proactive Benefits Eligibility Agent](https://github.com/sharathandres51-eng/eligibility-agent-ctti)** · Generalitat de Catalunya (via CTTI)

An agent that scans citizen profiles, identifies who qualifies for social benefits, and routes eligible cases to a caseworker for approval. Nothing sends automatically, because a human always decides. Built neuro-symbolically on purpose: the LLM handles reasoning and language, a pure Python rule engine makes every eligibility decision, which keeps the legal criteria auditable under the EU AI Act. LangGraph, Mistral, LangSmith evaluation instrumentation.

**[Procurement Evaluation Workbench](https://github.com/sharathandres51-eng/procurement-agent-ctti)** · Generalitat de Catalunya (via CTTI) · [live demo](https://procurement-agent-ctti.vercel.app)

AI assisted tender evaluation implementing the Spanish 3 envelope PCAP model. Evaluators keep all scoring authority; the system surfaces evidence from supplier proposals, applies the deterministic price formulae, and maintains a regulatory compliant audit trail. Team project, see the repo for the team and my role.

### Coursework and personal projects

| Project | What it does |
| --- | --- |
| ⚙️ **[Forging Line Cycle Time](https://github.com/sharathandres51-eng/cloud-final-project-0.11.11)** | Predicts quench bath time on a steel forging line after the 2nd strike, 18s into a 58s process, so delays can be flagged while there is still time to act. Postgres and Flyway, medallion pipeline, XGBoost, SageMaker endpoint, ECS/Fargate. MAE 0.65s (±1.1%), tuned for multi second alerting rather than sub second precision. |
| ⚙️ **[Bank Marketing Propensity](https://github.com/sharathandres51-eng/bank-marketing-AI2)** | Term deposit subscription prediction on 41k records. The interesting part is the cost sensitive threshold analysis: at €5 per call and €100 margin, breakeven precision is 5%, so the optimal threshold lands near 0.33 rather than the default 0.5. |
| ⚙️ **[Portfolio Risk Monitoring](https://github.com/sharathandres51-eng/portfolio-manager-group14-s3-lambda)** | Event driven daily risk pipeline on AWS. CloudWatch to Lambda to S3 to DynamoDB streams to SES, with deduplicated alerting when a client's portfolio drifts outside their risk band. Group project. |
| ⚙️ **[Tactical Breakdown Prototype](https://github.com/sharathandres51-eng/sharath-sofascore-prototype)** | Conversational football analyst over event level match data. A cheap 5 token scope classifier runs first so out of scope questions never trigger the expensive retrieval path. FAISS, RAG over a tactical knowledge base. |

⚙️ marks Esade coursework. These were built on course provided scaffolding and against set rubrics, so the repository structure, starter environment and some documentation came with the assignment. The analysis, models, services and deployments are mine.

---

## Tools I'd defend in an interview

**Languages** Python, Java, SQL, R
**Cloud and backend** AWS (Lambda, Aurora, S3, DMS, EventBridge, SQS, SNS, CloudFormation, Fargate, ECS, SageMaker), Docker
**AI** LangGraph, LangSmith, RAG, agentic workflows, LLM API integration (GPT-4o-mini, Mistral)
**Frameworks** FastAPI, Flask, SpringBoot, pandas, scikit-learn, pytest, Boto3
**Ways of working** Agile (Scrum, Jira), Git, Liquibase, n8n

**Certified** AWS Developer Associate · AWS Cloud Practitioner

**Languages spoken** English (fluent), Hindi (intermediate), Spanish (learning, enrolled in courses at Esade)

---

## Get in touch

[LinkedIn](https://www.linkedin.com/in/sharath-raveendran/) · [Email](mailto:sharathandres51@gmail.com) · Barcelona, Spain
