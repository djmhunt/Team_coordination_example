# GitHub for Non-Technical Teams: A Practical Guide

This guide walks through the specific GitHub features used for curriculum team coordination, with step-by-step instructions for non-technical users.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Working with Issues](#working-with-issues)
3. [Participating in Discussions](#participating-in-discussions)
4. [Using Projects for Planning](#using-projects-for-planning)
5. [Contributing to the Wiki](#contributing-to-the-wiki)
6. [Referencing Documents](#referencing-documents)
7. [Common Tasks](#common-tasks)

## Getting Started

### Creating a GitHub Account

1. Go to https://github.com
2. Click "Sign up" in the top right
3. Follow the prompts to create your account
4. Verify your email address

### Accessing the Repository

1. Navigate to: https://github.com/djmhunt/Team_coordination_example
2. Click "Watch" (top right) to receive notifications
3. Bookmark this page for easy access

### Understanding the Interface

- **Code tab**: Where documents are stored
- **Issues tab**: For proposals, tasks, and discussions that need tracking
- **Pull requests tab**: For proposed changes to documents (advanced)
- **Discussions tab**: For open-ended conversations
- **Projects tab**: For visual workflow management
- **Wiki tab**: For maintained knowledge base

## Working with Issues

Issues are perfect for:
- Course proposals that need review
- Policy discussions that need decisions
- Tasks that need completion
- Sharing good practices

### Creating an Issue

1. Click the **Issues** tab
2. Click green **New issue** button
3. Choose a template:
   - **Course Proposal**: For new course ideas
   - **Policy Discussion**: For policy proposals or revisions
   - **Share a Good Practice**: For teaching tips
   - **General Task**: For action items
4. Fill in the template fields
5. Add labels (tags) from the right sidebar:
   - `proposal` - for new proposals
   - `policy` - for policy matters
   - `good-practice` - for teaching tips
   - `needs-review` - requires feedback
   - `high-priority` - urgent items
6. Assign to people (right sidebar) if you know who should work on it
7. Click **Submit new issue**

### Commenting on an Issue

1. Scroll to the bottom of any issue
2. Type your comment in the text box
3. You can format text using the toolbar or [markdown](https://guides.github.com/features/mastering-markdown/)
4. Tag someone with `@username` to notify them
5. Click **Comment**

### Closing an Issue

Once the issue is resolved:
1. Scroll to the bottom
2. Click **Close issue** button
3. Add a final comment explaining the resolution

### Useful Issue Features

**Referencing other issues**: Type `#` followed by the issue number (e.g., `#5`)

**Mentioning people**: Type `@` followed by their username

**Creating a checklist**:
```markdown
- [ ] Task 1
- [ ] Task 2
- [x] Completed task
```

**Adding files**: Drag and drop files into the comment box, or click the "Attach files" link

## Participating in Discussions

Discussions are for conversations that don't need task tracking:
- Brainstorming new ideas
- Q&A about curriculum design
- Sharing resources
- General announcements

### Starting a Discussion

1. Click the **Discussions** tab
2. Click **New discussion**
3. Choose a category:
   - **General**: Open-ended conversations
   - **Ideas**: Brainstorming and suggestions
   - **Q&A**: Questions that need answers
   - **Show and tell**: Share your work
   - **Announcements**: Important updates
4. Add a clear title
5. Write your post (you can format it with markdown)
6. Click **Start discussion**

### Participating in a Discussion

1. Browse discussions in the Discussions tab
2. Click on one to read it
3. Add your thoughts in the comment box at the bottom
4. Use reactions (👍 😄 ❤️ etc.) to show agreement without cluttering comments
5. You can mark a response as the answer for Q&A discussions

## Using Projects for Planning

Projects provide a visual board to track progress on multiple related items.

### Viewing a Project

1. Click the **Projects** tab
2. Click on a project name to open it
3. See items organized in columns (e.g., "Proposed", "In Review", "Approved")

### Adding Items to a Project

1. Open the project
2. Click **+ Add item** in a column
3. Type to search for existing issues or create a new draft item
4. Press Enter to add

### Moving Items Between Columns

1. Click and drag an item to a new column
2. This shows progress (e.g., moving from "In Review" to "Approved")

### Using Project Views

Projects can have different views:
- **Board view**: Kanban-style columns
- **Table view**: Spreadsheet format
- **Roadmap view**: Timeline view

Switch views using the tabs at the top of the project.

## Contributing to the Wiki

The wiki is for living documentation that gets updated frequently.

### Creating a Wiki Page

1. Click the **Wiki** tab
2. Click **New page**
3. Give your page a descriptive title
4. Write content using markdown formatting
5. Click **Save page**

### Editing a Wiki Page

1. Navigate to the wiki page
2. Click **Edit** at the top right
3. Make your changes
4. Add a brief description of what you changed
5. Click **Save page**

### Organizing the Wiki

- Use the sidebar to organize pages hierarchically
- Link between pages using `[[Page Name]]` syntax
- Create a table of contents on the main wiki page

### Suggested Wiki Pages

- **Curriculum Development Guidelines**
- **Assessment Best Practices**
- **Resources for Instructors**
- **Meeting Notes Archive**
- **FAQ**
- **Active Learning Strategies**

## Referencing Documents

You can link to documents stored in the repository from issues, discussions, and wiki pages.

### Linking to a File

Format: `[Link Text](path/to/file.md)`

Example:
```markdown
See our [Course Proposal Template](docs/templates/course-proposal.md)
```

### Linking to a Specific Section

Add `#section-name` to the end of the link:
```markdown
See [Assessment Methods](docs/templates/course-proposal.md#assessment-methods)
```

### Viewing Files

1. Click the **Code** tab
2. Navigate through folders by clicking on them
3. Click on a file name to view it
4. Click **Raw** to see the unformatted text
5. Click the pencil icon to suggest edits (creates a pull request)

## Common Tasks

### Task: Submit a Course Proposal

1. Create your proposal document using the template at `docs/templates/course-proposal.md`
2. Save it in the `docs/proposals/` folder (create a pull request or ask admin to add it)
3. Create an issue using the "Course Proposal" template
4. Link to your proposal document in the issue
5. Tag relevant committee members
6. Monitor the issue for feedback and discussion

### Task: Propose a Policy Change

1. Draft the policy using `docs/templates/policy-template.md`
2. Save it in `docs/policies/`
3. Create an issue with the "Policy Discussion" template
4. Start a discussion in the Discussions tab to gather initial feedback
5. Update the policy based on feedback
6. Request formal review through the curriculum committee

### Task: Share a Teaching Practice

1. Document your practice using `docs/templates/good-practice-template.md`
2. Save it in `docs/good-practices/`
3. Create an issue with the "Share a Good Practice" template
4. Link to your detailed documentation
5. Invite others to share their experiences in comments

### Task: Track Meeting Action Items

1. After a meeting, create individual issues for each action item
2. Use the "General Task" template
3. Assign to responsible person
4. Set due date
5. Add to relevant project board
6. Check off when completed

### Task: Find Information

**Search for issues/discussions**: Use the search box at the top of the Issues or Discussions tab

**Search for documents**: Use GitHub's search (top left) and filter by "Code"

**Browse by label**: Click on any label to see all items with that label

## Tips for Success

1. **Be specific in titles**: Good: "Proposal: Data Literacy Course for Educators" vs. Bad: "New course idea"

2. **Use templates**: They ensure you include all necessary information

3. **Tag appropriately**: Use @mentions to bring items to people's attention

4. **Update regularly**: Keep issues current by adding comments when status changes

5. **Close completed items**: Keep your workspace tidy by closing resolved issues

6. **Link related items**: Use `#issue-number` to show connections

7. **Use labels consistently**: Helps with filtering and organization

8. **Subscribe to notifications**: Watch the repository to stay informed

9. **Write clearly**: Remember your audience is non-technical educators

10. **Ask questions**: Use discussions or comments if you're unsure how to do something

## Getting Help

- **GitHub Docs**: https://docs.github.com
- **Markdown Guide**: https://guides.github.com/features/mastering-markdown/
- **Ask the team**: Start a discussion with your question
- **Repository admin**: Contact [@djmhunt](https://github.com/djmhunt) for access or technical issues

## Glossary

- **Repository (Repo)**: The project space containing all files and history
- **Issue**: A trackable task, proposal, or discussion thread
- **Label**: A tag for categorizing issues
- **Mention**: Using @username to notify someone
- **Markdown**: Simple text formatting syntax
- **Wiki**: Editable documentation pages
- **Project**: Visual board for organizing work
- **Discussion**: Forum-style conversation
- **Watch**: Subscribe to notifications for a repository
- **Fork**: Creating your own copy of a repository (advanced)
- **Pull Request**: Proposing changes to files (advanced)

---

*This guide is a living document. If you have suggestions for improvements, please create an issue or discussion!*
