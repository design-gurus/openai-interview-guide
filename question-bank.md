# OpenAI interview question bank

This page lists 56 questions in three groups: 28 coding, 14 system design, and 14 behavioral. The reported questions come from candidate accounts, and interviewers are free to choose their own, so use the list as practice material. The follow-up questions carry most of the score.

## Coding: reported practical tasks

Each of these 10 tasks starts small and then grows through new requirements. Build the first version, test it, and then extend it.

| # | Task | Related lesson |
|---|---|---|
| 1 | Implement spreadsheet cells, where a formula refers to other cells and an update reaches every dependent cell | [Topological Sort](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/topological-sort-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 2 | Build an iterator, extend it to two dimensions, then write an asynchronous version | [Binary Search Tree Iterator](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/binary-search-tree-iterator-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 3 | Implement encode and decode for a list of strings | [Encode and Decode Strings](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/encode-and-decode-strings?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 4 | Implement a credit management system that tracks usage, refunds, and concurrent requests | [Code That Grows With Each Requirement](https://www.designgurus.io/course-play/grokking-the-forward-deployed-engineer-interview/doc/code-that-grows-with-each-requirement?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 5 | Refactor deeply nested code to support a new requirement while the existing tests still pass | [Reading an Unfamiliar Codebase](https://www.designgurus.io/course-play/grokking-the-forward-deployed-engineer-interview/doc/reading-an-unfamiliar-codebase?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 6 | Design a chess game with classes | [Design Chess](https://www.designgurus.io/course-play/grokking-the-object-oriented-design-interview/doc/design-chess?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 7 | Build a rate limiter | [Rate Limiting](https://www.designgurus.io/course-play/grokking-concurrency-in-python/doc/rate-limiting?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 8 | Implement a cache that evicts the least recently used or least frequently used item | [Introduction to Hash Map Pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-hash-map-pattern?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 9 | Build a store where every value carries a timestamp, and read the value as of any past time | No matching lesson |
| 10 | Build a chat interface with classes, then add commands such as status tracking | No matching lesson |

## Coding: pattern practice

Algorithm questions are reported at medium to hard difficulty. These 18 problems are taught in Grokking the Coding Interview and cover the topics candidates report: hash maps, strings, recursion, sorting, and scheduling. They are practice problems, not reported OpenAI questions.

| # | Problem | Pattern |
|---|---|---|
| 11 | [Two Sum](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/two-sum-easy?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Hash map |
| 12 | [Group Anagrams](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/group-anagrams-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Hash map |
| 13 | [Subarray Sum Equals K](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/subarray-sum-equals-k-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Prefix sum |
| 14 | [Longest Substring with K Distinct Characters](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/longest-substring-with-k-distinct-characters-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Sliding window |
| 15 | [Valid Parentheses](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/valid-parentheses-easy?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Stack |
| 16 | [Decode String](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/decode-string-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Stack |
| 17 | [Evaluate Expression](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/problem-challenge-1-evaluate-expression-hard?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Recursion |
| 18 | [Word Break](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/word-break-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Dynamic programming |
| 19 | [Merge Intervals](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/merge-intervals-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Merge intervals |
| 20 | [Minimum Meeting Rooms](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/problem-challenge-1-minimum-meeting-rooms-hard?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Merge intervals |
| 21 | [My Calendar I](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/my-calendar-i-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Ordered set |
| 22 | [Top K Frequent Numbers](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/top-k-frequent-numbers-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Top K elements |
| 23 | [Kth Largest Number in a Stream](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/kth-largest-number-in-a-stream-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Top K elements |
| 24 | [Find the Median of a Number Stream](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/find-the-median-of-a-number-stream-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Two heaps |
| 25 | [Merge K Sorted Lists](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/merge-k-sorted-lists-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | K-way merge |
| 26 | [Tasks Scheduling Order](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/tasks-scheduling-order-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Topological sort |
| 27 | [Implement Trie (Prefix Tree)](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/implement-trie-prefix-tree-medium-1?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Trie |
| 28 | [Number of Islands](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/number-of-islands-easy?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) | Graph traversal |

## System design

Questions 29 to 37 are reported across engineering loops. Questions 38 to 42 are the AI infrastructure variants.

| # | Question | Related lesson |
|---|---|---|
| 29 | Design the OpenAI Playground, from the interface down to the architecture | [Design a ChatGPT-Style Assistant](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/design-a-chatgptstyle-assistant?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 30 | Design an enterprise search system built on a large language model | [Capstone: Enterprise Document Q&A](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/capstone-enterprise-document-qa?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 31 | Design a notification system | [Designing a Notification System](https://www.designgurus.io/course-play/grokking-system-design-interview-ii/doc/designing-a-notification-system?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 32 | Design Slack, then explain what changes at 100 and 1,000 times the traffic | [Designing Facebook Messenger](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-facebook-messenger?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 33 | Design a job scheduler with distributed execution and fault tolerance | [Design a Reminder Alert System](https://www.designgurus.io/course-play/grokking-system-design-interview-ii/doc/design-a-reminder-alert-system?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 34 | Design a payment processing system with retries and idempotency | [Design Payment System](https://www.designgurus.io/course-play/grokking-system-design-interview-ii/doc/design-payment-system?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 35 | Design a streaming platform that keeps working as users and data grow | [Designing Youtube or Netflix](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-youtube-or-netflix?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 36 | Design a distributed rate limiter | [Designing an API Rate Limiter](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-an-api-rate-limiter?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 37 | Sync key and value state to and from the cloud | No matching lesson |
| 38 | Design the OpenAI API, with key management, rate limits for each key, and usage metering | [Distributed Rate Limiting](https://www.designgurus.io/course-play/grokking-system-design-fundamentals/doc/distributed-rate-limiting?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 39 | Design token streaming for a chat endpoint | [Long-Polling vs WebSockets vs Server-Sent Events](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/longpolling-vs-websockets-vs-serversent-events?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 40 | Design usage quotas and billing for an AI API | [Inference Economics](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/inference-economics?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 41 | Design a deployment system that serves a large model to millions of users | [Model Serving Basics](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/model-serving-basics?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank) |
| 42 | Design a distributed training system for deep learning models | No matching lesson |

## Behavioral

**Motivation and AI**

- 43. Why do you want to work at OpenAI, and not at another lab?
- 44. Which OpenAI product or research direction interests you most, and why?
- 45. What is your view on where AI is heading and how people will use it?
- 46. Where do you see AI going wrong or being misused?
- 47. How do you think about the risks of the technology you would build here?

**Speed and ownership**

- 48. Tell me about a release under a tight deadline. What did you cut, and how did you decide?
- 49. Tell me about a decision you made with incomplete information.
- 50. Describe a project where the requirements kept changing. How did you keep making progress?
- 51. Tell me about work you took on that was outside your job description.
- 52. Tell me about a project you drove from start to end.

**Disagreement and failure**

- 53. Tell me about a time you disagreed with your manager.
- 54. Tell me about a time you worked with a legal team or another function outside engineering.
- 55. Tell me about a significant mistake or failed project. What did you learn?
- 56. Tell me about a technical decision you got wrong.

## Go deeper

- [Grokking the Coding Interview](https://www.designgurus.io/course/grokking-the-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank): the course that teaches problems 11 to 28 by pattern.
- [Grokking the AI System Design Interview](https://www.designgurus.io/course/grokking-the-ai-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank): the course for questions 29, 30, and 38 to 42.
- Lesson: [Coding Patterns: A Cheat Sheet](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/coding-patterns-a-cheat-sheet?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank), in Grokking the Coding Interview
- Lesson: [Initiative and Leadership Questions](https://www.designgurus.io/course-play/grokking-behavioral-interview/doc/initiative-and-leadership-questions?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank), in Grokking Modern Behavioral Interview
- Free article: [OpenAI System Design Interview Questions](https://www.designgurus.io/blog/openai-system-design-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank)
- Free answer: [Top OpenAI Behavioral Interview Questions (and How to Answer Them)](https://www.designgurus.io/answers/detail/top-openai-behavioral-interview-questions-and-how-to-answer-them?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=question-bank)
