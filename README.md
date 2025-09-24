# Personal Project Portfolio

## Adding New Projects

To add a new project to your portfolio:

1. **Upload project image** to the repository
2. **Create an issue** using the "Add New Project" template
3. **Fill out all required fields** in the issue template
4. **Create a pull request** that references the issue
5. **Add the `new-project` label** to your pull request
6. **Merge the pull request** - the workflow will automatically:
   - Extract project info from the PR description
   - Add it to `projects.json`
   - Generate the new project HTML page
   - Update the main gallery

## Project Template Format

When creating a PR, include this format in the description:

```
**Project ID:** my-new-project
**Project Title:** My New Project
**Description:** Brief description for the gallery
**Image:** my-project-image.jpg
**External URL:** https://github.com/username/project
**Detailed Description:** Full description with technologies used, challenges faced, and solutions implemented.
```

## Manual Method

Alternatively, edit `projects.json` directly and push to trigger the workflow.