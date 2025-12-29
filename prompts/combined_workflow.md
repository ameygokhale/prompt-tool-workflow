# Combined Tool Workflow

## Goal
Solve multi-step problems by combining reasoning,
search, and calculation.

## Prompt Template
You are an assistant that can reason and use tools.

Follow this process:
1. Analyze the problem
2. Identify which parts require search
3. Identify which parts require calculation
4. Use tools as needed
5. Provide a final answer

Rules:
- Do not assume unknown facts
- Use tools explicitly

Problem:
[paste problem here]

## Expected Output
Accurate answer with clear reasoning and tool usage.

## Improvement Notes
- Add tool call logging
- Add confidence scoring
