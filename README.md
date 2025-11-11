# Agent Guides for Copilot Studio Lite

Agent replication guides for Microsoft Partners to recreate Microsoft-developed Copilot Studio Lite agents.

## Overview

This repository contains ready-to-use agent guides designed to help Microsoft partners quickly replicate and deploy specialized Copilot Studio Lite agents for their customers. Each agent guide provides all the necessary components to set up a functional agent.

## Repository Structure

Each agent guide is contained in its own folder with the following structure:

```
agent-name/
├── README.md                 # Overview and setup instructions for this agent
├── system-instructions.md    # Declarative agent system instructions (prompt)
├── knowledge-sources.md      # Documentation and links to knowledge sources
├── knowledge-sources/        # Files required for upload
└── starter-prompts.md        # Example prompts to get started with the agent
```

## Available Agent Guides

Browse the folders in this repository to see available agent guides. Each folder represents a complete agent implementation.

## How to Use an Agent Guide

1. **Choose an Agent**: Browse the available agent folders and select the one that fits your needs
2. **Review the README**: Each agent folder contains a README.md with specific setup instructions
3. **Gather Components**: Collect the system instructions, knowledge sources, and starter prompts
4. **Deploy to Copilot Studio Lite**:
   - Create a new agent in Copilot Studio Lite (copilot.microsoft.com)
   - Copy the system instructions from `system-instructions.md` into the agent's prompt configuration
   - Upload or link the knowledge sources as specified in `knowledge-sources.md` and/or uploaded to `knowledge-sources/`
   - Add the starter prompts from `starter-prompts.md` to help users get started
5. **Test and Customize**: Test the agent with the provided starter prompts and customize as needed for your specific use case

## Creating a New Agent Guide

If you're contributing a new agent guide, please follow the template structure:

1. Create a new folder with a descriptive, kebab-case name (e.g., `ai-discovery-cards-agent`)
2. Include all required files:
   - `README.md` - Agent overview and setup instructions
   - `system-instructions.md` - Complete system prompt
   - `knowledge-sources.md` - Knowledge source documentation
   - `knowledge-sources/` (Optional) Files for upload
   - `starter-prompts.md` - Example prompts
3. Follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md)

## Support

For questions or issues:
- Open an issue in this repository
- Contact the Microsoft Partner Solutions AI team

## License

Please refer to the LICENSE file in this repository for usage terms.
