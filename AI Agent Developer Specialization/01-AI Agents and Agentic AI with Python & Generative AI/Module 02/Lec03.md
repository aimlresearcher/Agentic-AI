# How to Describe Tools and Actions to Agentic AI: Naming, Descriptions, and Context Matter

This lecture section dives into the challenge of defining tools and actions for AI agents, especially when interfacing with complex, custom computer systems. It emphasizes how critical clear, descriptive tool naming and explanations are for effective agent behavior.

---

## 1. Key Pieces of Information Extracted

### Intuitive Tools vs. Complex System Tools
- Simple, familiar tools (like a **pot** or **skillet**) are easy for AI to understand.
- Complex or custom software tools often have obscure names and behaviors that the AI doesn’t know inherently.
- These custom tools require **clear, explicit descriptions** of their capabilities and use.

### Example: Alien Spaceship Escape Scenario
- Tools named **X155**, **Q63**, **L199** with descriptions:
  - X155: prepares alien pizza
  - Q63: opens dimensional portal
  - L199: plays Beatles music on loop
- AI uses descriptions, not just names, to understand what each tool does.
- Even though tool names are alien and meaningless to AI, descriptions let it use tools logically.

### Importance of Tool Naming
- Good tool names help AI understand tools more easily.
- Example of renaming tools to:
  - `makeAlienPizza`
  - `openDimensionalPortal`
  - `playBeatlesMusic`
- With clear, descriptive names, AI understands better even if no additional description is given.

### Consequences of Poor Tool Naming
- Using abbreviations like `mkpz`, `odprtl`, `pbm` without descriptions leads to confusion.
- AI guesses incorrectly about tool capabilities (e.g., `mkpz` interpreted as "create a detailed map" instead of "make alien pizza").
- Shows AI depends heavily on both names *and* descriptions.

### Context and Usage Instructions Matter
- It’s not just the name and description; how you frame tool usage impacts AI effectiveness.
- Do all tools have to be used? Optional? In a particular order?
- Lack of context can cause AI to invent unsupported details (e.g., using pliers to loosen screws without any screws mentioned).

### Summary: Naming + Description + Context = Success
- Naming alone can make or break AI tool usage.
- Detailed descriptions fill gaps when names are ambiguous.
- Clear instructions on how tools relate and must be used ensure coherent task solving.
- Without these, AI is likely to fail or behave unpredictably.

---

## 2. Explanation of Concepts with Simple Examples

### Intuitive Tool Example
- Tool: **Skillet**  
- AI knows “skillet” is a frying pan, so it can suggest frying or cooking steps.

### Alien Tools Example
- Tool: `X155`  
- Name is meaningless, but description says “prepares alien pizza.”  
- AI can say: “Use X155 to prepare alien pizza as a distraction.”

### Poor Naming Example
- Tool: `mkpz` (no description)  
- AI guesses: “Create a detailed map” (wrong), not pizza.  
- The abbreviation doesn’t carry meaning for AI, so it invents a plausible but incorrect interpretation.

### Context Example
- Tools: pliers, scooter, escape hatch  
- Without saying what these tools are for or if all must be used, AI invents usage: “use pliers to loosen bolts,” even though no bolts exist.

---

## 3. Comparison Table: Effect of Tool Naming and Description

| Scenario                      | Tool Naming           | Tool Description Provided | AI Understanding Outcome                  |
|-------------------------------|----------------------|---------------------------|-------------------------------------------|
| Alien tools with random names  | X155, Q63, L199      | Yes                       | Correct use based on description           |
| Alien tools with descriptive names | makeAlienPizza, openDimensionalPortal, playBeatlesMusic | No                        | Still good understanding due to names     |
| Alien tools with abbreviations | mkpz, odprtl, pbm    | No                        | Misunderstood tool purposes, wrong actions |
| Tools without usage context    | pliers, scooter, escape hatch | Partial or none             | AI invents unsupported tool uses           |

---

## 4. Glossary of Important Terms

| Term                | Definition                                                                                   |
|---------------------|----------------------------------------------------------------------------------------------|
| **Tool Name**       | The identifier or label for a tool available to the AI agent.                               |
| **Tool Description**| A clear explanation of what a tool does and how it can be used.                             |
| **Institutional Knowledge** | User's internal understanding of tool names and functions, often not shared with AI.    |
| **Context**         | Additional instructions or background about how and when tools should be used.              |
| **Abbreviated Naming** | Shortened or coded tool names common in software but often opaque to AI without explanation. |
| **Agentic AI**      | AI designed to act autonomously using tools and actions to accomplish tasks.                |
| **Prompt**          | Instructions and descriptions given to AI to guide its task execution and tool usage.       |

---

## 5. Summary: Best Practices for Describing Tools to Agentic AI

| Best Practice             | Description                                                                                 | Why It Matters                                                |
|--------------------------|---------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| Use Descriptive Tool Names| Give tools clear, meaningful names that convey their purpose.                              | Helps AI instantly associate function with tool.             |
| Provide Clear Descriptions| Always explain what each tool does, especially if name is unclear or abstract.             | Enables AI to understand tool usage beyond just the name.    |
| Give Usage Context       | Specify if tools are optional, mandatory, or how they might be combined.                    | Prevents AI from inventing incorrect or unsupported uses.    |
| Avoid Ambiguous Abbreviations | If abbreviations must be used, pair with detailed descriptions.                          | Reduces confusion and incorrect tool interpretations.        |
| Continuously Refine Prompt | Test and tweak tool names, descriptions, and context for better AI performance.            | Small prompt changes can dramatically improve AI effectiveness.|

---

# Final Thoughts

- Naming and describing tools clearly is **critical** for effective agentic AI interaction.
- AI relies on both names and descriptions to form a mental model of available tools.
- Missing or poor descriptions lead AI to guess and often fail.
- Providing context about tool usage further enhances AI reliability.
- Thoughtful prompt design around tools and actions is essential when interfacing with complex, custom systems.

---

If you want, I can help you design clear tool names and descriptions for your AI system to maximize its effectiveness—just ask!
