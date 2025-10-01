# Personal Project Portfolio

## Adding New Projects

To add a new project to your portfolio:

1. **Copy the template** from `templates/project-template.md`
2. **Fill out the frontmatter** with your project details:
   - `id`: unique project identifier (example-project)
   - `title`: project display name (Example Project)
   - `description`: brief description for gallery
   - `image`: image filename (project1-image.jpg)
   - `url`: external project URL
3. **Write your project content** in markdown below the frontmatter
4. **Save the file** as `projects/example-project.md`
5. **Commit and push** - the workflow will automatically:
   - Convert MD to HTML
   - Update `projects.json`
   - Update the main gallery
   - Remove duplicate HTML files

## Template Structure

```markdown
---
id: example-project
title: Example Project
description: A sample project demonstrating the markdown template
image: project1-image.jpg
url: https://github.com/username/example-project
---

# Example Project

## Overview
This is an example project that demonstrates how to use the markdown template system.
```

## Workflow Features

- Automatic MD to HTML conversion
- Duplicate prevention
- Gallery auto-update
- Frontmatter parsing