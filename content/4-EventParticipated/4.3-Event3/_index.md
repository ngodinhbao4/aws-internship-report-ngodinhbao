---
title: "Event3: FCAJ x Agentic AI Build Week"
date: 2026-07-25
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---

{{% notice info %}}
💡 **Overview:** The July 2026 FCAJ x Agentic AI Build Week hackathon—co-hosted with JI Fund—served as an intensive collaborative innovation hub. The event gathered builders, students, and mentors to transform ambitious AI ideas into production-ready cloud solutions. Sessions highlighted real-world AI agent implementations, end-to-end serverless architectures on AWS, multi-agent frameworks, and hands-on lessons in technical execution and product pitching.
{{% /notice %}}

# Event Report: “FCAJ x Agentic AI Build Week: Show Up. Build. Pitch. WIN!”

### Event Objectives

- **Embrace the Agentic Mental Model:** Encourage young technologists to challenge legacy release cadences (shifting from quarterly/bi-weekly deployments to continuous, agent-driven automation).
- **Hands-on Production Building:** Provide a 24-hour hackathon environment where participants roll up their sleeves, build real MVP/POC projects, and solve practical business problems.
- **Architectural Mastery on AWS:** Demonstrate how to build resilient, cost-effective, and low-latency multi-agent systems using Amazon Bedrock, Serverless services, and modern AI tools.
- **Cross-Disciplinary Collaboration:** Bridge technical engineering (Cloud, AI/ML, DevOps) with business strategy, product design, and pitching skills.

### Key Speakers & Guest Mentors

- **Mr. Joseph Marazzotta** - Head of Technology, Asia at AWS.
- **Mr. Nguyen Gia Hung** - Head of Solutions Architecture at AWS Vietnam.
- **One Team (1st Place AWS Track)** - Creators of the AI-Powered Conversational Ordering Agent.
- **Signal Scout / Dream AI (2nd Place AWS Track)** - Creators of the Multi-Agent Corporate Intelligence System.
- **Plan V Team** - Developers of the SA Professional AI-Native Architecture App.
- **3Ka / Shepherd Team** - Developers of the Real-Time Computer Vision & Crowd Flow Control Platform.
- **Six Pillars Team** - Developers of the Adaptive Workflow Engine for Anti-Money Laundering (AML).

---

### Session Highlights

#### 1. Keynote: Redefining Innovation in the Era of Agentic AI (Speaker: Joseph Marazzotta)
- **The Evolution of Mental Models:** Contrasted traditional IT mindsets (protecting mainframe stability with minimal changes) against today's AI-native paradigm, where AI agents execute continuous, automated releases.
- **Challenge the Status Quo:** Urged young developers not to be intimidated by veteran experience. Emerging builders possess a fresh mental model unburdened by 20-year-old technical debt, positioning them to lead industry transformation across retail, financial services, and robotics.
- **Human-in-the-Loop:** Highlighted Amazon's deployment of over 1 million fulfillment robots—emphasizing that hardware and AI models are useless without human engineers to direct, evaluate, and refine agent workflows.

#### 2. Conversational AI Ordering via Multi-Channel Agents (Speakers: One Team)
- **Solving the "App Switch" Friction:** Customers lose buying momentum when forced to download separate apps or create accounts just to place an order.
- **Overcoming AI Hallucinations:** Referenced past industry missteps (e.g., drive-thru AI mistakenly ordering hundreds of chicken nuggets) and implemented **Bedrock Guardrails** and verification steps before committing cart orders.
- **Technical Architecture & Cost Efficiency:** 
  - Integrated **Zalo** and **WhatsApp** via lightweight Channel Adapters to **Bedrock Agent Core** with persistent session memory.
  - Utilized **TinyFish** for dynamic web scraping of menu data without native APIs.
  - **Cost Performance:** Achieved an infrastructure cost of **$0.006 per order** (a 75% savings on Bedrock backend infrastructure, totaling ~$88/month for 500 orders/day) with a 3–5 second end-to-end latency.

#### 3. Multi-Agent Business Intelligence & Competitive Analysis (Speakers: Signal Scout)
- **Scattered Enterprise Signals:** Corporate strategists waste hundreds of hours manually gathering fragmented competitor updates across investor decks, financial reports, and public press releases.
- **Value Creation & Delivery Canvas:** Built a multi-agent system using **TinyFish** and **Apify** for web scraping (bypassing login walls for public data) and **LangFuse** for agent observability.
- **Serverless AWS Footprint:** Hosted UI on **AWS Amplify**, secured via **AWS WAF** and **Amazon Cognito**, storing verified enterprise intelligence in **Amazon S3** and **DynamoDB**.
- **Native AWS Cost Optimization:** Redesigned third-party dependencies into native AWS Browser/Web Tools to cut operational costs from $94/month down to ~$35/month while keeping data residency compliant.

#### 4. Automated Architecture Diagrams & IaC Generation (Speakers: Plan B)
- **The SA Bottleneck:** Solutions Architects often face emergency client requests requiring architecture diagrams, cost estimations, and Infrastructure-as-Code (IaC) templates delivered on extremely tight deadlines.
- **Natural Language to Infrastructure:** Developed an assistant that ingests natural language prompts or enterprise policy documents, parses business workflows, renders interactive **Draw.io** diagrams, calculates AWS pricing, and generates reusable **Terraform / CloudFormation** code.
- **Strict Typing & Output Control:** Applied custom validation scripts and internal service blacklists to prevent agents from introducing unauthorized AWS services or broken connections.

#### 5. Computer Vision & Financial Risk Management Systems (Speakers: 3K & Six Pillars)
- **3K (Shepherd - Crowd Control):** Ingests live video streams via **Amazon Kinesis Video Streams**, processes bounding boxes and tracking IDs using **YOLO v26 (Small)** + **ByteTrack** on **AWS Fargate**, and leverages an **Amazon Bedrock Agent** to autonomously direct field staff to congested airport/retail zones.
- **Six Pillars (AML Anti-Money Laundering):** Addressed the 90–95% False Positive alert rate in banking transactions ($158B in crypto fraud). Combined **Kinesis Data Streams**, **Amazon OpenSearch Vector Engine**, **Step Functions**, and dual **Bedrock Agents** to lower investigation times from 3 hours down to minutes while producing audit-ready evidence files.

---

### Key Takeaways

#### Business & Architectural Strategy
- **Solve Pain Points, Not Just Tech Flex:** A complex technical stack is worthless if it doesn't solve a clear, quantifiable customer problem. Judges and investors value a crisp value proposition (e.g., saving investigator review time or removing app-checkout friction) over overly dense code.
- **Scope Control for High-Pressure Delivery:** Successful hackathon and production projects define a strict Minimal Viable Product (MVP). Expanding scope mid-development leads to unstable code, missed deadlines, and failed live demos.

#### Engineering & Cloud Infrastructure
- **Agent Core & Session Memory:** Utilizing dedicated Agent Cores with built-in memory management enables AI systems to recall user preferences across multi-turn conversations without re-sending massive prompt contexts.
- **Observability and Guardrails:** AI agents operating in enterprise environments require strict output validation (**Bedrock Guardrails**, **LangFuse**) to mitigate hallucinations, enforce compliance, and maintain a strict human-in-the-loop fallback mechanism.

---

### Practical On-the-Job Applications

- **Deploying Micro-Adapters for Multi-Channel Ingestion:** Structure backend APIs using decoupled adapter patterns so new messaging platforms (Zalo, Telegram, Slack) or data scrapers can be added without rewriting core agent logic.
- **Optimizing AI Infrastructure Costs:** Regularly audit third-party agent tools against native AWS serverless offerings. Transitioning heavy API calls to event-driven architectures (Lambda, DynamoDB, Bedrock) drastically lowers per-transaction processing fees.
- **Automating Operations & System Diagnostics:** Implement agentic workflows for routine internal tasks—such as automated log ingestion, compliance verification, and infrastructure blueprint generation—freeing senior engineers for high-impact architecture.
- **Building a Culture of Rapid Prototyping:** Participate regularly in hackathons and build-weeks to refine crisis teamwork, practice high-stakes live pitching, and stay ahead of the rapidly changing GenAI landscape.

---

### Event Experience

#### High-Energy Hackathon Atmosphere
- The event captured the raw grit and excitement of tech innovation—featuring late-night code sprints, impromptu architecture debates on whiteboards, instant debugging sessions over coffee, and the shared thrill of delivering live product pitches.

#### Rigorous, Multidimensional Pitching
- Teams faced intense scrutiny from diverse panels of judges. Pitching went beyond technical architecture diagrams to cover business financial models, ROI forecasts, security compliance, and live software demonstrations.

#### Authentic Community Mentorship
- Mentors and AWS leaders actively engaged with teams throughout the event—offering real-time architecture feedback, helping resolve deployment errors, and guiding participants on how to turn hackathon POCs into real-world career opportunities.

#### Một số hình ảnh khi tham gia sự kiện
![FCAJ x Agentic AI Build Week](/images/4-Event/event3/event3-1.png)
![FCAJ x Agentic AI Build Week](/images/4-Event/event3/event3-2.png)

> **Summary:** The FCAJ x Agentic AI Build Week proved that the future of cloud engineering lies in combining strong foundational architectures with autonomous AI agents. By mastering AWS serverless infrastructure, controlling product scope, and focusing relentlessly on customer pain points, builders can transform radical ideas into winning enterprise solutions.
