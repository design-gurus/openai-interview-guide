# The OpenAI system design interview

OpenAI asks system design, and depending on the role it asks twice: once as an early screen and again, in more depth, inside the final loop. The questions mix classic infrastructure with product design. For product questions, interviewers are commonly reported to expect a screen sketch, an API contract, and a storage schema, not only a backend diagram.

An API (application programming interface) contract is the list of requests a service accepts, with the shape of each request and response.

## Format

| Round | Length | What it tests |
|---|---|---|
| Early design screen (some roles) | 45 to 60 minutes | Requirements, scope, and the structure of the problem |
| Final loop design | About 60 minutes | Depth, failure handling, and trade-offs under follow-up questions |

## Commonly reported questions

| Question | Follow-up areas reported | Related lesson |
|---|---|---|
| Design the OpenAI Playground | Screen layout, API layer, schema for thread and message history | [Design a ChatGPT-Style Assistant](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/design-a-chatgptstyle-assistant?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview) |
| Design enterprise search built on a large language model | Ingestion, indexing that respects permissions, retrieval, where the model sits | [Capstone: Enterprise Document Q&A](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/capstone-enterprise-document-qa?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview) |
| Design a notification system | Fan-out, delivery guarantees, user preferences | [Designing a Notification System](https://www.designgurus.io/course-play/grokking-system-design-interview-ii/doc/designing-a-notification-system?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview) |
| Design Slack-style messaging | Real-time delivery, channels, presence, 100 times the traffic | [Designing Facebook Messenger](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-facebook-messenger?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview) |
| Design a distributed job scheduler | At-least-once and exactly-once execution, fault tolerance, priority | [Worked Design: Consolidating Three Job Schedulers](https://www.designgurus.io/course-play/grokking-staff-engineer-interview/doc/worked-design-consolidating-three-job-schedulers?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview) |
| Design a payment processing system | Retries, idempotency, recovery after a failure | [Design Payment System](https://www.designgurus.io/course-play/grokking-system-design-interview-ii/doc/design-payment-system?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview) |
| Design a distributed rate limiter | Algorithms and coordination across servers | [Designing an API Rate Limiter](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-an-api-rate-limiter?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview) |
| Design a streaming platform | Global distribution and fast growth | [Designing Youtube or Netflix](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-youtube-or-netflix?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview) |

Two terms need definitions. A large language model (LLM) is a model that reads text and generates text. Idempotency means an operation gives the same result whether it runs once or five times, which matters because retries cannot be avoided.

## What the products imply

OpenAI's products are a chat application and a developer API, and the reported questions follow them. For questions that include a model, sources recommend three extra requirements: model latency per request, cost per call, and whether the response streams. The model is treated as one component with known latency and cost.

The AI questions still reduce to familiar problems. Those problems are request routing, queuing and batching, caching, storage layout, and permission models. Reported variants include the following.

- Design the OpenAI API itself, with key management, rate limits for each key, usage metering, and billing.
- Design token streaming for a chat endpoint, including failures in the middle of a stream.
- Design a model deployment system that serves a large model to millions of users.

## What a strong answer includes

1. Requirements and scale in the first 5 minutes, with one or two rough numbers.
2. The API before the architecture, with request and response shapes and error behavior.
3. A core path that works from start to end, then overload, retries, and partial failure.
4. One deep section that you choose before the interviewer chooses for you.
5. A close on how the design changes at 10 times the traffic.

Three habits are reported to matter in the follow-up questions.

- Sketch the screen first on product questions, then derive the API from the screen and the storage from the API.
- Name a property before a product. "A durable log" is easier to defend than a named queue.
- State what you will cover first and why. Scoping is graded as a separate skill.

## Go deeper

- [Grokking the AI System Design Interview](https://www.designgurus.io/course/grokking-the-ai-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview): the course for designs that include a model.
- [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview): the core method and the classic designs.
- Lesson: [Inference Economics](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/inference-economics?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview), in Grokking the AI System Design Interview
- Lesson: [Long-Polling vs WebSockets vs Server-Sent Events](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/longpolling-vs-websockets-vs-serversent-events?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview), in Grokking the System Design Interview
- Free article: [OpenAI System Design Interview Questions](https://www.designgurus.io/blog/openai-system-design-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=system-design-interview)
- Free guide: [OpenAI system design interview](https://github.com/design-gurus/grokking-system-design/blob/main/companies/openai.md), in Grokking System Design
