# Personal Project Portfolio

## Adding New Projects

To add a new project to your portfolio:

1. **Copy the template** from `templates/project-template.md`
2. **Fill out the frontmatter** with your project details:
   - `id`: unique project identifier (lowercase, no spaces)
   - `title`: project display name
   - `description`: brief description for gallery
   - `image`: image filename
   - `url`: external project URL
3. **Write your project content** in markdown below the frontmatter
4. **Save the file** as `projects/your-project-id.md`
5. **Commit and push** - the workflow will automatically:
   - Convert MD to HTML
   - Update `projects.json`
   - Update the main gallery
   - Remove duplicate HTML files

## Template Structure

```markdown
---
id: my-project
title: My Project
description: Brief description
image: project-image.jpg
url: https://github.com/username/project
---

# Your markdown content here
```

## Workflow Features

- Automatic MD to HTML conversion
- Duplicate prevention
- Gallery auto-update
- Frontmatter parsing