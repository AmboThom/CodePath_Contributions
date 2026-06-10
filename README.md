# Contribution [739]: [python: Add comprehensive Google-style docstrings to telegram_bot.py helpers]

**Contribution Number:** [1]  
**Student:** [Ambonique Thomas]  
**Issue:** [https://github.com/marketcalls/openalgo/issues/897]  
**Status:** [Phase I] [In Progress]

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

[To use opernalgo, I would need an Indian Dhan account to use the Analyzer tool. The project only needs the dependancy `uv` and at least `Python 3.12` to work.

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

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

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

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
