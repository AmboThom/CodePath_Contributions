# Contribution [739]: [python: Add comprehensive Google-style docstrings to telegram_bot.py helpers]

**Contribution Number:** [1]  
**Student:** [Ambonique Thomas]  
**Issue:** [https://github.com/marketcalls/openalgo/issues/897]  
**Status:** [Phase IV] [Complete]

---

## Why I Chose This Issue

[I choose this issue because I have an interest in the trading field. To start my my contributing journey, I choose a documentation issue to get used to the codebase. This issue matches my skills because I haven't worked in a large codebase before. I'm hoping to learn how to read other users code, communicating with other developers, and to understand a large codebase.]

---

## Understanding the Issue

### Problem Description

[There are two helper functions that need Google-style docstrings with Args, Returns, Raises, and Example sections.]

### Expected Behavior

[Code shouldn't change because this issue only asks for comments. Although, when other users read the comments, they should be able to understand how the function works and outputs.]

### Current Behavior

[Both mentioned functions have basic comments that doesn't use Python documentation conventions PEP 257.]

### Affected Components

[The affected file is restx_api/telegram_bot.py .]

---

## Reproduction Process

### Environment Setup

[To use openalgo, I would need an Indian Dhan account to use the Analyzer tool. The project only needs the dependancies `uv` and at least `Python 3.12` to work.

Working Branch: https://github.com/AmboThom/openalgo/tree/feature/doc-touch-up]

### Steps to Reproduce

1. [Navigate to restx_api/telegram_bot.py]
2. [Read both functions to understand how they work.]
3. [Read the functions callers to understand how they are used.]
4. [**Expected:** One line docstrings]
5. [**Actual:** Detailed Google-style docstrings]

### Reproduction Evidence

- **Commit showing reproduction:** [https://github.com/AmboThom/openalgo/tree/feature/doc-touch-up]
- **Screenshots/logs:** [N/A]
- **My findings:** [It wasn't stated that the project is for Indian Dhan accounts or Indian brokers. Users in other countries will not be able to use some of the tools.]

---

## Solution Approach

### Analysis

[Two functions didnt have Google-doc style comments. This is to help other developers who want to understand these functions for later use.]

### Proposed Solution

[Read both functions to understand how they are used and what they are for. Read python documentation to learn about 
errors that the functions can raise.]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [For the functions, `run_async()` and `get_webhook_secret`, add Google-style docstrings using PEP 257.]

**Match:** [Functions are documented the same so the pattern is similar.]

**Plan:** 
1. [Read both functions to understand how they work]
2. [Read PEP 257 to understand how to write Google-style docstrings]
3. [Update docstrings for both functions]

**Implement:** [https://github.com/AmboThom/openalgo/tree/feature/doc-touch-up]

**Review:** [I will review PEP 257 and follow the guidlines to ensure the docstrings are completed.]

**Evaluate:** [Manually review the docstrings to make sure the reader can understand the functions.]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[Nothing was tested but I did proofread my comments to make sure that it can be understood by anyone else who would read them.]

---

## Implementation Notes

### Week [4] Progress

[What you built this week, challenges faced, decisions made]

### Week [4] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [restx_api/telegram_bot.py]
- **Key commits:** [https://github.com/marketcalls/openalgo/commit/911d4a2427ae8f02fb0f57ad861cce4303a977d2
https://github.com/marketcalls/openalgo/commit/32de5f2768b49064cdbb53d0255f6ae56ef2ffe1]
- **Approach decisions:** [I separated the coomits to keep the commits organzied and to pace myself. Each commmit is for me working on each of the functions seperatly.]

---

## Pull Request

**PR Link:** [https://github.com/marketcalls/openalgo/pull/1540]

**PR Description:** [Added Google-style docstrings to telegram_bot helpers following PEP-257.]

**Maintainer Feedback:**
- [Date]: [N/A Maintainer hasn't reviewed or communicated yet.]
- [Date]: [N/A]

**Status:** [Awaiting review]

---

## Learnings & Reflections

### Technical Skills Gained

[I learned how to write Google-style docstrings for functions. Before I just used single line comments but Google-style 
docs helps it looks more readable and a bit easier to understand.]

### Challenges Overcome

[The challenge that I faced was setting up my local machine. The repo gives no clue that the project is for Indian users and you would need an Indian Dhan account to use the project.]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [https://peps.python.org/pep-0257/]
- [I used this prompt to help me setup on my local machine:
    Im trying to install on my local environment. I understand that I need to connect a brokers api in the .env before I start. I'm
  located in the united states, are the available connected brokers only for india users? how can I create an account or find an
  united states broker that I can use instead? use the readme.md to find the available connected brokers or use this link
  https://docs.openalgo.in/connect-brokers/brokers
]
- [GitHub issues or discussions that helped]
