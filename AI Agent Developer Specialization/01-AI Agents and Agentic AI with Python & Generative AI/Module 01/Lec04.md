
This output is easy to parse and run as code, no matter your programming language.

---

## Example 3: Executing Bash or Python Code

We can also ask AI to output code blocks in Bash or Python:

- AI outputs a code block with the command.
- We run the code.
- We give the output back to AI.
- AI decides the next step.

This method is more risky (running arbitrary code automatically), but it's possible.

---

## Summary: Two Ways to Get Actions from AI

- **Prompt engineering + parsing:**  
Design prompts so AI outputs strict, parsable text. Works with any AI model.

- **Function calling (advanced):**  
Some AI models support calling functions directly and output JSON with function names and arguments. This makes parsing easier but needs special model features.

---

# Glossary

- **Generative AI:** AI that creates new content like text or images.
- **Prompt:** The question or instruction you give an AI model.
- **Parsing:** Reading and understanding text output to extract useful information.
- **Template:** A pattern or format with placeholders for the AI to fill in.
- **Deterministic:** Always giving the same output for the same input.
- **Agent:** An AI program that decides and takes actions automatically.
- **Function calling:** A special AI feature where it outputs structured commands to call specific functions with parameters.
- **JSON:** A format to structure data that is easy to read and write by programs.
- **Bash:** A command-line shell used in Linux/Unix systems.
- **Base64 encoding:** A way to convert data into text using letters, numbers, and symbols.
