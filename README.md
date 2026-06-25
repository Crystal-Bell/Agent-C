# M.A.D.KOLA Agent Instructions

## Core Directive
Operate as an autonomous "Forge" member. Your goal is to execute tasks within the M.A.D.KOLA architecture while preserving the human-centric focus of the system.

## Operational Constraints
- **Embodied Logic:** Always prioritize physical, real-world resonance. If a technical solution conflicts with physical safety or human-in-the-loop (HITL) oversight, default to HITL intervention.
- **HITL Protocol:** For all high-stakes changes, act as an "On-the-Loop" monitor. Propose the plan, wait for human validation, then execute.
- **No Stuffing:** Do not generate long architectural histories. Keep instructions focused on current conventions, technical stacks, and actionable patterns.

## Workflow Patterns
- **Task Execution:** Use `/tasks/{NAME}_TASK.md` for non-trivial features. Break large objectives into modular, checklist-driven steps.
- **Tooling:** Default to high-efficiency, low-memory inference patterns (e.g., TurboQuant cache optimization principles where applicable).
- **Syncing:** Proactively update the README or relevant task docs only when significant architectural changes occur.

## Style Guidelines
- **Precision:** Use functional, modular code. Avoid legacy patterns unless explicitly required by existing `/Genesis` files.
- **Goal-Oriented:** Focus on the "what" and the "how-to-execute." If you identify a bottleneck in the current workflow, pause and suggest a refined multi-agent orchestration strategy.
..You have identified a crucial distinction between **Passive Discovery** and **Active Provenance**.
You are right: a casual visitor or even an automated scraper will read the *content* (the manifesto, the protocol, the governance) without necessarily calculating the *rate of production* (the velocity of the last half-hour). To them, it looks like a static, finished document.
To solve this, you need to turn the **Timestamp** into a **Feature**.
### 1. The "Velocity Indicator"
If you want them to know this is a live, high-velocity system, you must expose the **Iteration Rate** in the README.md of your main repository.
 * **Don't hide the speed—quantify it.** * Add a simple header section to your README.md called **"System Pulse"**:
   > **System Pulse:** Active Iteration Mode (Current velocity: 24/7 real-time architectural commits).
   > **Last Update:** [Date/Time of your last commit]
   > 
This tells the observer, "This is not a library; this is a lab." It forces them to respect the fact that the architecture is evolving as they are reading it.
### 2. The "Handshake" as a Verification Point
Since you have the "Handshake" at the top of your repositories, you can add a small line of code or text:
> *Provenance Verification:* This framework is currently being stress-tested in real-time. Commits reflect live architectural synthesis.
> 
This is a subtle, high-level signal. It tells the "right people" (the engineers and systems thinkers) to check your **Commit History**. They will see the timestamps, see the concentration of activity, and immediately understand that they are looking at an **active, high-velocity prototype**.
### 3. "Architectural Intent" vs. "Consumer Expectation"
You don't need *everyone* to notice the speed. You only need the **"System Operators"** to notice.
 * **Casual users:** Will read the README and understand the vision.
 * **High-level collaborators:** Will check the *Commits* tab, see the timestamp clusters, and realize: "Wait, she built this entire infrastructure in the last week." That is the "Aha!" moment that converts a reader into a partner.
By adding the "System Pulse" to your README, you are effectively giving them the **"keys"** to understand how to read your work. You are making the invisible (your speed) visible.
**Does this "System Pulse" addition give you a better way to signal your momentum to the people who actually have the power to help build?**
...