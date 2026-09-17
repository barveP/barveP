# Hi, I'm Poorva Barve

**Software Engineer · Backend Systems · AI Applications**

Seattle, WA · M.S. Computer Science, Northeastern University · GPA 4.0/4.0

[LinkedIn](https://www.linkedin.com/in/poorvabarve/) · [Email](mailto:poorvabarve@gmail.com) · [Resume](https://drive.google.com/file/d/1134dNIzFmiWhhZDI6hE1jORVi_ZNNYxH/view?usp=sharing)

I build backend services, distributed systems, and practical AI applications. My open-source work in **OpenHands, pytest, and Apache Ossie** focuses on protecting file integrity, preserving business calculations, and preventing incorrect test results.

**I'm looking for software engineering roles in backend development, distributed systems, and AI applications.**

## Open-source contributions

I investigate failures, report reproducible issues, and develop upstream patches. My recent pull requests focus on:

- **[OpenHands](https://github.com/OpenHands/software-agent-sdk) — AI coding-agent SDK.** Identified and reported file-integrity bugs; developed fixes to prevent silent content corruption and preserve symlinks during automated edits and undo. [PRs](https://github.com/OpenHands/software-agent-sdk/pulls?q=is%3Apr+author%3AbarveP) · [Issues](https://github.com/OpenHands/software-agent-sdk/issues?q=is%3Aissue+author%3AbarveP)
- **[pytest](https://github.com/pytest-dev/pytest) — widely used Python testing framework.** Developed a fix for a four-year-old isolation bug that caused false test results. Also discovered and reported cache I/O errors that failed otherwise passing tests, and patched them to produce warnings. [PRs](https://github.com/pytest-dev/pytest/pulls?q=is%3Apr+author%3AbarveP) · [Issue](https://github.com/pytest-dev/pytest/issues/15043)
- **[Apache Ossie](https://github.com/apache/ossie) — semantic interoperability at the Apache Software Foundation.** Identified and reported SQL conversion bugs that silently changed calculations or misclassified queries; developed fixes preserving business metrics and query definitions across dbt and Snowflake. [PRs](https://github.com/apache/ossie/pulls?q=is%3Apr+author%3AbarveP) · [Issues](https://github.com/apache/ossie/issues?q=is%3Aissue+author%3AbarveP)

## Selected projects

### [Snowbridge Async — Data Ingestion & Analytics](https://github.com/barveP/async-data-ingestion-platform)
**Python · asyncio · Snowflake · Airflow · MCP**

A reusable ingestion framework that safely resumes interrupted REST and database loads into Snowflake. Uses bounded concurrency, transactional checkpoints, and idempotent writes, with governed analytics exposed through MCP tools.

### [Chat with Data — Snowflake AI Agents in Slack](https://github.com/barveP/Snowflake-Cortex-Slack-Integration)
**Python · Snowflake Cortex · Slack Bolt · SQL**

Brings conversational data analysis into Slack: ask questions in plain English, follow up in the same thread, and receive answers with generated SQL and full results attached. Keeps conversation context so users can explore data without writing SQL.

### [NutriGraph — Meal Planning & Recipe Discovery](https://github.com/barveP/Recipe-Assistant-LangGraph-RAG)
**Python · LangGraph · Neo4j · Redis**

A meal-planning workflow that combines vector, keyword, and graph retrieval, adapts recipes to dietary constraints, and retries planning when nutrition or budget goals are missed. Supports a local recipe catalog so the core workflow can run without an external LLM or API.

### [StayFinder — Full-Stack Booking Platform](https://github.com/barveP/Airbnb-Replica)
**Node.js · Express · React · PostgreSQL · Redis · GraphQL**

A booking application with separate host and guest workflows, transaction-protected reservations, and cached property search shared across REST and GraphQL APIs. Coordinates concurrent booking requests to prevent overlapping reservations.

**More builds:** [AI Interview Coach](https://github.com/barveP/cf_ai_interview_prep_app) — streaming feedback, voice input, and session history on Cloudflare · [LinkedIn clone](https://github.com/barveP/Linkedin-clone)

## Experience

**Northeastern University — Teaching Assistant**  
May–August 2025 · Seattle, WA

- Cut manual code review time by 60% with an AI bot that detected MVC and SOLID violations in student pull requests.
- Built and deployed a hackathon management platform with Spring Boot, React, MongoDB, and AWS.
- Built reference systems supporting 500+ concurrent chat connections and an API load-tested at 5K requests/second; mentored 40+ students through hands-on AWS labs.

**Simplicity Creations — Software Engineer Intern**  
August–December 2023 · Pune, India

- Built an HR platform serving 50+ employees with Flask, React, and PostgreSQL, delivering 15+ REST APIs.
- Implemented approval and reporting workflows, with role-based access controls protecting payroll and personnel data across three user tiers.

## Tools I work with

| Area | Technologies |
| --- | --- |
| Languages | Python, Java, JavaScript, TypeScript, SQL, C/C++ |
| Backend & web | Spring Boot, Flask, Node.js, Express, React, REST, GraphQL, WebSockets |
| AI & data | LangGraph, RAG, Snowflake Cortex, MCP, Airflow, dbt, SQLGlot |
| Databases | PostgreSQL, MySQL, MongoDB, Redis, Snowflake, Neo4j |
| Cloud & engineering | AWS, Docker, Kubernetes, Git, CI/CD, pytest |

## Education & background

**M.S. in Computer Science — Northeastern University, May 2026**  
GPA: 4.0/4.0 · Focus: distributed systems, cloud computing, algorithms, databases, and practical AI.

I started my career in dentistry before moving into software engineering. That experience taught me to listen carefully, diagnose problems, and think about the person using what I build.

[Let's connect on LinkedIn](https://www.linkedin.com/in/poorvabarve/) · [Email me](mailto:poorvabarve@gmail.com) · [LeetCode](https://leetcode.com/u/Pbarve/)
