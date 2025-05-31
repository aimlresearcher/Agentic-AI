# How Agentic Systems Interact with the World: Tools and Actions Explained

This transcript explores how AI agents (agentic systems) interact with their environment through **tools** or **actions**, why constraining these is critical, and how to think about defining and bounding agent capabilities for effective, real-world task completion.

---

## 1. Key Pieces of Information Extracted

### Agents Interact Through Tools or Actions
- Agents **cannot just imagine any solution** they want; they must operate within **defined tools or actions**.
- Tools and actions are how agents **affect** or **gather information** from their environment.

### Tools vs. Actions: Concept and Examples
- **Tools:** Physical or conceptual resources the agent can use.
  - Example: In cooking, a skillet, a pan, or a wood fire.
- **Actions:** Specific operations or commands the agent can perform using tools.
  - Example: “Put pan on fire,” “Stir dough,” “Send email.”

### Example: Cooking Agent with Limited Tools
- Agent is given **only** a one-quart sauté pan, a skillet, a cast iron skillet, and a wood fire (oak).
- Agent **does not physically act**; it **instructs the human** step-by-step.
- Agent plans and guides cooking within these constraints.
- The agent cannot suggest other tools like a microwave or Instant Pot.
- The agent solves the problem **with the tools provided**, emphasizing constraint.

### Real-World Constraints for Agentic AI
- Agents must be **bounded by what’s realistically accessible**.
- Example: An AI cannot just use a supercomputer if it doesn’t have access.
- Boundaries are crucial for safe, predictable interaction with systems like CRM, email, or other software.

### When to Use "Tool" vs "Action"
- **Tools** are better when interacting with humans or flexible systems.
  - Humans can flexibly use tools to perform many actions.
  - E.g., Tool = "phone," Action = "make a call."
- **Actions** are better when interfacing with rigid computer systems.
  - Finite, explicit instructions must be clearly defined.
  - E.g., Actions might be "create contact," "send email," "query database."

### Programming Analogy
- Like CPUs have a limited instruction set.
- Agentic AI actions must be explicitly defined.
- Whether to use “tool” or “action” terminology depends on the interface and context.

---

## 2. Explanation of Concepts with Simple Examples

### Why Agents Need Tools or Actions

**Imagine:** You want an AI to plan a trip.  
- If you don’t restrict it, it might say, “Fly private jet,” which you don’t want.  
- Instead, you define allowed transport methods: “car, bus, train.”  
- The AI must choose only from those—tools or actions it can use.

### Cooking Example (Step-by-step)

1. **Available tools:** skillet, wood fire, pan.  
2. You say, “Cook pizza.”  
3. AI says, “Gather ingredients.” You do it.  
4. AI says, “Prepare dough.” You do it.  
5. AI says, “Light the wood fire.” You do it.  
6. AI says, “Preheat skillet on fire.” You do it.  
7. AI guides cooking step-by-step within these tools.

This teaches the AI **to solve the problem using what’s actually available**, not invent impossible options.

### Tools vs. Actions in Context

- **Tools + Humans:**  
  *Tool:* “Use the phone”  
  *Human decides action:* “Call mom,” “Send text,” “Check voicemail”  
- **Actions + Computers:**  
  *Action:* “Send email,” “Delete contact” — explicit, finite, and rigid.

---

## 3. Comparison Table: Tools vs Actions

| Aspect               | Tools                                    | Actions                                  |
|----------------------|------------------------------------------|-----------------------------------------|
| Definition           | Resources or instruments used to perform tasks | Specific operations or commands          |
| Common Use Case      | Interactions involving humans or flexible agents | Interactions with rigid computer systems |
| Flexibility          | High — many possible actions per tool    | Low — must be explicitly defined         |
| Example (Cooking)    | Skillet, wood fire                        | “Put skillet on fire,” “Cook dough”      |
| Example (Computers)  | Phone (tool for communication)            | “Send email,” “Query database”            |
| Agent role           | Suggests use of tool, human executes      | Agent executes or triggers discrete actions |

---

## 4. Glossary of Important Terms

| Term              | Definition                                                                                       |
|-------------------|-------------------------------------------------------------------------------------------------|
| **Agentic System** | An AI system capable of acting autonomously to accomplish tasks in the world.                   |
| **Tool**          | A resource or instrument an agent can use to interact with the environment, often indirectly.   |
| **Action**        | A specific, discrete operation or command an agent performs, usually with computers.             |
| **Bounded Tools/Actions** | A constrained, limited set of allowed tools or actions an agent can use to solve a problem.  |
| **Persona**       | The defined role or identity of the agent (e.g., “helpful cooking assistant”).                    |
| **Constraint**    | Limits placed on what tools or actions an agent may use, reflecting real-world availability.    |
| **Ephemeral Information** | Temporary data or feedback during task execution, guiding next steps.                      |
| **CPU Instruction Set** | A fixed set of operations a computer’s processor can perform, analogous to an agent’s actions.|

---

## 5. Summary: How Agents Use Tools and Actions in Practice

| Step                | What Happens                                             | Why It Matters                                            |
|---------------------|----------------------------------------------------------|-----------------------------------------------------------|
| Define tools/actions | List exactly what the agent can use or do                | Prevents impossible or unsafe requests                    |
| Constrain universe   | Limit agent’s options to realistic capabilities          | Ensures feasible, predictable solutions                   |
| Use human-agent loop | Agent instructs human or system step-by-step              | Allows gradual task progress with feedback                |
| Choose terminology   | Use “tools” when flexibility exists, “actions” when rigid | Matches the interaction type for better clarity           |

---

# Final Thoughts

- Agentic AI must interact with the world through **defined, limited tools or actions**.
- Properly constraining tools/actions prevents unrealistic or unsafe behavior.
- Understanding the difference between tools and actions helps design better agent interfaces.
- Clear constraints and structured prompts lead to agents that solve problems effectively within real-world limits.

---

If you want, I can help you design a tool/action set for an agent for your specific domain—just let me know!
