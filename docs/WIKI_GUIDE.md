# Setting Up and Using the Wiki

The GitHub Wiki is perfect for maintaining living documentation that needs frequent updates. This guide explains how to set it up and use it effectively for curriculum team coordination.

## Why Use the Wiki?

The wiki is ideal for:
- **Frequently updated content** (meeting notes, resource lists)
- **Collaborative documentation** (everyone can edit)
- **Knowledge that needs to be found quickly** (policies, guidelines)
- **Content that evolves over time** (best practices, FAQs)

## Enabling the Wiki

**For Repository Administrators:**
1. Go to repository Settings
2. Scroll to "Features" section
3. Check the box next to "Wikis"
4. Click "Save"

## Suggested Wiki Structure

Here's a recommended organization for a curriculum team wiki:

### Home Page
- Welcome message
- Quick links to key pages
- Recent updates
- How to navigate the wiki

### Main Sections

#### 1. Curriculum Development
- **Guidelines for Course Development**
  - Course design principles
  - Learning outcome writing guide
  - Assessment design tips
- **Review Processes**
  - How peer review works
  - Timeline and expectations
  - Checklist for proposals
- **Approval Workflow**
  - Steps from proposal to approval
  - Who decides what
  - Appeal process

#### 2. Policies and Procedures
- **Active Policies**
  - List of all current policies with links
  - Policy summaries
  - Effective dates
- **Policy Development Process**
  - How to propose a new policy
  - Review and approval steps
  - Implementation guidelines
- **Standard Operating Procedures**
  - Step-by-step guides for common tasks
  - Templates and forms
  - Contact information

#### 3. Best Practices
- **Teaching Strategies**
  - Active learning techniques
  - Assessment methods
  - Student engagement approaches
- **Course Design**
  - Backward design process
  - Aligning outcomes with activities
  - Scaffolding learning
- **Technology Integration**
  - Recommended tools
  - Implementation guides
  - Troubleshooting tips

#### 4. Resources
- **Internal Resources**
  - Curriculum committee members
  - Support services
  - Training opportunities
- **External Resources**
  - Recommended readings
  - Useful websites
  - Professional organizations
- **Template Library**
  - Links to all templates
  - Example documents
  - Style guides

#### 5. Meeting Notes
- **Current Academic Year**
  - All meeting summaries
  - Decisions made
  - Action item tracking
- **Archive**
  - Previous years' notes
  - Historical decisions
  - Lessons learned

#### 6. FAQ
- **For Course Proposers**
  - Common questions about the process
  - How to address typical concerns
  - Success tips
- **For Reviewers**
  - Review expectations
  - Common issues to look for
  - Feedback best practices
- **For Committee Members**
  - Roles and responsibilities
  - Meeting schedule
  - Communication norms

## Creating Wiki Pages

### From the Wiki Tab
1. Click the **Wiki** tab
2. Click **New page** (or **Create the first page** if starting fresh)
3. Enter a page title (use descriptive names)
4. Write content using markdown
5. Click **Save page**

### Linking Between Pages
Use double brackets to link to another wiki page:
```markdown
See the [[Course Development Guidelines]] for more information.
```

GitHub automatically creates the link, and you can click it to create the page if it doesn't exist yet.

### Creating Sub-pages
Use forward slashes in page titles to create hierarchy:
- Main page: `Policies`
- Sub-page: `Policies/Peer-Review`
- Sub-page: `Policies/Assessment`

This creates a navigable structure.

## Markdown Basics for Wiki

### Headers
```markdown
# Main Header (H1)
## Section Header (H2)
### Subsection Header (H3)
```

### Lists
```markdown
- Bullet point
- Another point
  - Indented point

1. Numbered item
2. Another numbered item
```

### Links
```markdown
[Link text](https://example.com)
[[Wiki Page Name]]
[Link to file](../docs/templates/course-proposal.md)
```

### Tables
```markdown
| Column 1 | Column 2 |
|----------|----------|
| Data 1   | Data 2   |
| Data 3   | Data 4   |
```

### Formatting
```markdown
**bold text**
*italic text*
`code or commands`
> Quote block
---
Horizontal rule
```

## Best Practices for Wiki Management

### 1. Start with a Strong Home Page
Create a welcoming home page that:
- Explains the wiki's purpose
- Links to key pages
- Shows recent updates
- Guides navigation

Example home page structure:
```markdown
# Curriculum Team Wiki

Welcome! This wiki contains our collective knowledge about curriculum development.

## Quick Links
- [[Course Development Guidelines]]
- [[Active Policies]]
- [[Meeting Notes]]
- [[FAQ]]

## Recent Updates
- Added new peer review process (Oct 15)
- Updated assessment guidelines (Oct 1)

## How to Use This Wiki
...
```

### 2. Use Consistent Naming
- Use clear, descriptive titles
- Be consistent with capitalization
- Avoid special characters
- Use hyphens for multi-word titles

### 3. Keep Pages Focused
- One topic per page
- Link to related pages rather than duplicating content
- Break long pages into sub-pages

### 4. Update Regularly
- Review pages quarterly
- Add "Last updated" dates
- Archive outdated information rather than deleting it
- Note when content is no longer current

### 5. Make It Searchable
- Use descriptive headers
- Include keywords in page text
- Create a comprehensive home page with links
- Consider a sitemap page

### 6. Encourage Contributions
- Keep the barrier to editing low
- Welcome improvements and additions
- Acknowledge contributors
- Make it clear that everyone can edit

## Maintenance Schedule

### Weekly
- Review and approve suggested edits
- Update meeting notes

### Monthly
- Check for broken links
- Update "Recent Updates" section
- Review most-visited pages for accuracy

### Quarterly
- Comprehensive review of all pages
- Archive old meeting notes
- Update FAQ based on recent questions
- Solicit feedback on wiki usefulness

### Annually
- Major restructuring if needed
- Archive previous year's content
- Update all "year-specific" content
- Review and update templates

## Migrating Existing Documentation

If you have existing documentation, here's how to move it to the wiki:

1. **Prioritize**: Start with most frequently accessed documents
2. **Convert to Markdown**: If documents are in Word/PDF, convert to markdown
3. **Create Pages**: Add one document at a time
4. **Link**: Create navigation between related pages
5. **Announce**: Let team know where to find migrated content
6. **Redirect**: Update old links to point to wiki
7. **Archive**: Keep old documents temporarily for reference

## Examples of Wiki Pages

### Example 1: Simple Policy Page
```markdown
# Assessment Policy

**Approved**: October 2024
**Next Review**: October 2025

## Purpose
This policy ensures consistent, fair assessment practices across all courses.

## Key Principles
1. Assessments align with learning outcomes
2. Multiple assessment methods are used
3. Clear grading criteria are provided to students

## Procedures
See [[Assessment Development Process]] for step-by-step guide.

## Resources
- [[Rubric Templates]]
- [[Assessment Examples]]

---
*For questions, contact the Assessment Committee*
```

### Example 2: Resource List
```markdown
# Teaching Resources

## Active Learning Strategies
- [[Think-Pair-Share]]
- [[Jigsaw Method]]
- [[Case-Based Learning]]

## Technology Tools
- **Polling**: Mentimeter, Poll Everywhere
- **Collaboration**: Google Docs, Padlet
- **Assessment**: Canvas, Gradescope

## Recommended Reading
- *How Learning Works* by Ambrose et al.
- *Small Teaching* by James Lang

---
*Have a resource to add? Edit this page!*
```

### Example 3: Meeting Notes Index
```markdown
# Curriculum Committee Meeting Notes

## 2024-2025 Academic Year
- [[2024-11 November Meeting]]
- [[2024-10 October Meeting]]
- [[2024-09 September Meeting]]

## Previous Years
- [[2023-2024 Meetings]]
- [[2022-2023 Meetings]]

## Upcoming Meetings
**Next meeting**: November 19, 2024 at 2pm

**Agenda items**: Add to [[Agenda Ideas]]

---
*Meeting notes are typically posted within 48 hours of the meeting*
```

## Troubleshooting

**Problem**: Can't find a page
- **Solution**: Use the search box in the wiki, or check the page list in the sidebar

**Problem**: Broken link
- **Solution**: Edit the page and fix the link, or create the missing page

**Problem**: Lost my edits
- **Solution**: Check the "History" tab on the page to view previous versions

**Problem**: Formatting looks wrong
- **Solution**: Click "Edit" and check your markdown syntax, or use the preview

**Problem**: Someone made an incorrect edit
- **Solution**: Use "History" to view previous versions, then edit to restore correct content

## Additional Resources

- **GitHub Wiki Documentation**: https://docs.github.com/en/communities/documenting-your-project-with-wikis
- **Markdown Guide**: https://www.markdownguide.org/
- **Wiki Examples**: Browse other GitHub project wikis for inspiration

---

*This guide itself could be turned into a wiki page! Once your wiki is set up, consider moving these instructions there for easier access.*
