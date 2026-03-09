# Contributing to AI Sustainability Consulting

Thank you for considering contributing to this repository. Every agent here exists to help sustainability professionals do rigorous, defensible work — and contributions that raise the technical quality bar are the most valuable ones.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Agent Design Guidelines](#agent-design-guidelines)
- [Pull Request Process](#pull-request-process)
- [Style Guide](#style-guide)
- [Community](#community)

---

## 📜 Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code:

- **Be Respectful**: Treat everyone with respect. Healthy debate is encouraged, but personal attacks are not tolerated.
- **Be Inclusive**: Welcome and support people of all backgrounds and identities.
- **Be Collaborative**: What we create together is better than what we create alone.
- **Be Professional**: Keep discussions focused on improving the agents and the community.

---

## 🎯 How Can I Contribute?

### 1. Create a New Agent

Have an idea for a specialized agent? Great! Here's how to add one:

1. **Fork the repository**
2. **Choose the appropriate division** (or propose a new one):
   - `climate/` - GHG accounting, targets, climate risk, carbon markets
   - `compliance/` - CSRD, EPR, EU Taxonomy, SEC climate, permitting
   - `reporting/` - ESG reporting, CDP, materiality, data quality
   - `energy-resources/` - Energy efficiency, renewable energy, circular economy, water/waste
   - `supply-chain/` - Scope 3, LCA, supplier engagement, human rights
   - `nature-biodiversity/` - TNFD, nature-based solutions, land use
   - `strategy-engagement/` - Strategy, stakeholder engagement, impact, greenwashing audit
   - `specialized/` - Orchestration, data consolidation, client deliverables

3. **Create your agent file** following the template below
4. **Test your agent** in real scenarios
5. **Submit a Pull Request** with your agent

### 2. Improve Existing Agents

Found a way to make an agent better? Contributions welcome:

- Add real-world examples and use cases
- Enhance code samples with modern patterns
- Update workflows based on new best practices
- Add success metrics and benchmarks
- Fix typos, improve clarity, enhance documentation

### 3. Share Success Stories

Used these agents successfully? Share your story:

- Post in [GitHub Discussions](https://github.com/msitarzewski/agency-agents/discussions)
- Add a case study to the README
- Write a blog post and link it
- Create a video tutorial

### 4. Report Issues

Found a problem? Let us know:

- Check if the issue already exists
- Provide clear reproduction steps
- Include context about your use case
- Suggest potential solutions if you have ideas

---

## 🎨 Agent Design Guidelines

### Agent File Structure

Every agent should follow this structure:

```markdown
---
name: Agent Name
description: One-line description of the agent's specialty and focus
color: colorname or "#hexcode"
---

# Agent Name

## 🧠 Your Identity & Memory
- **Role**: Clear role description
- **Personality**: Personality traits and communication style
- **Memory**: What the agent remembers and learns
- **Experience**: Domain expertise and perspective

## 🎯 Your Core Mission
- Primary responsibility 1 with clear deliverables
- Primary responsibility 2 with clear deliverables
- Primary responsibility 3 with clear deliverables
- **Default requirement**: Always-on best practices

## 🚨 Critical Rules You Must Follow
Domain-specific rules and constraints that define the agent's approach

## 📋 Your Technical Deliverables
Concrete examples of what the agent produces:
- Code samples
- Templates
- Frameworks
- Documents

## 🔄 Your Workflow Process
Step-by-step process the agent follows:
1. Phase 1: Discovery and research
2. Phase 2: Planning and strategy
3. Phase 3: Execution and implementation
4. Phase 4: Review and optimization

## 💭 Your Communication Style
- How the agent communicates
- Example phrases and patterns
- Tone and approach

## 🔄 Learning & Memory
What the agent learns from:
- Successful patterns
- Failed approaches
- User feedback
- Domain evolution

## 🎯 Your Success Metrics
Measurable outcomes:
- Quantitative metrics (with numbers)
- Qualitative indicators
- Performance benchmarks

## 🚀 Advanced Capabilities
Advanced techniques and approaches the agent masters
```

### Agent Design Principles

1. **Technical accuracy is non-negotiable**
   - Cite real frameworks with correct version numbers (GHG Protocol Corporate Standard, ESRS 1, ISO 14040:2006, etc.)
   - Name specific regulations with correct citation (CA SB 54, EU Directive 2024/825/EU, 16 CFR Part 260)
   - Include real tool names: USEEIO, IBAT, ENCORE, WRI Aqueduct, Exiobase, OpenLCA, CDP questionnaire module numbers
   - Do not cite "various sustainability frameworks" — name them

2. **Greenwashing rules in every agent**
   - Every agent must include a "No Greenwashing — Ever" section in Critical Rules
   - The rule must be substantive — not just "don't greenwash" but specific to the agent's domain
   - Agents must actively prevent greenwashing risk in their domain, not just flag it

3. **Deliverable-focused**
   - Provide concrete output templates: GHG inventory tables, CDP module excerpts, ESRS disclosure structures, board deck slide frameworks
   - Show real outputs with real data structures, not vague descriptions of what the agent "will produce"
   - Every recommendation has a named owner and a timeline

4. **Audience-specific communication**
   - Agents must translate technical content for non-technical audiences
   - Board-level language: financial exposure, risk, and decision framing
   - Technical-level language: methodology precision, data quality scores, framework compliance
   - Legal-level language: appropriately hedged, forward-looking statement qualifications

5. **Quality bar: Anthesis/ERM/BSR standard**
   - Ask yourself: would a senior consultant at Anthesis, ERM, or BSR produce this deliverable?
   - If not, the agent needs more depth, more specificity, or better templates

### What Makes a Great Agent?

**Great sustainability agents have**:
- Narrow, deep specialization with real regulatory citations
- Distinct personality and clear communication style
- Concrete output templates with realistic data structures
- "No Greenwashing" section with domain-specific rules
- Step-by-step workflows calibrated to real engagement timelines
- Success metrics tied to actual outcomes (CDP score, assurance clearance, board approval)

**Avoid**:
- Vague framework references ("aligned with sustainability best practices")
- Generic output descriptions without actual templates
- Missing "No Greenwashing" commitment
- Overly broad scope that could apply to any sustainability topic
- Fabricated regulatory citations or incorrect methodology details

---

## 🔄 Pull Request Process

### Before Submitting

1. **Test Your Agent**: Use it in real scenarios, iterate on feedback
2. **Follow the Template**: Match the structure of existing agents
3. **Add Examples**: Include at least 2-3 code/template examples
4. **Define Metrics**: Include specific, measurable success criteria
5. **Proofread**: Check for typos, formatting issues, clarity

### Submitting Your PR

1. **Fork** the repository
2. **Create a branch**: `git checkout -b add-agent-name`
3. **Make your changes**: Add your agent file(s)
4. **Commit**: `git commit -m "Add [Agent Name] specialist"`
5. **Push**: `git push origin add-agent-name`
6. **Open a Pull Request** with:
   - Clear title: "Add [Agent Name] - [Category]"
   - Description of what the agent does
   - Why this agent is needed (use case)
   - Any testing you've done

### PR Review Process

1. **Community Review**: Other contributors may provide feedback
2. **Iteration**: Address feedback and make improvements
3. **Approval**: Maintainers will approve when ready
4. **Merge**: Your contribution becomes part of The Agency!

### PR Template

```markdown
## Agent Information
**Agent Name**: [Name]
**Category**: [engineering/design/marketing/etc.]
**Specialty**: [One-line description]

## Motivation
[Why is this agent needed? What gap does it fill?]

## Testing
[How have you tested this agent? Real-world use cases?]

## Checklist
- [ ] Follows agent template structure
- [ ] Includes personality and voice
- [ ] Has concrete code/template examples
- [ ] Defines success metrics
- [ ] Includes step-by-step workflow
- [ ] Proofread and formatted correctly
- [ ] Tested in real scenarios
```

---

## 📐 Style Guide

### Writing Style

- **Be specific**: "Reduce page load by 60%" not "Make it faster"
- **Be concrete**: "Create React components with TypeScript" not "Build UIs"
- **Be memorable**: Give agents personality, not generic corporate speak
- **Be practical**: Include real code, not pseudo-code

### Formatting

- Use **Markdown formatting** consistently
- Include **emojis** for section headers (makes scanning easier)
- Use **code blocks** for all code examples with proper syntax highlighting
- Use **tables** for comparing options or showing metrics
- Use **bold** for emphasis, `code` for technical terms

### Code Examples

```markdown
## Example Code Block

\`\`\`typescript
// Always include:
// 1. Language specification for syntax highlighting
// 2. Comments explaining key concepts
// 3. Real, runnable code (not pseudo-code)
// 4. Modern best practices

interface AgentExample {
  name: string;
  specialty: string;
  deliverables: string[];
}
\`\`\`
```

### Tone

- **Professional but approachable**: Not overly formal or casual
- **Confident but not arrogant**: "Here's the best approach" not "Maybe you could try..."
- **Helpful but not hand-holding**: Assume competence, provide depth
- **Personality-driven**: Each agent should have a unique voice

---

## 🌟 Recognition

Contributors who make significant contributions will be:

- Listed in the README acknowledgments section
- Highlighted in release notes
- Featured in "Agent of the Week" showcases (if applicable)
- Given credit in the agent file itself

---

## 🤔 Questions?

- **General Questions**: [GitHub Discussions](https://github.com/MikeTannenbaum/ai-sustainability-consulting/discussions)
- **Bug Reports**: [GitHub Issues](https://github.com/MikeTannenbaum/ai-sustainability-consulting/issues)
- **Feature Requests**: [GitHub Issues](https://github.com/MikeTannenbaum/ai-sustainability-consulting/issues)
- **Upstream (agent architecture)**: [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)

---

## 📚 Resources

### For New Contributors

- [README.md](README.md) - Overview and agent catalog
- [Example: GHG Inventory Specialist](climate/climate-ghg-inventory-specialist.md) - Strong technical depth
- [Example: Greenwashing Auditor](strategy-engagement/strategy-greenwashing-auditor.md) - Forensic personality + regulatory precision
- [Example: CSRD Advisor](compliance/compliance-csrd-advisor.md) - Complex framework, structured deliverables

### For Agent Design

- Read existing agents for inspiration
- Study the patterns that work well
- Test your agents in real scenarios
- Iterate based on feedback

---

## 🎉 Thank You!

Your contributions make The Agency better for everyone. Whether you're:

- Adding a new agent
- Improving documentation
- Fixing bugs
- Sharing success stories
- Helping other contributors

**You're making a difference. Thank you!**

---

<div align="center">

**Questions? Ideas? Feedback?**

[Open an Issue](https://github.com/msitarzewski/agency-agents/issues) • [Start a Discussion](https://github.com/msitarzewski/agency-agents/discussions) • [Submit a PR](https://github.com/msitarzewski/agency-agents/pulls)

Made with ❤️ by the community

</div>
