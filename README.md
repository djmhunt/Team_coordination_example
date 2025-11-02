# Curriculum Team Collaboration Guide

This repository demonstrates how GitHub can be used for asynchronous coordination of curriculum development teams. It showcases how non-technical team members can collaborate on policy documents, proposals, and discussions about good practices—without storing the main course content.

## 🎯 Purpose

This repository serves as a **coordination hub** for curriculum teams to:
- Discuss and refine educational policies
- Propose new courses or curriculum changes
- Share and discuss examples of good practice
- Track progress on curriculum development initiatives
- Maintain institutional knowledge in the Wiki

## 🛠️ Key GitHub Features for Curriculum Teams

### 1. **Issues** - Task Tracking & Discussions
Use issues to track tasks, proposals, and discussions:
- **Course Proposals**: Submit new course ideas for team review
- **Policy Discussions**: Debate changes to teaching policies
- **Good Practice Examples**: Share and discuss successful teaching methods
- **Action Items**: Track follow-up tasks from meetings

**How to create an issue:**
1. Go to the "Issues" tab
2. Click "New issue"
3. Choose a template (if available) or create a blank issue
4. Add a clear title and description
5. Tag relevant team members with @mentions
6. Assign labels (e.g., "policy", "proposal", "good-practice")
7. Link related documents by adding their file paths

### 2. **Discussions** - Community Conversations
Use discussions for broader conversations that don't need task tracking:
- Brainstorming sessions
- Q&A about curriculum design
- Announcements and updates
- Long-form discussions about teaching philosophy

**How to start a discussion:**
1. Go to the "Discussions" tab
2. Click "New discussion"
3. Choose a category (Q&A, Ideas, General, etc.)
4. Share your thoughts and invite feedback

### 3. **Projects** - Visual Workflow Management
Use project boards to organize and track multiple initiatives:
- Curriculum development roadmap
- Course review pipeline
- Policy implementation tracking

**How to use projects:**
1. Go to the "Projects" tab
2. Create a new project with columns (e.g., "Proposed", "In Review", "Approved", "Implemented")
3. Add issues and pull requests to track progress
4. Move items between columns as they advance

### 4. **Wiki** - Knowledge Repository
Use the wiki to maintain institutional knowledge:
- Curriculum design guidelines
- Teaching best practices documentation
- Meeting notes and decisions
- Resource libraries
- Standard operating procedures

**How to use the wiki:**
1. Go to the "Wiki" tab
2. Create new pages for different topics
3. Link between pages to create a knowledge network
4. Keep documentation up-to-date as policies evolve

### 5. **Documents & Referencing**
Store policy documents, proposals, and examples as markdown or text files in the repository. Reference them in issues and discussions:

```markdown
See our [Course Proposal Template](docs/templates/course-proposal.md)
Relates to [Good Practice: Active Learning](docs/good-practices/active-learning.md)
```

## 📁 Repository Structure

```
/docs
  /policies          - Team policies and guidelines
  /proposals         - Course and curriculum proposals
  /good-practices    - Examples of effective teaching methods
  /templates         - Reusable templates for proposals and documents
  /meeting-notes     - Records of team meetings
```

## 🚀 Getting Started

### For Team Members New to GitHub

1. **Create a GitHub account** at https://github.com
2. **Navigate to this repository**
3. **Watch the repository** to get notifications about new discussions and issues
4. **Explore the tabs**: Issues, Discussions, Projects, Wiki
5. **Start participating**: Comment on issues, join discussions, suggest changes

### For Repository Administrators

1. **Enable Discussions**: Settings → Features → Discussions
2. **Enable Wiki**: Settings → Features → Wiki
3. **Set up issue templates**: Create `.github/ISSUE_TEMPLATE/` directory
4. **Configure project boards**: Create project views for different workflows
5. **Add collaborators**: Settings → Collaborators

## 💡 Best Practices

1. **Use clear, descriptive titles** for issues and discussions
2. **Tag relevant team members** to bring items to their attention
3. **Link related items** using #issue-number or file paths
4. **Label everything** for easy filtering and organization
5. **Close completed items** to keep the workspace tidy
6. **Update the wiki regularly** with decisions and learnings
7. **Be respectful and constructive** in all communications

## 📚 Example Workflows

### Proposing a New Course
1. Create an issue using the "Course Proposal" template
2. Describe the course concept, objectives, and target audience
3. Tag curriculum committee members for review
4. Discuss in comments, making revisions as needed
5. Once approved, move to "Approved" in the project board
6. Use the issue to track course development progress

### Discussing a Policy Change
1. Create a draft policy document in `/docs/policies/`
2. Open a discussion in the "Policy Discussion" category
3. Reference the document in the discussion
4. Collect feedback and suggestions
5. Create an issue to track the policy approval process
6. Once approved, update the wiki with the new policy

### Sharing Good Practices
1. Write up the practice as a markdown document in `/docs/good-practices/`
2. Create an issue with the "Good Practice" label
3. Share context about when and how it worked
4. Invite others to share their experiences
5. Update the wiki with a summary of learnings

## 🤝 Contributing

This repository is for the curriculum team. All team members are encouraged to:
- Share ideas and feedback
- Propose improvements to our processes
- Document their experiences
- Help maintain our collective knowledge base

## 📄 License

This repository is licensed under CC0 1.0 Universal - see the [LICENSE](LICENSE) file for details.