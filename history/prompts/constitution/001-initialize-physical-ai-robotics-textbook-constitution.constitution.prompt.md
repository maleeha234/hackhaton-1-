---
id: 001
title: Initialize Physical AI & Robotics Textbook Constitution
stage: constitution
date: 2025-12-05
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: 001-calculator
user: unknown
command: /sp.constitution
labels: ["constitution", "initialization"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
- .specify/memory/constitution.md
tests:
null
---

## Prompt

```text
📘 Constitution Prompt for Spec-Kit-Plus — Project 1: Physical AI & Humanoid Robotics Textbook
1. Project Identity

Project Title: Physical AI & Humanoid Robotics — An AI-Native Technical Textbook
Project Type: Docusaurus-based AI-generated textbook
Tools:

Spec-Kit Plus for structured book development

Claude Code for iterative writing and code generation

Docusaurus for documentation website

GitHub Pages for deployment

Primary Goal:
Create a complete, production-ready textbook that teaches the Physical AI & Humanoid Robotics course as described in the official curriculum. The book must be suitable for AI-native learners, robotics students, engineers, and future instructors at Panaversity.

2. Tone, Style & Writing Standards

The AI must follow these stylistic rules consistently:

2.1 Tone

Clear, educational, and authoritative

Friendly but professional

Avoid unnecessary complexity

Avoid emotional or biased wording

2.2 Style

Use short paragraphs

Use diagrams, examples, code snippets, and tables where needed

Prefer step-by-step explanations

Ensure that every chapter has Learning Outcomes, Key Terms, Hands-On Exercises, and Review Questions

2.3 Formatting Requirements

Use Markdown compatible with Docusaurus:

# → Chapter

## → Sections

### → Subsections

Code blocks must specify language (e.g., ```python)

Provide images as Mermaid diagrams or textual descriptions

Use admonitions:

:::note

:::tip

:::warning

3. Book Structure Requirements

The book must follow this exact structure:

PART 1 — Foundations of Physical AI

Introduction to Physical AI

Embodied Intelligence & the Future of Humanoid Work

Sensors in Physical AI (LIDAR, RGB, IMU, F/T sensors)

Digital vs Physical AI: Moving Beyond Software-Only Agents

PART 2 — ROS 2: The Robotic Nervous System

ROS 2 Architecture

Nodes, Topics, Services, and Actions

Building Python ROS 2 Packages

Launch Files & Parameter Management

URDF for Humanoids

PART 3 — The Digital Twin: Gazebo & Unity

Introduction to Gazebo

URDF/SDF Simulation Pipelines

Physics Simulation Basics

Sensor Simulation

Unity for High-Fidelity Visualization

PART 4 — The AI Brain: NVIDIA Isaac Platform

Introduction to Isaac SDK & Isaac Sim

Photorealistic Simulation

Synthetic Data Generation

Isaac ROS Perception + VSLAM

Nav2 for Humanoid Path Planning

Reinforcement Learning + Sim-to-Real Transfer

PART 5 — Vision-Language-Action (VLA) Robotics

Voice-to-Action with Whisper

LLMs for Cognitive Planning

VLA Pipelines

Natural Language → ROS Action Graph

PART 6 — Humanoid Robotics & Interaction

Humanoid Kinematics & Dynamics

Bipedal Walking, Balance, and Control

Manipulation & Grasping

Human-Robot Interaction

PART 7 — Capstone: The Autonomous Humanoid

Requirements & Architecture

Obstacle Navigation

Object Recognition & Manipulation

Final Integration Guide

Evaluation Rubric & Testing Procedures

4. Content Requirements

Every section must include:

✔ Clear definitions
✔ Real-world analogies
✔ Practical code examples (Python ROS 2 preferred)
✔ Step-by-step tutorials
✔ Hands-on lab exercises
✔ Visual explanations (Mermaid diagrams)
✔ Review questions
✔ A mini-project or assignment

The book must be self-contained, enabling a student to master the full course.

5. Technical Requirements
5.1 ROS 2 Examples

All ROS nodes must be valid rclpy examples

Provide working launch files

Provide URDF snippets

5.2 Gazebo/Isaac Sim

Provide correct commands for Ubuntu 22.04

Use Isaac Sim's USD workflow accurately

5.3 VLA
```

## Response snapshot

The project constitution has been initialized to version 0.1.0. This is the initial version for the "Physical AI & Humanoid Robotics — An AI-Native Technical Textbook" project.

The following templates require manual review and updates to align with the new constitution principles:
*   .specify/templates/plan-template.md
*   .specify/templates/spec-template.md
*   .specify/templates/tasks-template.md
*   .specify/templates/commands/*.md

Suggested commit message: `docs: initialize constitution to v0.1.0 (physical AI & robotics textbook)`

## Outcome

- ✅ Impact: Constitution for Physical AI & Humanoid Robotics textbook initialized.
- 🧪 Tests: N/A
- 📁 Files: 1 file created/modified: .specify/memory/constitution.md
- 🔁 Next prompts: Review and update dependent templates (plan, spec, tasks, commands).
- 🧠 Reflection: Successfully initialized the project constitution based on user-provided details for a textbook project. Adapted the general constitution template to fit the specific needs of a book.

## Evaluation notes (flywheel)

- Failure modes observed: create-phr.sh script failed to locate template, requiring agent-native PHR creation.
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment: Ensure PHR script correctly identifies template paths or improve agent's fallback mechanism for PHR creation.
