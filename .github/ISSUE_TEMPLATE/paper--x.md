---
name: 'Paper: X'
about: Paper digestion life-cycle records
title: ''
labels: ''
assignees: ''

---

**Q1: Why am I reading it? What problem is this solving? (10 minutes)**
*Example1: I want to understand whether ReAct improves tool-use reliability for my Design Assistant.*
*Example2: I want to see if GraphRAG helps retrieve aviation requirements better.*

**Q2: What is the insight from this paper that is helpful to my own project? (30 minutes)**
*Example: Reasoning should be interleaved with actions.*

**Q3: What is the architecture? (Inputs, Outputs, Components, Data Flow) (30 minutes)**
*Example ReAct:*
```
User
 ↓
LLM

 ├── Thought
 ├── Action
 └── Observation

Loop

 ↓
Final Answer
``` 

**Q4: Define MVP (10 minutes)**
*Example ReAct:*
```
GPT
+
Wikipedia Tool
+
Loop
```
