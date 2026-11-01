# Problem Solving Coach

**Start with one problem. Understand the concepts. Learn a method you can reuse.**

[简体中文](README.md) · English

Problem Solving Coach is a Codex skill for university STEM students. Given a problem, it explains the relevant concepts and reasoning step by step, then extracts a method that can be applied to related questions.

> Starting point → Concepts → Method choice → Worked solution → Transfer practice → Review

## What it does

- **Identify the essentials:** Separate the given conditions, the goal, core concepts, and useful related ideas.
- **Start with the approach:** Identify the first step before the theory, then explain method choice, its limits, and each important step.
- **Build a reusable approach:** Summarize recognition cues, steps, assumptions, shortcuts, and common mistakes.
- **Practice transfer:** By default, receive one consolidation problem and one exam-style variation, both with worked solutions.
- **Adapt to your request:** Ask for a hint, a simpler explanation, feedback on your work, or explanations based on your course materials.
- **Adjust the depth:** Keep simple problems concise, develop complex derivations, and organize large sets into tracked batches.

The skill covers university STEM subjects such as circuits, digital and analog electronics, signals and systems, digital signal processing, communications, mathematics, C, and FPGA/VHDL.

## Quick start

Clone this repository into the Codex skills directory:

```bash
git clone https://github.com/Ryan-2727/problem-solving-coach.git ~/.codex/skills/problem-solving-coach
```

If Codex uses a custom skills directory, replace the destination with its `problem-solving-coach` folder. Start a new Codex session and provide a problem:

```text
Use $problem-solving-coach to analyze this problem and focus on a reusable solution method:
[Paste the problem or attach an image]
```

You can also request only the approach, ask for a step to be explained again, or submit your own solution for feedback.

## Default workflow

| Step | What to expect |
| --- | --- |
| 1. Problem framing | Give the starting point first, then identify conditions, goal, and problem type |
| 2. Concepts | Explain the core ideas and closely related concepts |
| 3. Exam patterns | Explore relevant variations, study priorities, and pitfalls |
| 4. Worked solution | Explain method choice and assumptions, derive the answer, and check it |
| 5. Solving template | Extract reusable steps, techniques, and limits |
| 6. Transfer practice | Present a similar problem and an exam-style variation |
| 7. Worked practice | Explain both solutions and summarize key points for review |

The depth and format adjust to the problem and your explicit instructions, with repeated ideas explained in detail only once. For large sets, the skill lists coverage and works in batches when needed, tracking completed and remaining problems. It asks for missing essential information rather than inventing it, and grounds claims about exam emphasis in available course materials.

## Repository structure

```text
├── SKILL.md           # Teaching instructions and workflow
├── agents/openai.yaml # Codex display metadata and example prompt
├── README.md          # Chinese documentation
└── README.en.md       # English documentation
```

The skill explains primarily in Chinese and retains important English terminology where helpful. Check definitions, conventions, and calculations against your course materials.
