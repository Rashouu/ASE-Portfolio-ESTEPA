# ASE Portfolio

**Name:** Estepa, Jose Emmanuel J.  
**Course:** CPELX230-330 (Agentic Software Engineering)

This repository is my portfolio for the Agentic Software Engineering course. It holds my activities, reflections, and notes for the term.

## Course Introduction

Agentic Software Engineering looks at how to build software that includes AI agents: programs that can perceive their environment, make decisions, and take actions toward a goal. The course combines standard software engineering (Sommerville), Agile development with Scrum, version control with Git, intelligent agent concepts (Russell and Norvig), and responsible AI practices based on the NIST AI Risk Management Framework.

## Personal Learning Goals

1. Understand how AI agents work and how they differ from traditional rule-based programs.
2. Get comfortable using Git and GitHub for everyday work: commits, branches, pull requests, and clear commit messages.
3. Apply Scrum in a team project, including sprint planning, reviews, and retrospectives.
4. Learn to identify and reduce risks in AI systems, especially around security, privacy, and bias.
5. Build at least one small agent-based project and document it properly in this portfolio.

## Reflection from Part A: Concept Analysis

### i. What is Agentic Software Engineering?
Agentic Software Engineering (ASE) is the practice of building, testing, and maintaining software that contains AI agents, and of using AI agents as helpers in the development process itself. Russell and Norvig define an agent as anything that perceives its environment and acts on it to reach a goal. ASE takes the activities Sommerville lists for any software process (specification, design, validation, and evolution) and applies them to systems whose behavior is partly decided at runtime by the agent.

### ii. How does an AI agent differ from a traditional software application?
A traditional application follows rules a programmer wrote in advance. The same input gives the same output, and every path can be traced in the code. An AI agent is given a goal and picks its own steps to reach it. It can call tools, read new information, and change its plan based on what it observes. Its output may differ between runs, and it can do things the developer never coded line by line. This makes it more flexible, but also harder to test and predict.

### iii. Why are Agile methods appropriate for developing agentic systems?
You usually cannot fully specify an agent's behavior upfront. You learn how it behaves by running it on real tasks. Scrum is built on empiricism (transparency, inspection, and adaptation), which matches this situation. Short sprints let the team test the agent often, find problems early, and adjust prompts, tools, and guardrails based on evidence. Sprint reviews and retrospectives give regular checkpoints to confirm the agent still does what stakeholders want. Version control such as Git supports this by recording every change to code, prompts, and settings, so the team can compare versions and roll back a bad change.

### iv. What risks should developers consider when deploying autonomous AI agents?
Agents can give wrong answers with confidence (hallucinations). They can take actions with real effects, such as deleting files, sending messages, or making purchases. They are open to security attacks like prompt injection, and they become more dangerous when given wider permissions than they need. They may leak personal data or make biased decisions. It can also be unclear who is accountable when an agent causes harm. The NIST AI Risk Management Framework adds that AI risks are hard to measure and can change as the data or the environment changes.

### v. Why is human oversight important in AI-enabled applications?
An agent does not understand consequences or values the way a person does, and it can be wrong without knowing it. A human reviewing high-impact actions can catch mistakes before they cause damage and keeps a real person accountable for the outcome. The Govern function of the NIST AI RMF calls for clear roles and responsibilities for this. In practice, oversight means approval steps for risky actions, logs that someone actually reads, and a way to stop the agent at any time.
