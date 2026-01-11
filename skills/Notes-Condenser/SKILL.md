---
name: notes-condenser
description: This skill should be used when students need to condense long study materials into short, focused notes. Takes long text or study material and provides a bullet point summary with key points highlighted, all under 150 words using simple English.
---

# Notes Condenser

This skill transforms lengthy study materials into concise, focused notes that are easy to review and remember.

## Purpose

The notes-condenser skill helps students break down long texts into digestible, condensed notes. It extracts the most important information and presents it in a clear, bullet-point format for efficient studying.

## Before Implementation

Gather context to ensure successful note condensation:

| Source | Gather |
|--------|--------|
| **User Requirements** | Long text or study material to condense |
| **Conversation Context** | Any specific aspects the user wants emphasized |
| **Study Purpose** | Understanding goals (review, exam prep, quick reference) |

## Input

- Long text or study material (string) - The content that needs to be condensed into shorter notes

## Required Clarifications

1. What is the long text or study material you want condensed?
2. Are there specific topics or sections within the text you want emphasized?

## Output Specification

The skill returns two components in bullet point format:

1. Short bullet point summary of the content (under 150 words)
2. Key points highlighted in bullet points

## Output Checklist

Before delivering the output, verify:
- [ ] Content is under 150 words total
- [ ] Uses simple, clear English
- [ ] All output is in bullet points format
- [ ] Key points are clearly highlighted
- [ ] Most important information is preserved
- [ ] Summary captures the essence of the original content

## Constraints

- Output must be under 150 words
- Uses simple, clear English
- Output must be in bullet points only
- Focuses on academic content only
- Preserves essential information while condensing

## Educational Best Practices

### Must Follow
- [ ] Identify and highlight the most important concepts
- [ ] Use clear, concise language
- [ ] Organize information in logical order

### Must Avoid
- Including unnecessary details
- Using complex sentence structures
- Losing critical information in the condensation

## How to Use

Simply provide the long text or study material you want condensed. The skill will return a short bullet point summary with key points highlighted, all under 150 words using simple English.

## Reference Resources

| Resource | URL | Use For |
|----------|-----|---------|
| Study Skills Guide | https://www.studygs.net/ | Effective note-taking strategies |
| Cornell Note-Taking | https://acsc.uccs.edu/ | Condensing information techniques |
| Learning Science | https://www.apa.org/education/k12 | Information retention methods |

## Examples of Good Condensations

Good example:
- Concise bullet points under 150 words
- Key information preserved
- Simple, clear language

Bad example:
- Too lengthy (over 150 words)
- Complex language
- Missing key concepts