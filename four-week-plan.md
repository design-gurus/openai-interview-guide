# A four-week plan for the OpenAI interview

Four weeks is enough to prepare for the OpenAI loop if you already write code daily. Spend week 1 on practical coding, week 2 on patterns and reading code, week 3 on system design, and week 4 on stories, your project, and a full mock loop. Each week ends with a finish condition that you can check.

The plan assumes about 10 hours per week. If your recruiter confirms a role-specific round, such as refactoring or a take-home case study, move time toward it. See [Roles](roles.md).

## The plan

| Week | Focus | Finish condition |
|---|---|---|
| 1 | Practical coding: build, test, extend | Three small programs built in 60 minutes each, with tests, and each extended once |
| 2 | Coding patterns, language depth, and unfamiliar code | 12 pattern problems solved, one iterator written by hand, one 100-line file refactored aloud |
| 3 | System design, including product and AI questions | Three designs rehearsed aloud in 45 minutes each, one of them from screen to schema |
| 4 | Behavioral stories, project walkthrough, and a mock loop | Five stories written, one project written up with numbers, one timed mock of each round |

## Week 1: practical coding

- Build a rate limiter, a credit ledger, and a store with timestamps. Use a real editor and run the code.
- After each build, add one new requirement and extend the code without a rewrite.
- Write the test cases before the timer ends. Test coverage is reported as a grading criterion.
- Explain each choice aloud while you type.

Start with [Code That Grows With Each Requirement](https://www.designgurus.io/course-play/grokking-the-forward-deployed-engineer-interview/doc/code-that-grows-with-each-requirement?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=four-week-plan), which teaches the staged format.

## Week 2: patterns, language, and reading code

- Solve 12 pattern problems from the [question bank](question-bank.md), numbers 11 to 28.
- Write an iterator and a generator by hand in your interview language, then an asynchronous version.
- Take one file of 100 to 150 lines with nested conditionals and restructure it aloud on a timer.
- Open an unfamiliar repository and trace one function from start to end.

## Week 3: system design

- Rehearse a job scheduler and a chat system, because both are commonly reported.
- Rehearse the OpenAI Playground from the screen first: layout, then API, then storage schema.
- For each design, cover requirements, the API, the core path, one deep section, and failure handling.
- Prepare one design that includes a model. State model latency, cost per call, and whether the response streams.

[Design a ChatGPT-Style Assistant](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/design-a-chatgptstyle-assistant?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=four-week-plan) is the closest lesson to the product questions reported for this loop.

## Week 4: stories, project, and mock loop

- Write five stories: speed, ownership, conflict, failure, and scale. Keep each one under two minutes.
- Write your answer to "Why OpenAI?" in three parts, and say it aloud until it is fluent.
- Write a position on AI risk in five sentences, with one concrete example.
- Write up one project you owned: decisions, rejected options, numbers, and what you would change.
- Run one timed mock of each round, and ask the other person for hard follow-up questions.

## If you have less time

| Time left | What to keep |
|---|---|
| Two weeks | Week 1 and week 3, plus the "Why OpenAI?" answer |
| One week | Two timed builds, one product design from the screen, and three stories |
| Two days | One timed build with tests, and the motivation and AI risk answers |

## Go deeper

- [Grokking the Coding Interview](https://www.designgurus.io/course/grokking-the-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=four-week-plan): the course for week 2.
- [Grokking the AI System Design Interview](https://www.designgurus.io/course/grokking-the-ai-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=four-week-plan): the course for the AI designs in week 3.
- Lesson: [A Framework for AI Design Answers](https://www.designgurus.io/course-play/grokking-the-ai-system-design-interview/doc/a-framework-for-ai-design-answers?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=four-week-plan), in Grokking the AI System Design Interview
- Lesson: [How to Prepare for Behavioral Interview](https://www.designgurus.io/course-play/grokking-behavioral-interview/doc/how-to-prepare-for-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=four-week-plan), in Grokking Modern Behavioral Interview
- Lesson: [Choosing the Project to Present](https://www.designgurus.io/course-play/grokking-the-forward-deployed-engineer-interview/doc/choosing-the-project-to-present?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=four-week-plan), in Grokking the Forward Deployed Engineer Interview
- Free answer: [How to Prepare for an OpenAI System Design Interview](https://www.designgurus.io/answers/detail/how-to-prepare-for-a-openai-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=four-week-plan)
