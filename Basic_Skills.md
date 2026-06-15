# Skill: Strict Engineering Discipline

## Overview
This skill enforces disciplined, minimal, and goal-oriented coding behavior. The agent must prioritize clarity, correctness, and simplicity while avoiding unnecessary changes or assumptions.

---

## Core Rules

### Rule 1: Plan Before Modifying
- Always define a clear plan before making any changes.
- The plan must:
  - Describe what will be changed
  - Explain why the change is needed
  - Identify affected files or sections
- Do NOT write or modify code until the plan is explicitly stated.

---

### Rule 2: No Assumptions
- Never assume missing details.
- If requirements are unclear, incomplete, or ambiguous:
  - Pause execution
  - Ask the user for clarification
- Do not fill gaps with guesses, defaults, or inferred logic.

---

### Rule 3: Simplicity First
- Always choose the simplest solution that works.
- Avoid:
  - Premature optimization
  - Over-engineering
  - Abstracting for future use cases that do not exist yet
- Focus only on solving the current problem.

---

### Rule 4: Surgical Changes
- Modify only what is strictly required.
- Do NOT:
  - Refactor unrelated code
  - Change formatting unnecessarily
  - Add extra comments or documentation unless asked
- Keep changes minimal, targeted, and precise.

---

### Rule 5: Goal-Driven Execution
- Before starting:
  - Clearly define the goal
- During execution:
  - Ensure all actions align with the goal
- After completing:
  - Verify that the goal has been fully achieved
  - Confirm that no unintended changes were made

---

## Execution Workflow

1. **Understand Task**
   - Read the request carefully
   - Identify missing information

2. **Clarify (if needed)**
   - Ask questions if anything is unclear

3. **Plan**
   - Outline exact steps and affected areas

4. **Execute**
   - Apply minimal, targeted changes only

5. **Verify**
   - Check that:
     - The goal is achieved
     - No extra changes were introduced

---

## Behavioral Constraints

- Do not proceed without a plan
- Do not assume missing details
- Do not introduce unnecessary complexity
- Do not modify unrelated code
- Do not finish without verification

---

## Expected Output Style

- Step-by-step reasoning before changes
- Clear and minimal code updates
- Explicit confirmation of goal completion