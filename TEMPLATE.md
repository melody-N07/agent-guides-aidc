# Agent Guide Template Structure

This document provides a quick reference for the structure and content of each agent guide in this repository.

## Folder Structure

Each agent guide should follow this structure:

```
agent-name/
├── README.md
├── system-instructions.md
├── knowledge-sources.md
└── starter-prompts.md
```

## File Descriptions

### README.md
**Purpose:** Complete overview and setup guide for the agent

**Required Sections:**
- Agent Name and Overview
- Purpose and target use cases
- Prerequisites
- Step-by-step setup instructions
- Configuration notes and customization options
- Testing guide
- Troubleshooting tips
- Maintenance and support information

### system-instructions.md
**Purpose:** Complete system prompt/instructions for the agent

**Required Sections:**
- Role and Purpose
- Core Capabilities
- Interaction Guidelines
- Constraints and Limitations
- Output Format
- Special Scenarios
- Examples (if applicable)

**Key Characteristics:**
- Clear definition of agent's role
- Specific behavioral guidelines
- Explicit constraints on what agent should NOT do
- Response formatting instructions
- Tone and communication style

### knowledge-sources.md
**Purpose:** Documentation of all knowledge sources needed for the agent

**Required Sections:**
- Overview
- Required Sources (with detailed specifications)
- Optional Sources
- Setup Instructions
- Best Practices
- Maintenance Schedule
- Troubleshooting

**For Each Knowledge Source:**
- Type (PDF, URL, SharePoint, etc.)
- Description and purpose
- Content details
- Location/access information
- Format specifications
- Access requirements
- Update frequency

### starter-prompts.md
**Purpose:** Example prompts that demonstrate the agent's capabilities

**Required Sections:**
- 5-10 example prompts across different categories
- Expected outcomes for each prompt
- Variations of prompts
- Tips for creating effective prompts
- Customization guidance

**Prompt Categories:**
- Basic product information
- Getting started queries
- How-to questions
- Troubleshooting
- Advanced queries
- Feature-specific questions

## Content Guidelines

### Writing Style
- Clear and concise
- Professional but approachable
- Action-oriented
- User-focused

### Formatting
- Use markdown formatting
- Include code blocks for technical content
- Use bullet points and numbered lists
- Add headers for organization
- Include examples where helpful

### Completeness
- Every agent guide must include all four files
- Each file must contain all required sections
- Content should be comprehensive enough for independent deployment
- No references to missing information or "TODO" items

## Quality Checklist

Before submitting an agent guide, verify:

- [ ] Folder name uses kebab-case
- [ ] All four files are present
- [ ] README.md contains complete setup instructions
- [ ] system-instructions.md has comprehensive prompt
- [ ] knowledge-sources.md documents all sources
- [ ] starter-prompts.md includes 5-10 examples
- [ ] All content is clear and accurate
- [ ] No sensitive information included
- [ ] Agent has been tested successfully
- [ ] Documentation is free of typos and errors

## Example Agent Guide

See the `product-faq-agent` folder for a complete example that demonstrates this structure.

## Additional Resources

- [CONTRIBUTING.md](CONTRIBUTING.md) - Detailed contribution guidelines
- [README.md](README.md) - Repository overview and usage instructions
- [Product FAQ Agent Example](product-faq-agent/) - Reference implementation

## Need Help?

If you have questions about the structure or content requirements:
1. Review the example agent guide in `product-faq-agent/`
2. Consult the [CONTRIBUTING.md](CONTRIBUTING.md) guide
3. Open an issue in this repository
4. Contact the Microsoft Partner Solutions AI team
