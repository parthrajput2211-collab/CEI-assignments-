# Week 8 - Single Agent Systems & Agent Pipelines

## Objective

The objective of this project is to build a small Single-Agent Smart Assistant that understands user queries, routes them based on intent, uses appropriate tools, and returns structured output.

## Project Components

### 1. Single-Agent Smart Assistant

The agent supports three main routes:

- **Calculate** → Calculator Tool
- **Keywords** → Keyword Extractor Tool
- **General queries** → General Response

The system also includes basic error handling and structured JSON output.

## Agent Pipeline

User Query
↓
Agent
↓
Intent Detection
↓
Conditional Routing
↓
Calculator / Keyword Extractor / General Response
↓
Structured JSON Output

## Technologies Used

- Python
- Google Colab
- JSON
- Python AST
- Regular Expressions

## Features

- Conditional query routing
- Calculator tool
- Keyword extraction tool
- General response handling
- Structured JSON responses
- Error handling
- Multiple test cases
- Routing evaluation

## Quiz

The Week 8 quiz covers concepts related to:

- Stateful directed graphs
- Nodes and edges
- Conditional routing
- Loops
- Single-agent and multi-agent systems
- JSON schemas
- Sequential and parallel tool calls
- Error handling
- Trajectory evaluation
- Task success and cost

The completed quiz answers are included in:

`week8_quiz_answers_Parth_Rohilla.pdf`

## Files

- `week8_Parth_Rohilla.ipynb` - Completed and executed agent pipeline notebook.
- `week 8 quiz.pdf` - Completed Week 8 quiz answers.

## Conclusion

This project demonstrates the basic concepts of single-agent systems and agent pipelines by combining conditional routing, tool usage, structured outputs, and error handling in a small smart assistant.
