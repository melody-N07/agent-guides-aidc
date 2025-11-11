# Contributing to Agent Guides

Thank you for your interest in contributing agent guides for Microsoft partners! This document provides guidelines for creating and submitting new agent guides.

## Prerequisites

Before creating a new agent guide, ensure you have:
- A working Copilot Studio Lite agent that has been tested and validated
- Clear documentation of the agent's purpose and use cases
- All necessary knowledge sources properly documented
- A set of starter prompts that demonstrate the agent's capabilities

## Agent Guide Structure

Each agent guide must follow this standardized structure:

### Folder Naming
- Use lowercase letters with hyphens (kebab-case)
- Be descriptive and specific (e.g., `technical-support-agent`, `sales-assistant`)
- Avoid generic names

### Required Files

#### 1. README.md
The README should include:
- **Agent Name**: Clear, descriptive name
- **Purpose**: What problem does this agent solve?
- **Target Use Cases**: Specific scenarios where this agent excels
- **Prerequisites**: Any required setup or access
- **Setup Instructions**: Step-by-step deployment guide
- **Configuration Notes**: Any customization options
- **Testing Guide**: How to verify the agent is working correctly

#### 2. system-instructions.md
This file contains the complete system prompt for the agent:
- Write clear, comprehensive instructions
- Define the agent's role, capabilities, and limitations
- Include any specific behavioral guidelines
- Specify output format requirements if applicable
- Use markdown formatting for readability

**Template Structure:**
```markdown
# System Instructions for [Agent Name]

## Role and Purpose
[Define what the agent does]

## Core Capabilities
[List key capabilities]

## Interaction Guidelines
[How the agent should interact]

## Constraints and Limitations
[What the agent should not do]

## Output Format
[Expected response format]
```

#### 3. knowledge-sources.md
Document all knowledge sources used by the agent:
- **Type**: Files, URLs, SharePoint sites, etc.
- **Description**: What each source provides
- **Access Requirements**: Any permissions needed
- **Update Frequency**: How often sources should be refreshed
- **Format**: File types and structure

**Template Structure:**
```markdown
# Knowledge Sources for [Agent Name]

## Overview
[Brief description of knowledge sources]

## Required Sources

### [Source Name 1]
- **Type**: [File/URL/SharePoint/etc.]
- **Description**: [What this source provides]
- **Location**: [Where to find it]
- **Format**: [File type/structure]
- **Access Requirements**: [Permissions needed]
- **Update Frequency**: [How often to update]

### [Source Name 2]
[Repeat for each source]

## Optional Sources
[Additional sources that can enhance the agent]

## Setup Instructions
[How to upload/configure these sources in Copilot Studio Lite]
```

#### 4. starter-prompts.md
Provide 5-10 example prompts that demonstrate the agent's capabilities:
- Cover different use cases
- Range from simple to complex queries
- Show the variety of tasks the agent can handle
- Include expected outcome descriptions

**Template Structure:**
```markdown
# Starter Prompts for [Agent Name]

These prompts help users understand the agent's capabilities and get started quickly.

## Basic Queries

### Prompt 1: [Category]
**User Input:**
```
[Example prompt]
```
**Expected Outcome:** [What the agent should do]

### Prompt 2: [Category]
[Repeat pattern]

## Advanced Queries

### Prompt 5: [Category]
[More complex examples]

## Tips for Creating Your Own Prompts
[Guidance for users to create effective prompts]
```

## Submission Process

1. **Create Your Agent Guide**:
   - Create a new folder in the repository root
   - Add all required files following the templates
   - Ensure all content is complete and accurate

2. **Test Your Guide**:
   - Follow your own instructions to deploy the agent
   - Verify all starter prompts work as expected
   - Have a colleague review for clarity

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
   - [ ] starter-prompts.md includes 5-10 examples
   - [ ] Agent has been tested successfully
   - [ ] No sensitive information is included

## Quality Guidelines

### Content Quality
- **Clarity**: Write in clear, concise language
- **Completeness**: Include all necessary information
- **Accuracy**: Ensure technical accuracy
- **Examples**: Provide concrete, realistic examples

### Security and Privacy
- **No Secrets**: Never include API keys, passwords, or tokens
- **No PII**: Don't include personally identifiable information
- **Public Data Only**: Use only publicly available knowledge sources or provide clear instructions for obtaining proprietary sources
- **Customer Data**: Never include actual customer data

### Documentation Standards
- Use proper markdown formatting
- Include code blocks where appropriate
- Use bullet points and numbered lists for readability
- Add headers to organize content
- Check spelling and grammar

## Review Process

All submissions will be reviewed for:
1. **Completeness**: All required files and sections present
2. **Quality**: Clear, accurate, and well-documented
3. **Security**: No sensitive information included
4. **Functionality**: Agent guide can be successfully deployed
5. **Value**: Provides clear value to Microsoft partners

## Getting Help

If you have questions about contributing:
- Open an issue with the `question` label
- Contact the Microsoft Partner Solutions AI team
- Review existing agent guides as examples

## Code of Conduct

By contributing, you agree to maintain a professional and collaborative environment. All contributions should:
- Be respectful and inclusive
- Focus on helping Microsoft partners succeed
- Maintain high quality standards
- Follow all security and privacy guidelines

Thank you for contributing to help Microsoft partners deploy effective AI agents!
