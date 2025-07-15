# LangChain Structured Output Practice

This repository contains hands-on practice with **LangChain Structured Output** formats. It focuses on the most popular and widely used methods for structured outputs in LangChain, namely:

- **TypedDict**   
- **Pydantic**  
- **JSON Schema** 

Each example demonstrates how to define structured outputs and how to parse model responses using LangChain's built-in tools. It also includes examples with `with_structured_output`, which provides a clean API to integrate these output formats.

---

## What’s Inside

| File Name | Description |
|-----------|-------------|
| `pydantic_demo.py` | Basic example using Pydantic for output validation and structure. |
| `typeddict_demo.py` | Demonstrates using Python's `TypedDict` for structured outputs. |
| `with_structured_output_typeddict.py` | Example of LangChain's `with_structured_output()` method using TypedDict. |
| `with_structured_output_pydantic.py` | Example of `with_structured_output()` with a Pydantic model. |
| `with_structured_output_json.py` | Uses a JSON Schema with `with_structured_output()` to validate output. |
| `with_structured_output_llama.py` | An advanced example integrating structured output with a LLM wrapper. |

---

## Key Concepts Practiced

- Defining response structures with `TypedDict`, `Pydantic`, and `JSON Schema`
- Leveraging LangChain’s `with_structured_output()` method for clean parsing
- Parsing and validating LLM responses in structured formats
- Preparing structured prompts to get predictable and typed outputs

---

## Why This Matters

Structured outputs are critical for production-level AI applications. They ensure predictable, validated, and type-safe responses from LLMs — which is especially useful in tools, chains, and agents that rely on consistent outputs.

---
