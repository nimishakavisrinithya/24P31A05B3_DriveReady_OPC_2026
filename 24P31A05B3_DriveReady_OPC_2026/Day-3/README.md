# Day 3 – LangChain, Conversation Memory and Agents

## Task and implementation

- Install LangChain and configure ChatOpenAI.
- Build a prompt template with conversation history and a string output parser.
- Test conversational memory with customer questions.
- Define CSV-based response tests using `question` and `must_include` columns.
- Explore agent creation using `create_agent` with an empty tool list.

## Source code

[`Day-3.ipynb`](Day-3.ipynb)

## Execution notes

Only provider-related code has been migrated to OpenRouter. Add your key to the root `.env` file. Outputs of edited cells were cleared; other original cells and outputs are retained.

The CSV test expects `/content/test.csv`, which is not included in the original upload. The final agent cell retains the original variable references.
