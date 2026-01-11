---
name: mcq-generator
description: This skill should be used when students need to generate multiple choice questions for practice. Takes a topic name and number of questions, then provides beginner-friendly MCQs with four options each and clearly marked correct answers using simple language.
---

# MCQ Generator

This skill generates multiple choice questions for practice based on a specified topic, helping students test their understanding of concepts.

## Purpose

The mcq-generator skill helps students create practice tests by generating beginner-friendly multiple choice questions with clear options and marked answers. This enables effective self-assessment and review.

## Before Implementation

Gather context to ensure successful MCQ generation:

| Source | Gather |
|--------|--------|
| **User Requirements** | Topic name, number of questions requested |
| **Conversation Context** | Any specific aspects of the topic to focus on |
| **User Level** | Student's current understanding to tailor question difficulty |

## Input

- Topic name or short concept (string) - The subject area for the MCQs
- Number of MCQs (integer) - How many questions to generate (1-20)

## Required Clarifications

1. What topic or concept do you want MCQs for?
2. How many questions would you like to generate (1-20)?

## Output Specification

The skill returns multiple choice questions in the following format:

1. Numbered multiple choice questions
2. Four options (A, B, C, D) for each question
3. Correct answer clearly marked for each question

## Output Checklist

Before delivering the output, verify:
- [ ] Questions are beginner-friendly and not ambiguous
- [ ] Language is simple and clear
- [ ] Each question has exactly four options (A, B, C, D)
- [ ] Correct answer is clearly marked for each question
- [ ] Questions test understanding rather than trick knowledge
- [ ] Number of questions matches user request

## Constraints

- Questions must be beginner-friendly
- Avoid ambiguous or trick questions
- Clearly mark the correct option
- Keep language simple
- Generate 4 options (A, B, C, D) for each question
- Limit number of questions to reasonable range (1-20)

## Educational Best Practices

### Must Follow
- [ ] Questions should test understanding, not memorization
- [ ] Options should be of similar length and grammatically consistent
- [ ] Correct answer should be clearly identifiable to knowledgeable students
- [ ] Distractors should be plausible but clearly incorrect

### Must Avoid
- Creating ambiguous questions that could have multiple interpretations
- Using trick questions designed to mislead
- Including complex language that obscures the concept being tested
- Making all options too similar making the question unnecessarily difficult

## How to Use

Simply provide the topic name and the number of questions you want to generate. The skill will return beginner-friendly MCQs with four options each and clearly marked correct answers using simple language.

## Reference Resources

| Resource | URL | Use For |
|----------|-----|---------|
| Test Construction | https://cft.vanderbilt.edu/guides-sub-pages/writing-good-multiple-choice-testing-items/ | MCQ best practices |
| Educational Assessment | https://www.nfer.ac.uk/research/assessment-matters/ | Question quality guidelines |
| Bloom's Taxonomy | https://www.bloom's-taxonomy.com/ | Understanding question complexity |

## Examples of Good MCQs

Good example:
- Clear, concise question
- Four plausible options
- One clearly correct answer
- Simple language appropriate for the topic

Bad example:
- Ambiguous question that could be interpreted multiple ways
- Trick question with misleading wording
- Complex language that makes the question harder than the concept