## What

This paper uses program synthesis and program analysis techniques to improve the performance of two large language models (GPT3, Codex) on a natural language to code snippet translation task.

## Why?

The pre-trained large language models (PTLM) suffer from two problems:

- don't understand program semantics,
- the quality of their output code snipeets can be low.

In particular, their approach handles the following three issues in the output of PTLM.

- referencing errors: even with the correct context, the output might incorrectly reference variable names.
- incorrect arguments: right functions but wrong arguments.
- semantic errors: dfin.ix (wrong), dfin.loc (correct)

## How?

For the first two issues, they used program analysis techniques to check the correctness of the code and variable name referencing. For the semantic error, they adopted but adjusted a program synthesis technique (Autopanda) which perofrms an enumerative search in an argument space given a natural language query and input table. What they did is to extract the method name first from the model output. Then the argument search space is inferred using 1) the NL text input, 2) the argument presented in the model output, 3), the column names in the data table, and 4) variables in the scope.

## Findings and Takeaways

Their approach outperformance using the two language models alone and I/O example based program synthesis technique.

- code quality is more nuanced than just the correctness on unit tests.
- ideally, AI code assistance should produce high quality code, no security vulnerabilities, and respect licensing attribution

## Where

![office](office.JPG)
