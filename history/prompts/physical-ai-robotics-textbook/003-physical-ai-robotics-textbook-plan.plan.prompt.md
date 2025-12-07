---
id: 003
title: Physical AI & Humanoid Robotics Textbook Plan
stage: plan
date: 2025-12-05
surface: agent
model: claude-sonnet-4-5-20250929
feature: physical-ai-robotics-textbook
branch: 001-calculator
user: unknown
command: /sp.plan
labels: ["plan", "textbook"]
links:
  spec: specs/physical-ai-robotics-textbook/spec.md
  ticket: null
  adr: null
  pr: null
files:
- specs/physical-ai-robotics-textbook/plan.md
tests:
null
---

## Prompt

```text
✅ Spec-Kit Plus – PLAN PROMPT (Project 1: Physical AI & Humanoid Robotics Textbook)

Copy & paste the entire prompt into speckit-plan.yaml or plan.md depending on your setup.

project:
  name: "Physical AI & Humanoid Robotics Textbook"
  description: >
    Create a complete Docusaurus-based AI-native textbook teaching Physical AI & Humanoid Robotics.
    The book must follow the course outline provided by Panaversity and integrate ROS 2, Gazebo,
    Unity, NVIDIA Isaac, VSLAM, and Vision-Language-Action Systems. Use Spec-Kit Plus and
    Claude Code to generate the entire project, and deploy it to GitHub Pages.

goals:
  - Write a unified, AI-native textbook for the Physical AI & Humanoid Robotics course.
  - Build the book using Docusaurus (latest version).
  - Use Claude Code + Spec-Kit Plus for structured, automated writing.
  - Deploy the book on GitHub Pages.
  - Follow the provided 13-week module outline.
  - Produce a professional, industry-grade technical curriculum.
  - Include examples, code listings, diagrams, lab instructions, and project walkthroughs.
  - Provide guidance on hardware setups: RTX workstation, Jetson kits, robots.
  - Ensure AI agent–friendly design (semantic structure, embeddings-ready content).

constraints:
  - Must strictly follow the course modules and weekly breakdown provided.
  - Must include all robotics stacks: ROS 2, Gazebo, Unity, Isaac Sim, Nav2, Whisper, VLA.
  - Must generate a full textbook with chapters, sections, hands-on labs, and capstone project.
  - Must be deployable on GitHub Pages without errors.
  - Must be written in clean, structured Markdown compatible with Docusaurus.
  - Must avoid plagiarism—write original content.
  - Must ensure clarity for beginners while maintaining technical rigor.

deliverables:
  - A complete Docusaurus project folder.
  - `/docs` folder containing all textbook chapters.
  - `sidebar.js` fully configured.
  - Homepage with course summary and CTAs.
  - A 13-week structured textbook with modules, labs, and quizzes.
  - Hardware recommendation pages.
  - Capstone guide: Autonomous Humanoid with VLA + Navigation + Manipulation.
  - GitHub repo with working deployment pipeline (GitHub Actions).
  - Published live book on GitHub Pages.

outline:
  textbook:
    - Preface
      - Why Physical AI Matters
      - The Era of Embodied Intelligence
      - Industry Landscape

    - Chapter 1: Introduction to Physical AI
      - What is Physical AI?
      - Embodied vs Digital AI
      - Sensors overview

    - Chapter 2: Robotics Foundations
      - Kinematics, Dynamics, Control
      - Sensor Fusion
      - Actuators and motors

    - Chapter 3: ROS 2 Fundamentals
      - Nodes, Topics, Services, Actions
      - rclpy basics
      - ROS 2 Package Development
      - Launch files and parameters
      - URDF for Humanoids

    - Chapter 4: Simulation with Gazebo
      - World building
      - Gravity, physics, collisions
      - SDF vs URDF
      - Sensor simulation (Lidar, IMU, RGB-D)

    - Chapter 5: Simulation & Interaction in Unity
      - Unity Robotics Hub
      - High-fidelity rendering
      - Human-in-the-loop interaction

    - Chapter 6: NVIDIA Isaac Platform
      - Isaac Sim overview
      - Synthetic data generation
      - Reinforcement learning
      - Isaac ROS pipelines (VSLAM, Nav2)

    - Chapter 7: Humanoid Robotics
      - Bipedal locomotion
      - Balancing systems
      - Manipulation and grasping
      - Human-robot natural interaction

    - Chapter 8: Vision-Language-Action (VLA)
      - LLM + Robotics connection
      - Whisper for voice commands
      - Planning with LLMs
      - Converting natural language to ROS actions

    - Chapter 9: Hardware Setup & Labs
      - RTX workstation requirements
      - Jetson Orin Setup
      - RealSense Setup
      - Humanoid robot options (Go2, G1, OP3, Hiwonder)

    - Chapter 10: Capstone Project
      - Autonomous Humanoid Pipeline
      - Voice → Plan → Perception → Navigation → Manipulation
      - Testing in Isaac Sim
      - Optional sim-to-real deployment

tasks:
  foundational:
    - Initialize a new Docusaurus project using Claude Code.
    - Configure GitHub repository + actions for deployment.
    - Add Spec-Kit Plus folder structure.

  writing:
    - Generate each chapter in Markdown using Claude Code + Spec-Kit templates.
    - Add code examples for ROS 2, URDF, Gazebo, Isaac Sim, VLA, Whisper.
    - Add diagrams (ASCII or generated images if allowed by agents).
    - Add lab exercises and weekly quizzes.
    - Add capstone walkthrough with step-by-step instructions.

  integration:
    - Connect chapters to sidebar.
    - Optimize Markdown for AI-native reading.
    - Ensure smooth navigation.

  testing:
    - Build locally via `npm run build`.
    - Fix broken links, sidebar issues, markdown formatting.
    - Deploy to GitHub Pages and validate live website.

tools:
  - Spec-Kit Plus for planning, outlining, and structuring.
  - Claude Code for writing and refactoring entire Docusaurus project.
  - Git + GitHub Actions for deployment.
  - Docusaurus for rendering the textbook.
  - Optional image-generation agents for diagrams.

deployment:
  steps:
    - Create GitHub Repo
    - Create Docusaurus site via Claude Code
    - Commit all files
    - Configure `docusaurus.config.js` for GitHub Pages
    - Push to GitHub
    - Enable Pages
    - Verify deployment
    - Share final live URL


✅ Your Plan Prompt is Ready

If you want, I can also generate:

✅ speckit-spec.yaml
✅ folder structure for the book
✅ Full Docusaurus skeleton
✅ First 2 chapters fully written
✅ GitHub Actions workflow
✅ Capstone project chapter/sp.plan
```

## Response snapshot

The implementation plan has been created and saved to `specs/physical-ai-robotics-textbook/plan.md`.

## Outcome

- ✅ Impact: Project plan for Physical AI & Humanoid Robotics textbook created.
- 🧪 Tests: N/A
- 📁 Files: 1 file created: specs/physical-ai-robotics-textbook/plan.md
- 🔁 Next prompts: Proceed with task generation based on the plan.
- 🧠 Reflection: Successfully generated a detailed implementation plan based on the user's prompt, incorporating all specified goals, constraints, deliverables, and technical requirements. The plan now provides a clear roadmap for the textbook's development.

## Evaluation notes (flywheel)

- Failure modes observed: N/A
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment: Generate tasks based on the created plan.
