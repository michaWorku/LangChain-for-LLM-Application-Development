# LangChain for LLM Application Development

## Course Overview
This course, taught by LangChain creator Harrison Chase, provides essential skills for building advanced LLM-powered applications. Key topics include:
- Models, Prompts, and Parsers – Calling LLMs, structuring prompts, and parsing responses.
- Memories for LLMs – Storing conversations and managing context.
- Chains – Creating sequences of operations for complex workflows.
- Question Answering over Documents – Applying LLMs to proprietary data.

Agents – Using LLMs as reasoning agents to enhance application capabilities.

## Course Contents

### 1. Introduction
#### Overview
- Open-source development framework for LLM applications.
- Supports Python and JavaScript (TypeScript).
- Focuses on composition and modularity.
- Key value additions:
  1. Modular components.
  2. Use cases: Common ways to combine components.

#### Components
- **Models**: LLMs, chat models, text embedding models.
- **Prompts**: Templates, output parsers, example selectors.
- **Indexes**: Document loaders, text splitters, vector stores, retrievers.
- **Chains**: Sequences of operations combining LLMs, prompts, and parsers.
- **Agents**: Autonomous reasoning agents with specialized toolkits.

### 2. [Models, Prompts, and Parsers](https://github.com/michaWorku/LangChain-for-LLM-Application-Development/blob/main/L1-Model_prompt_parser.ipynb)
- Direct API calls to OpenAI and through LangChain.
- **Models**: Control randomness with temperature (e.g., 0.0 for deterministic responses).
- **Prompts**:
  - Structured prompt templates.
  - Reuse effective prompts.
  - Pre-built prompts for common tasks.
- **Output Parsers**:
  - Define structured LLM output.
  - Parse output into Python dictionaries.

### 3. [Memory](https://github.com/michaWorku/LangChain-for-LLM-Application-Development/blob/main/L2-Memory.ipynb)
- LLMs are stateless; memory provides conversational context.
- Types of memory:
  - **Conversation Buffer Memory**
  - **Conversation Buffer Window Memory**
  - **Conversation Token Buffer Memory**
  - **Conversation Summary Memory**
- **Additional Memory Types**:
  - **Vector Data Memory**: Stores and retrieves text using a vector database.
  - **Entity Memories**: Remembers details about specific entities.
  - **Hybrid Memory**: Combines conversation and entity memory.

### 4. [Chains](https://github.com/michaWorku/LangChain-for-LLM-Application-Development/blob/main/L3-Chains.ipynb)
- **LLMChain**: Basic model execution.
- **Sequential Chains**:
  - SimpleSequentialChain.
  - SequentialChain.
- **Router Chain**: Directs queries to specialized chains.

### 5. [Question Answering](https://github.com/michaWorku/LangChain-for-LLM-Application-Development/blob/main/L4-QnA.ipynb)
- Query product catalogs and other document-based data.
- **LLMs on Documents**:
  - LLMs have context limitations (~few thousand words).
- **Embeddings**:
  - Transform text into vector representations.
  - Similar texts have similar vectors.
- **Vector Databases**:
  - Store and retrieve embeddings efficiently.
- **Document Querying Methods**:
  - **Stuffing**: Concatenate all data into a single prompt.
  - **Map-Reduce**: Process smaller chunks and aggregate results.
  - **Refine**: Iteratively improve responses.
  - **Map-Rerank**: Rank results based on relevance.

### 6. [Evaluation](https://github.com/michaWorku/LangChain-for-LLM-Application-Development/blob/main/L5-Evaluation.ipynb)
- Create a Q&A application.
- Combine and test examples:
  - Hardcoded.
  - LLM-generated.
- **Evaluation Techniques**:
  - Manual debugging.
  - LLM-assisted evaluation.
  - LangChain evaluation platform.

### 7. [Agents](https://github.com/michaWorku/LangChain-for-LLM-Application-Development/blob/main/L6-Agents.ipynb)
- Build agents using LangChain tools:
  - Load tools like Wikipedia search, Python REPL.
  - Initialize agents with tools and LLM.
  - Execute actions dynamically.

## Getting Started
1. Install LangChain and dependencies.
2. Set up an API key for LLM access.
3. Run Jupyter notebooks to explore the concepts interactively.

## References
- [Course Link](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)

