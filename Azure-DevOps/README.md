# Azure DevOps AI Work Item Editor Prompts

A comprehensive collection of specialized AI system prompts designed to optimize Azure DevOps work item creation, editing, and management. These prompts enable AI assistants to provide expert-level guidance for all aspects of agile project management and software development workflows.

## 📋 Overview

This collection provides AI assistants with deep expertise in:
- **Agile Methodology**: Scrum, Kanban, and hybrid approaches
- **Work Item Hierarchies**: From Epics to Tasks with proper relationships
- **Quality Standards**: INVEST principles, DoD, and acceptance criteria
- **Team Collaboration**: Cross-functional workflows and communication
- **Process Optimization**: Continuous improvement and best practices

## 🎯 Work Item Types Covered

### Strategic Planning
- **[Epic Planning](Epic-Feature-Planning-Assistant.md)**: Large business initiatives spanning multiple releases
- **[Feature Planning](Epic-Feature-Planning-Assistant.md)**: Major capabilities within epics

### Development Work
- **[Product Backlog Items (PBI)](PBI-Creation-Assistant.md)**: User-focused features and functionality
- **[User Stories](User-Story-Creation-Assistant.md)**: End-user requirements and scenarios
- **[Tasks](Task-Creation-Assistant.md)**: Technical implementation work and subtasks

### Quality Assurance
- **[Test Cases](Test-Case-Creation-Assistant.md)**: Comprehensive testing scenarios and validation
- **[Bug Tracking](Bug-Tracking-Assistant.md)**: Defect reporting and resolution management

### Ongoing Management
- **[Work Item Editing](Work-Item-Editing-Management-Assistant.md)**: Lifecycle management and updates
- **[System Prompt](Work-Item-Editor-AI-System-Prompt.md)**: Comprehensive AI assistant configuration

## 🚀 Quick Start Guide

### For AI Integration
1. Choose the appropriate prompt file for your work item type
2. Use the system prompt as base configuration for your AI assistant
3. Combine with specific work item prompts as needed
4. Customize field mappings and team processes as required

### For Team Adoption
1. Start with the **[System Prompt](Work-Item-Editor-AI-System-Prompt.md)** for comprehensive guidance
2. Focus on **[PBI Creation](PBI-Creation-Assistant.md)** for user-facing features
3. Add **[Task Creation](Task-Creation-Assistant.md)** for technical work breakdown
4. Implement **[Bug Tracking](Bug-Tracking-Assistant.md)** for quality management

## 📚 Prompt Structure

Each prompt follows a consistent structure:

### 1. **Core Framework**
- Purpose and objectives
- Key principles and methodologies
- Quality standards and best practices

### 2. **Templates and Examples**
- Field-by-field guidance
- Real-world scenarios
- Common patterns and anti-patterns

### 3. **Quality Assurance**
- Checklists and validation criteria
- INVEST principles application
- Definition of Ready/Done alignment

### 4. **Team Integration**
- Collaboration guidelines
- Stakeholder communication
- Process optimization

## 🏆 Key Features

### Smart Field Population
- **Automated Suggestions**: Context-aware field recommendations
- **Template Library**: Pre-configured formats for common scenarios
- **Validation Rules**: Built-in quality checks and standards enforcement

### Agile Best Practices
- **INVEST Criteria**: Independent, Negotiable, Valuable, Estimable, Small, Testable
- **User-Centric Focus**: Always prioritize user value and business outcomes
- **Iterative Refinement**: Support for continuous improvement and adaptation

### Cross-Functional Support
- **Technical Teams**: Detailed implementation guidance and architectural considerations
- **Product Teams**: Business value articulation and stakeholder communication
- **QA Teams**: Comprehensive testing strategies and acceptance criteria definition

## 📖 Usage Examples

### Creating a New PBI
```
Prompt: "Help me create a PBI for user authentication with social media providers"

AI Response:
Title: "Enable users to sign in using Google and Facebook accounts"

As a new user visiting our platform
I want to sign in using my existing Google or Facebook account
So that I can access the platform quickly without creating a new password

Acceptance Criteria:
AC1: Social Provider Integration
- Given I'm on the sign-in page
- When I click "Sign in with Google" 
- Then I'm redirected to Google OAuth flow
- And upon successful authentication, I'm logged into our platform

[Complete detailed response with all fields populated]
```

### Breaking Down an Epic
```
Prompt: "Help me break down the 'Mobile App Development' epic into features"

AI Response:
Epic: Mobile App Development - Capture Mobile Market Share

Features:
1. Core User Authentication and Profile Management
2. Product Browsing and Search Functionality  
3. Shopping Cart and Checkout Process
4. Order History and Tracking
5. Push Notifications and Alerts
6. Offline Mode and Data Synchronization

[Detailed feature descriptions with acceptance criteria]
```

### Creating Test Cases
```
Prompt: "Create test cases for the shopping cart functionality"

AI Response:
Test Suite: Shopping Cart Management

TC-001: Functional - Add Product to Cart - Valid Product Selection
Objective: Validate users can successfully add products to shopping cart

[Complete test case with steps, expected results, and pass/fail criteria]
```

## ⚙️ Integration Guidelines

### Azure DevOps Configuration
1. **Work Item Types**: Map prompt templates to your organization's work item types
2. **Field Mappings**: Align field names with your project's custom fields
3. **Process Templates**: Integrate with Agile, Scrum, or CMMI process templates
4. **Area Paths**: Configure for your team and product structure

### Team Process Integration
1. **Sprint Planning**: Use PBI and Task prompts during sprint planning sessions
2. **Daily Standups**: Apply Work Item Editing prompts for progress updates
3. **Retrospectives**: Leverage quality guidelines for process improvement
4. **Release Planning**: Utilize Epic and Feature prompts for strategic planning

## 🎨 Customization Options

### Organization-Specific Adaptations
- **Industry Terminology**: Adapt language for healthcare, finance, manufacturing, etc.
- **Compliance Requirements**: Integrate GDPR, HIPAA, SOX, or other regulatory needs
- **Technology Stack**: Customize for specific development platforms and tools
- **Team Practices**: Align with existing team ceremonies and workflows

### Field Customizations
```
Standard Fields → Custom Fields
Story Points → Effort Hours
Priority → Business Value Score
Tags → Component Categories
Assigned To → Development Pod
```

## 📊 Quality Metrics and KPIs

### Work Item Quality Indicators
- **Completion Rate**: Percentage of work items completed within sprint
- **Estimation Accuracy**: Variance between estimated and actual effort
- **Defect Escape Rate**: Bugs found in production vs. development
- **Cycle Time**: Average time from active to closed state

### Team Performance Metrics
- **Velocity Trends**: Story points completed per sprint over time
- **Burndown Accuracy**: Sprint progress predictability
- **Stakeholder Satisfaction**: Feedback on delivered features
- **Technical Debt Ratio**: Maintenance work vs. new feature work

## 🔧 Troubleshooting Common Issues

### Poor Work Item Quality
- **Symptoms**: Vague requirements, scope creep, frequent changes
- **Solutions**: Use INVEST criteria, implement DoR/DoD, regular refinement
- **Prompts**: Apply PBI Creation and Work Item Editing guidelines

### Team Coordination Problems
- **Symptoms**: Dependencies blocking work, unclear ownership
- **Solutions**: Improve linking strategy, clearer assignments, daily updates
- **Prompts**: Focus on Task Creation and Work Item Management sections

### Stakeholder Communication Gaps
- **Symptoms**: Misaligned expectations, late feedback, requirement disputes
- **Solutions**: Better story mapping, regular demos, clear acceptance criteria
- **Prompts**: Emphasize User Story Creation and Epic Planning approaches

## 🚀 Advanced Features

### AI-Powered Enhancements
- **Automated Sizing**: ML-based story point estimation
- **Smart Assignments**: Team capacity and skill-based task distribution
- **Predictive Analytics**: Sprint success probability and risk assessment
- **Natural Language Processing**: Requirements extraction from conversations

### Integration Capabilities
- **Version Control**: Link work items to code branches and pull requests
- **CI/CD Pipelines**: Automated work item state transitions
- **Communication Tools**: Slack, Teams, and email notification integration
- **Business Intelligence**: PowerBI and analytics dashboard integration

## 📈 Success Metrics

### Implementation Success Indicators
- **20% reduction** in work item revision cycles
- **30% improvement** in sprint completion rates  
- **40% decrease** in requirement clarification time
- **50% increase** in stakeholder satisfaction scores

### Long-term Organizational Benefits
- **Improved Predictability**: Better sprint and release planning accuracy
- **Enhanced Quality**: Fewer defects and higher user satisfaction
- **Faster Delivery**: Reduced cycle time and improved throughput
- **Better Alignment**: Clear traceability from business goals to implementation

## 🤝 Contributing

We welcome contributions to improve these prompts:

1. **Fork the Repository**: Create your own copy for modifications
2. **Propose Improvements**: Submit pull requests with enhancements
3. **Share Examples**: Add real-world usage examples and case studies
4. **Report Issues**: Identify gaps or areas for improvement

### Contribution Guidelines
- Follow existing prompt structure and formatting
- Include practical examples and use cases
- Maintain focus on quality and best practices
- Test prompts with different AI models for compatibility

## 📄 License

This collection is provided under the MIT License, enabling free use and modification for both commercial and non-commercial purposes.

## 🆘 Support and Resources

### Getting Help
- **Documentation**: Comprehensive guides in each prompt file
- **Examples**: Real-world scenarios and templates included
- **Community**: Share experiences and best practices
- **Expert Consultation**: Professional services available

### Additional Resources
- [Azure DevOps Official Documentation](https://docs.microsoft.com/en-us/azure/devops/)
- [Agile Best Practices Guide](https://www.agilealliance.org/agile101/)
- [Scrum Framework Overview](https://scrumguides.org/)
- [User Story Mapping Techniques](https://www.jpattonassociates.com/user-story-mapping/)

---

**Transform your Azure DevOps workflow with AI-powered work item management. Start with any prompt file and experience the difference expert guidance makes in your agile delivery process.**