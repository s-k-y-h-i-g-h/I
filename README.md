# I - Intelligence-based Development Framework

A framework that compiles natural language requirements into executable products, leveraging agent coordination and iterative verification—like GCC for intelligence-driven development.

## Vision

"I" (pronounced "eye" or "intelligence") is a development framework that transforms structured natural language documents into working software products. It treats intelligence—both human and artificial—as the primary compilation mechanism, using coordinated agents to interpret requirements, implement features, verify correctness, and produce deployable artifacts.

Just as GCC translates C source code into machine executables through preprocessing, compilation, assembly, and linking, "I" translates requirement documents into products through stages of clarification, agent-based development, verification, iteration, and packaging.

## Collaboration Note

This project emerged from collaborative exploration between the user and Ember (an OpenClaw assistant). The user provided the core vision, direction, and key insights, while Ember helped elaborate, structure, document, and explore implications of these ideas through sustained dialogue and joint thinking.

## Core Concepts

### 1. Input: Structured Natural Language
- Requirements, designs, and specifications are written as natural language documents in a well-organized Git repository
- Directory structure and labeling provide semantic context (e.g., `/requirements/`, `/design/`, `/test-cases/`)
- Flexible "language"—the system adapts to various documentation styles while extracting actionable intent

### 2. Processing: Agent-Coordinated Development
Leverages OpenClaw's agent architecture for specialized, coordinated work:
- **Requirement Interpreter Agents**: Clarify and refine specifications through dialogue with the user
- **Design Agents**: Translate clarified requirements into technical designs and architectures
- **Implementation Agents**: Specialized subagents (frontend, backend, testing, etc.) that write code
- **Verification Agents**: Validate implementations against requirements using tests, simulations, and review
- **Orchestrator Agent**: Manages the workflow, handles dependencies, and drives the iteration loop

### 3. Iterative, Interactive Process
Unlike traditional linear compilers, "I" embraces iteration:
1. Development environment is spawned
2. User and LLM collaborate to clarify requirements and design
3. Refined specs are passed to subagents for implementation
4. Results are published for user review
5. Feedback drives refinement in subsequent cycles
6. Process continues until product meets acceptance criteria

### 4. Output: Packaged Products
- Platform-specific executables (ELF for Linux, Win32 for Windows, etc.)
- Bundled with all relevant resources (images, configuration files, etc.)
- Distributed as installers (packages, DMGs, MSIs, etc.) ready for deployment
- Includes verification artifacts and documentation

### 5. Systemic Self-Similarity
The framework embodies the same structural patterns observed in biological homeostasis and early warning systems:
- Sensors → Requirement gathering and clarification
- Processor → Agent coordination and implementation
- Actor → Code generation and execution
- Feedback → Verification, user review, and iterative refinement

## Relationship to ArchClaw

"I" is designed to be built **on top of ArchClaw**, which provides:
- Integrated OS environment with OpenClaw core pre-installed
- Skill system for specialized development agents (e.g., "web-dev", "test-writer" skills)
- Update mechanisms for framework and skill evolution
- Cross-platform deployment targets (WSL2, chroot/containers, native Arch)
- Automated backup and continuity systems

By building on ArchcClaw, "I" inherits a stable, intelligent platform that handles environmental concerns, allowing the framework to focus purely on the requirement-to-product translation process.

## Development Philosophy

"I" represents a belief that software creation should be:
- **Intelligence-centric**: Human insight and machine capability work in continuous dialogue
- **Verification-driven**: Correctness is checked early and often, not just at the end
- **Iterative and exploratory**: Requirements evolve through implementation and feedback
- **Agent-coordinated**: Specialized intelligences collaborate rather than relying on monolithic effort
- **Product-focused**: The goal is deployable, working software, not just code

## Getting Started

See [DESIGN.md](DESIGN.md) for detailed architecture and implementation plans.

## Repository Structure

- `docs/` - Detailed design documents
- `src/` - Framework source code (agent orchestrators, interpreters, etc.)
- `packages/` - Skill packages for specialized development agents
- `templates/` - Example project structures and requirement templates
- `examples/` - Sample projects demonstrating the framework
- `installer/` - Platform-specific installer logic

---
*I: Where natural language requirements are compiled into working software through coordinated intelligence.*