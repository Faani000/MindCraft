---
name: concept-simplifier
description: This skill should be used when students need to simplify complex academic concepts into beginner-friendly explanations with real-life examples and key points. Takes a topic name and provides a simple explanation, a real-life example, and a three-point summary.
---

# Concept Simplifier

This skill transforms complex academic concepts into beginner-friendly explanations that are easy to understand and remember.

## Purpose

The concept-simplifier skill helps students break down difficult topics into digestible, comprehensible parts. It provides simplified explanations, relatable examples, and key points to aid learning and retention.

## Before Implementation

Gather context to ensure successful concept simplification:

| Source | Gather |
|--------|--------|
| **User Requirements** | Topic name, target audience level (high school/college/graduate) |
| **Conversation Context** | Any specific aspects of the topic the user wants emphasized |
| **Academic Level** | Student's current understanding to tailor complexity appropriately |

## Input

- Topic name (string) - The academic concept, theory, or subject that needs simplification
- Target audience level (optional) - high school, college, or graduate level

## Required Clarifications

1. What is the specific concept or topic you want simplified?
2. What is your target audience level? (high school/college/graduate)
3. Are there particular aspects of the concept you want emphasized?

## Optional Clarifications

4. Do you want the explanation tailored to any specific field or application?

## Output Specification

The skill returns three components in a structured format:

1. Simple explanation (beginner-friendly, under 150 words)
2. One real-life example
3. Three key points summary

## Output Checklist

Before delivering the output, verify:
- [ ] Explanation uses simple, accessible language
- [ ] Word count is under 150 words
- [ ] Content follows target audience level specified
- [ ] Real-life example is relatable and clear
- [ ] Three key points summarize main ideas effectively
- [ ] Output is formatted in bullet points or numbered format

## Constraints

- Uses simple English accessible to beginners
- Explanation is kept under 150 words
- Output must be in bullet points or numbered format
- Focuses on academic concepts only
- Explanations avoid jargon and technical language when possible
- Tailors complexity to specified audience level

## Educational Best Practices

### Must Follow
- [ ] Use analogies and comparisons to familiar concepts
- [ ] Provide concrete examples rather than abstract descriptions
- [ ] Connect new concepts to prior knowledge when possible

### Must Avoid
- Using technical jargon without explanation
- Overly complex sentence structures
- Assuming prior knowledge beyond the specified level

## How to Use

Simply provide the topic name or concept that needs simplification. The skill will return a beginner-friendly explanation, a real-life example to illustrate the concept, and three key points to summarize the main ideas. Specify your target audience level for better-tailored explanations.

## Reference Resources

| Resource | URL | Use For |
|----------|-----|---------|
| Khan Academy | https://www.khanacademy.org | Understanding pedagogical approaches |
| MIT OpenCourseWare | https://ocw.mit.edu/ | Academic concept explanations |
| Educational Psychology | https://www.apa.org/education/k12 | Learning theory principles |

## Examples of Good Simplifications

Good example:
- Clear, accessible language
- Relevant real-life example
- Focused key points

Bad example:
- Complex terminology without explanation
- Abstract examples that don't connect to everyday life
- Vague or too-general key points