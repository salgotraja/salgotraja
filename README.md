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

- [When 100% Agent Success Does Not Mean the Task Was Done](https://engnotes.dev/blog/agentic-ai-stress-suite/part-4-agent-success-flags-react-vs-plan-and-execute?utm_source=github&utm_medium=social&utm_campaign=part-4-agent-success-flags-react-vs-plan-and-execute&utm_content=profile)
  Oct 2026. Plan-and-Execute reported success on all 84 gpt-oss trials. Only 48 of its answers held up against the tool evidence.

- [Two RAG Evaluators, Two Very Different Scores](https://engnotes.dev/blog/agentic-ai-stress-suite/part-3-rag-evaluation-beyond-recall-at-5?utm_source=github&utm_medium=social&utm_campaign=part-3-rag-evaluation-beyond-recall-at-5&utm_content=profile)
  Oct 2026. RAGAS scores 30 naive RAG answers at 0.370 correctness. A gpt-4o-mini judge scores the same answers 0.887.

- [Dense vs Hybrid Retrieval: Measuring What Each Layer Adds](https://engnotes.dev/blog/agentic-ai-stress-suite/part-2-advanced-retrieval-hybrid-reranking-metadata?utm_source=github&utm_medium=social&utm_campaign=part-2-advanced-retrieval-hybrid-reranking-metadata&utm_content=profile)
  Sept 2026. Dense-only: 0.739 MRR on 30 queries. Hybrid BM25+RRF lifts it to 0.794. FlashRank adds 0.7 s and no ranking gain.

- [Do HyDE and Query Decomposition Improve RAG Retrieval?](https://engnotes.dev/blog/agentic-ai-stress-suite/part-1-state-aware-rag-beyond-top-k-retrieval?utm_source=github&utm_medium=social&utm_campaign=part-1-state-aware-rag-beyond-top-k-retrieval&utm_content=profile)
  Sept 2026. On 142 questions, HyDE's recall gain over dense retrieval remains uncertain. Decomposition lowers top-1 retrieval.

Read more at [engnotes.dev](https://engnotes.dev)

---

## Connect

- LinkedIn: [linkedin.com/in/jagdishsal](https://www.linkedin.com/in/jagdishsal)
- Blog: [engnotes.dev](https://engnotes.dev)
- Email: jagdishsal@gmail.com

---

"The benchmark that hides the pause is more dangerous
than the pause itself."
