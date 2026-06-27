# Hi, I am Jagdish Salgotra

Principal Engineer with 15 years building distributed systems that serve at scale and fail honestly.

Currently building a serverless financial intelligence platform on AWS: real-time market data pipeline, LLM-generated watchlist
insights via Bedrock Claude, and DPDP-aligned consent management.

Stack: Java 25, Spring Boot, Lambda with SnapStart, Step Functions, Bedrock, DynamoDB, S3, CDK.

I write about what I build at engnotes.dev, covering production systems benchmarks, Java concurrency, and applied AI in production.

---

## What I work on

Distributed systems and event-driven architecture, designing for failure modes, not just happy paths.

Production AI: RAG evaluation, agentic systems, LLM ops. Benchmarks over claims.

Java and JVM: concurrent and parallel system design, thread lifecycle management, lock-free data structures, and the virtual thread model through Java 25. The kind of Java that shows up in production incidents, not just tutorials.

Serverless on AWS: Lambda SnapStart, Step Functions orchestration, Bedrock inference, CDK infrastructure as code.

Observability-first design: systems that tell you what is
wrong before users do.

---

## Open source

**[financial-intelligence-platform](https://github.com/salgotraja/financial-intelligence-platform)**
Production-grade serverless platform on AWS. Real-time market data ingestion via EventBridge and Step Functions, Bedrock Claude for LLM-generated insights, DynamoDB with TTL, S3 data
lake, API Gateway with Cognito and DPDP consent management. 

Java 25, Spring Boot, CDK.

**[production-systems-labs](https://github.com/salgotraja/production-systems-labs)**
Deterministic Java benchmarks for tail latency, queueing theory, hedged requests, coordinated omission, backpressure, and SLO
engineering. Reproducible outputs, checked-in golden CSVs.

**[agentic-ai-stress-suite](https://github.com/salgotraja/agentic-ai-stress-suite)**
Production AI benchmarks across RAG evaluation, single and multi-agent workflows, LLM ops, and security guardrails.
25,000 lines of annotated code with measured results.

---

## Latest writing

- [The Coordinated Omission Problem](https://engnotes.dev/blog/tail-latency-system-behavior/part-4-the-coordinated-omission-problem?utm_source=github&utm_medium=social&utm_campaign=part-4-the-coordinated-omission-problem&utm_content=profile)
  Jun 2026. Closed-loop vs open-loop benchmarking and why your load test lied about the pause.

- [Hedged Requests and Speculative Execution](https://engnotes.dev/blog/tail-latency-system-behavior/part-3-hedged-requests-and-speculative-execution?utm_source=github&utm_medium=social&utm_campaign=part-3-hedged-requests&utm_content=profile)
  Jun 2026. p95-based hedging that cuts p99 tail latency with less extra load than most teams expect.

Read more at [engnotes.dev](https://engnotes.dev)

---

## Connect

- LinkedIn: [linkedin.com/in/jagdishsal](https://www.linkedin.com/in/jagdishsal)
- Blog: [engnotes.dev](https://engnotes.dev)
- Email: jagdishsal@gmail.com

---

"The benchmark that hides the pause is more dangerous
than the pause itself."
