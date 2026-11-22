# The OpenAI coding interview

The OpenAI coding round is commonly reported as a practical task, not an algorithm puzzle. For 45 to 60 minutes you write code that runs, and the interviewer then changes the requirements and asks you to extend it. Algorithm questions still appear, usually at medium to hard difficulty, so you should prepare for both formats.

## Format

| Round | Commonly reported format |
|---|---|
| Technical screen | 45 to 60 minutes of live coding in your own editor or a shared one |
| Final loop coding | About 60 minutes, a harder task with more follow-up requirements |
| Debugging or refactoring | About 60 minutes on code you did not write, reported for frontend and full stack loops |
| Take-home project | Used by some teams instead of a second live round, with a short deadline |

Candidates report less help from interviewers than they expected. The round is built for you to make progress alone, so state what you are trying before you ask for a hint.

## What is graded

Candidates report four stated criteria: solution design, code quality, performance, and test coverage. In the room, that translates into the following order of priorities.

1. Correctness before speed. A simple working answer scores better than a fast broken one.
2. Tests that you write without being asked.
3. Depth in your language, not only its syntax.
4. A structure that stays clean when the requirements change.
5. A clear explanation of each choice while you type.

## Commonly reported tasks

Each reported task starts small, works, and then grows. The interviewer is checking whether your first design can absorb a change without a rewrite.

| Task type | Reported example | Related lesson |
|---|---|---|
| Staged build | A credit system that tracks usage, refunds, and concurrent requests | [Code That Grows With Each Requirement](https://www.designgurus.io/course-play/grokking-the-forward-deployed-engineer-interview/doc/code-that-grows-with-each-requirement?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview) |
| Iterator | An iterator extended to two dimensions, then to an asynchronous version | [Binary Search Tree Iterator](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/binary-search-tree-iterator-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview) |
| Encoding | Encode and decode a list of strings | [Encode and Decode Strings](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/encode-and-decode-strings?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview) |
| Dependency updates | Spreadsheet cells whose formulas refer to other cells | [Topological Sort](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/topological-sort-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview) |
| Parsing | A parser for a structured input format | [Decode String](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/decode-string-medium?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview) |
| API client | A small client that wraps an external API | [Calling and Wrapping an External API](https://www.designgurus.io/course-play/grokking-the-forward-deployed-engineer-interview/doc/calling-and-wrapping-an-external-api?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview) |
| Debugging | Find the fault in unfamiliar code | [A Method for Debugging Unfamiliar Code](https://www.designgurus.io/course-play/grokking-the-forward-deployed-engineer-interview/doc/a-method-for-debugging-unfamiliar-code?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview) |

Other reported tasks include a cache that evicts the least recently used item, a store that returns a value as of a past time, and a rate limiter. A rate limiter is a component that caps how many requests one client may send in a period.

## Topics and patterns

The fundamentals appear inside the practical tasks. Candidates report hash maps, sorting, string handling, recursion, and complexity reasoning most often. You should be able to state the time cost of the code you wrote.

Language depth matters more here than at most companies. For Python, candidates report that iterators, generators, asynchronous code, and concurrency are needed as working knowledge. Concurrency means several tasks making progress during the same period, which requires care with shared data.

## How to practice

- Build under a timer. Set 45 to 60 minutes, write a small program that runs, then add a requirement and extend it.
- Use a real editor and write the test cases before the time ends.
- Read unfamiliar code in your strongest language, and trace one function from start to end.
- Keep the pattern base solid for the algorithm half. A coding pattern is a reusable approach that solves a family of problems.

## Go deeper

- [Grokking the Coding Interview](https://www.designgurus.io/course/grokking-the-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview): the course for the pattern half of the round.
- Lesson: [What Practical Coding Questions Test](https://www.designgurus.io/course-play/grokking-the-forward-deployed-engineer-interview/doc/what-practical-coding-questions-test?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview), in Grokking the Forward Deployed Engineer Interview
- Lesson: [Async Iterators, Generators and Context Managers](https://www.designgurus.io/course-play/grokking-concurrency-in-python/doc/async-iterators-generators-and-context-managers?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview), in Grokking Concurrency in Python
- Lesson: [Coding Patterns: A Cheat Sheet](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/coding-patterns-a-cheat-sheet?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview), in Grokking the Coding Interview
- Free answer: [Does OpenAI Ask LeetCode Questions in Interviews?](https://www.designgurus.io/answers/detail/does-openai-ask-leetcode-questions-in-interviews?utm_source=github&utm_medium=repo&utm_campaign=openai-interview-guide&utm_content=coding-interview)
- Free guide: [Grokking Coding Interview](https://github.com/design-gurus/grokking-coding-interview)
