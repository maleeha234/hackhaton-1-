---
id: 002
title: Physical AI & Humanoid Robotics Textbook Specification
stage: spec
date: 2025-12-05
surface: agent
model: claude-sonnet-4-5-20250929
feature: physical-ai-robotics-textbook
branch: 001-calculator
user: unknown
command: /sp.specify
labels: ["specification", "textbook"]
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
✅ Spec-Kit Plus Specification Prompt (Project 1 — Physical AI & Humanoid Robotics Textbook)
Fully aligned with Hackathon I requirements, Claude Code workflow, and Panaversity publishing standards.
📘 Project Title

Physical AI & Humanoid Robotics — An AI-Native Technical Textbook

🎯 Project Objective

Create a complete, production-ready AI-native textbook for the course Physical AI & Humanoid Robotics, using:

Spec-Kit Plus (for specification-driven writing)

Claude Code (for automated structured chapter generation)

Docusaurus (for website/book deployment)

GitHub Pages (for public publishing)

This book must be fully AI-agent friendly, structured, modular, and compliant with Panaversity’s standards.

📚 Context & Vision

This textbook will serve as the official learning resource for the Physical AI & Humanoid Robotics Quarter at Panaversity.
It enables students to build robotic systems that combine:

Embodied intelligence

ROS 2

Gazebo

Unity

NVIDIA Isaac Sim

Vision-Language-Action systems

A full humanoid robot capstone

The textbook must be AI-native, meaning:

Chapters are atomic and machine-readable

Can be consumed by LLM agents

Optimized for search, summarization, and structured queries

Contains explicit outcomes, steps, and technical accuracy

📦 Core Deliverables

The Spec-Kit Plus project must produce:

1. A complete Docusaurus book

/docs folder containing all chapters

Sidebar + navigation structure

Preface, overview, glossary, quizzes, labs

Code examples and diagrams

2. Spec documents

spec.md (this file — master constitution)

Chapter specs

Component specs

Auto-generated content using Claude Code

3. Deployment

Fully deployable GitHub Pages site

Config files (docusaurus.config.js, sidebar.js)

4. Capstone Implementation Guide

Full walkthrough for the final humanoid robot project

🧭 Course Alignment

This textbook must strictly follow the course structure:

📖 Book Macro-Structure (Top-Level Parts)
Part I — Introduction to Physical AI

What is Physical AI

Embodied intelligence

Robots vs digital AI

Humanoid robotics overview

Sensor systems (LiDAR, IMU, Depth, FT sensors)

Part II — ROS 2 Fundamentals

ROS 2 architecture (Nodes, Topics, Services, Actions)

rclpy for Python AI Agents

ROS 2 package building

URDF for humanoids

Launch files and params

Part III — Simulation with Gazebo & Unity

Gazebo setup

URDF/SDF simulation

Physics, gravity, collision

Sensor simulation

Unity high-fidelity rendering

Digital twin concepts

Part IV — NVIDIA Isaac Platform

Isaac Sim

Isaac ROS

VSLAM

Nav2 navigation

Reinforcement learning

Sim-to-real transfer

Part V — Humanoid Robotics Engineering

Humanoid kinematics

Dynamics

Biped locomotion

Balance control

Manipulation + grasping

HRI (Human-Robot Interaction)

Part VI — Vision-Language-Action Robotics

Whisper voice input

GPT/LLM planning

Natural language → ROS 2 task sequences

Multimodal perception

Part VII — Capstone Project

A simulated humanoid robot that:

Receives voice commands

Plans actions using GPT

Navigates around obstacles

Perceives objects

Manipulates a target item

Runs end-to-end in Isaac Sim + ROS 2

🧪 Assessments (Must Be Included in Book)

ROS 2 package development

Gazebo simulation build

Isaac perception pipeline

VLA integration mini-project

Capstone humanoid robot implementation

🔧 Technical Requirements for All Chapters

Every chapter must:

Structure

Begin with learning objectives

End with summary + review questions

Include code blocks

Include diagrams (Mermaid, SVG)

Provide step-by-step instructions

Be broken into well-defined sections

Contain glossary terms

AI-Agent Friendly

Use atomic, consistent headings

Avoid ambiguous language

Provide structured definitions

Use tables where possible

Keep consistent terminology

Code Requirements

ROS 2 examples must run on Humble or Iron

Isaac examples must be valid for Isaac Sim 4.x

Unity examples must use Unity 6

Python code must follow PEP-8

ROS launch files must be real and testable

🖥️ Hardware Requirements (Must Include Sections & Diagrams)
Digital Twin Workstation

RTX 4070 Ti minimum (ideal 4090)

64 GB RAM

Ubuntu 22.04

Edge AI Kit

Jetson Orin Nano / NX

RealSense D435i

USB IMU

ReSpeaker Mic

Robot Options

Unitree Go2 (budget)

Unitree G1 / Robotis OP3 (humanoid)

Premium lab: Unitree G1 humanoid

Cloud Option

AWS g5 or g6e instances

Omniverse Cloud instance for Isaac

📂 Folder Structure (Required for Generation)
project-root/
  spec.md
  chapters/
    01-intro.md
    02-physical-ai.md
    03-ros2-basics.md
    04-gazebo.md
    05-unity.md
    06-isaac.md
    07-humanoids.md
    08-vla.md
    09-capstone.md
  docusaurus/
    docs/
    src/
    static/
  assets/
  scripts/

🤖 Claude Code Guidelines

Claude must follow:

Never invent modules not included in this spec

All content must be deterministic and reproducible

Always follow chapter specs

Use structured headings strictly

Generate high-level drafts → refine → finalize

Maintain consistent vocabulary across entire book

📌 Acceptance Criteria (Hackathon Evaluation)

Your book will be accepted only if:

Matches all modules exactly

Docusaurus site builds without errors

Follows Spec-Kit Plus framework

Contains real ROS 2 / Isaac / Unity code

Capstone is fully documented end-to-end

Content quality equals university-level textbook

Everything deploys to GitHub Pages

AI-native structure is preserved

🚀 Final Goal

Produce a full AI-native textbook that enables students to learn:

Physical AI

Humanoid robotics

Simulation engineering

ROS 2 + Isaac + Unity

Vision-Language-Action robotics

…culminating in a fully autonomous humanoid embodied agent.
```

## Response snapshot

I have received the detailed specification for the "Physical AI & Humanoid Robotics — An AI-Native Technical Textbook" project. This specification outlines the project objective, context, core deliverables, course alignment, macro-structure, assessments, technical requirements, hardware requirements, folder structure, Claude Code guidelines, and acceptance criteria. I will now proceed to process this specification and ensure all future work aligns with these guidelines.

## Outcome

- ✅ Impact: Project specification for Physical AI & Humanoid Robotics textbook received and acknowledged.
- 🧪 Tests: N/A
- 📁 Files: None directly modified by this specific tool call, but constitution was updated previously.
- 🔁 Next prompts: Proceed with planning and implementation based on the provided specification.
- 🧠 Reflection: Successfully captured the user's detailed specification for the textbook project. This will serve as the guiding document for all subsequent development, ensuring alignment with project goals and standards. The prompt includes comprehensive details across various aspects of the textbook creation.

## Evaluation notes (flywheel)

- Failure modes observed: N/A
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment: Begin creating the project's plan based on this specification.
