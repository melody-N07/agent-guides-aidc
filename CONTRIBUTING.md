# Contributing to Agent Guides

Thank you for your interest in contributing agent guides for Microsoft partners! This document provides guidelines for creating and submitting new agent guides.

## Prerequisites

Before creating a new agent guide, ensure you have:
- A working Copilot Studio Lite agent that has been tested and validated
- Clear documentation of the agent's purpose and use cases
- All necessary knowledge sources properly documented
- A set of suggested prompts that demonstrate the agent's capabilities

## Agent Guide Structure

Each agent guide must follow this standardized structure below. For easy creation, copy and rename the `agent-guide-template/` folder

### Folder Naming
- Use lowercase letters with hyphens (kebab-case)
- Be descriptive and specific (e.g., `ai-discovery-cards-agent`)
- Avoid generic names

### Required Files

#### 1. README.md
The README should include:
- **Agent Name**: Clear, descriptive name
- **Purpose**: What problem does this agent solve?
- **Target Use Cases**: Specific scenarios where this agent excels

#### 2. system-instructions.md
This file contains the complete system prompt for the agent:
- Write clear, comprehensive instructions
- Define the agent's role, capabilities, and limitations
- Include any specific behavioral guidelines
- Specify output format requirements if applicable
- Use markdown formatting, and capture prompt in text block to preserve markdown for copy/paste

#### 3a. knowledge-sources.md
Document all knowledge sources used by the agent:
- **Type**: Files, URLs, Outlook, Teams, etc.
- **Description**: What each source provides

#### 3b. knowledge-sources/ folder (optional as needed)
Folder containing all files needed for upload (.txt, .docx, .pptx, .pdf, etc)
- **Public Data Only**: Use only publicly available knowledge sources or provide clear instructions for obtaining proprietary sources

#### 4. suggested-prompts.md
Provide 3 or more example prompts that demonstrate the agent's capabilities:
- Cover different use cases
- Range from simple to complex queries
- Show the variety of tasks the agent can handle

## Submission Process

1. **Create Your Agent Guide**:
   - Create a new folder in the repository root
   - Add all required files following the templates
   - Ensure all content is complete and accurate

2. **Test Your Guide**:
   - Follow your own instructions to deploy the agent
   - Verify all suggested prompts work as expected

3. **Submit a Pull Request**:
   - Fork the repository
   - Add your agent guide folder
   - Create a pull request with a clear description
   - Include any special considerations or notes

4. **Pull Request Checklist**:
   - [ ] Folder name follows kebab-case convention
   - [ ] All four required files are present
   - [ ] README.md is complete and clear
   - [ ] system-instructions.md contains the full prompt
   - [ ] knowledge-sources.md documents all sources
   - [ ] suggested-prompts.md includes 3+ examples
   - [ ] Agent has been tested successfully
   - [ ] No sensitive information is included

## Review Process

All submissions will be reviewed for:
1. **Completeness**: All required files and sections present
2. **Quality**: Clear, accurate, and well-documented
3. **Security**: No sensitive information included
5. **Value**: Provides clear value to Microsoft partners

## Getting Help

If you have questions about contributing:
- Open an issue with the `question` label
- Contact Melody Yin or Lauren Tran
- Review existing agent guides as examples

## Code of Conduct

By contributing, you agree to maintain a professional and collaborative environment. All contributions should:
- Be respectful and inclusive
- Focus on helping Microsoft partners succeed
- Maintain high quality standards
- Follow all security and privacy guidelines

Thank you for contributing to help Microsoft partners deploy effective AI agents!
