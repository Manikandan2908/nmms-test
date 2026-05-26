# GitHub Test Repository

This repository stores test JSON files for an online test application.

## Structure

- index.json → list of tests
- tests/*.json → individual question files

## Question Format

{
  "title": "Test Name",
  "questions": [
    {
      "id": 1,
      "question": "Question text",
      "options": ["A", "B", "C", "D"],
      "answer": "Correct Option"
    }
  ]
}
