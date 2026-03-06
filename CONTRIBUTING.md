# Contributing to the PD Data Guide

Thank you for your interest in contributing to the Getting Started With Parkinson's Disease Data guide!

## How to Contribute

### Reporting Issues

If you find errors, outdated information, or have suggestions:

1. Check if an issue already exists in the [GitHub Issues](https://github.com/MJFF-ResearchCommunity/getting-started-PD-data/issues)
2. If not, create a new issue with:
   - Clear description of the problem or suggestion
   - Page/section where the issue appears
   - Any relevant links or references

### Submitting Changes

#### Small Changes (typos, broken links, minor updates)

1. **Fork the repository** to your GitHub account
2. **Create a branch** for your changes:
   ```bash
   git checkout -b fix/typo-in-ppmi-chapter
   ```
3. **Make your changes** to the `.qmd` files
4. **Test locally**:
   ```bash
   quarto preview
   # Or render and open _book/index.html in your browser
   quarto render
   ```
5. **Commit your changes**:
   ```bash
   git add .
   git commit -m "Fix typo in PPMI chapter"
   ```
6. **Push to your fork**:
   ```bash
   git push origin fix/typo-in-ppmi-chapter
   ```
7. **Create a Pull Request** on GitHub

#### Large Changes (new sections, restructuring, major updates)

For substantial changes:

1. **Open an issue first** to discuss the proposed changes
2. Wait for feedback from maintainers
3. Once approved, follow the process above for submitting changes

## Development Workflow

### Prerequisites

- [Quarto](https://quarto.org/) (version 1.3+)
- Git
- Text editor (VS Code, RStudio, etc.)

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MJFF-ResearchCommunity/getting-started-PD-data.git
   cd getting-started-PD-data
   ```

2. **Preview the book**:
   ```bash
   quarto preview
   ```
   This starts a local server with live reload

3. **Make changes** to `.qmd` files in your editor

4. **Build the book**:
   ```bash
   quarto render
   ```

### File Structure

- `*.qmd` - Chapter content files (edit these)
- `_quarto.yml` - Book configuration
- `styles.css` - Custom styling
- `images/` - Image assets
- `_book/` - Rendered output (auto-generated, not committed)

### Style Guidelines

#### Content

- **Accuracy**: Verify all information against official sources
- **Clarity**: Write for researchers with varying backgrounds
- **Consistency**: Follow the existing structure and tone
- **Citations**: Include links to official documentation

#### Formatting

- Use **callout boxes** for important information:
  ```markdown
  ::: {.callout-note}
  ## Title
  Content here
  :::
  ```
  Types: `note`, `tip`, `warning`, `important`

- Use **markdown tables** for tabular data
- Use **section IDs** for cross-references: `{#sec-chapter-section}`
- Use **descriptive alt text** for all images

#### Code Style

- Format code blocks with language:
  ````markdown
  ```bash
  quarto render
  ```
  ````

### Testing Your Changes

Before submitting a PR:

1. ✅ Run `quarto render` without errors
2. ✅ Check rendered output in browser
3. ✅ Verify all links work
4. ✅ Check for typos and grammar
5. ✅ Ensure tables are formatted correctly
6. ✅ Test on mobile if possible

## Pull Request Process

1. **Update documentation** if needed (README, etc.)
2. **One PR per feature/fix** - keep changes focused
3. **Write clear commit messages**:
   - Use imperative mood: "Fix bug" not "Fixed bug"
   - Reference issues: "Fix #123: Update PPMI access link"
4. **Fill out the PR template** with:
   - What changed
   - Why it changed
   - How to verify the change
5. **Respond to review feedback** promptly
6. **Keep your branch updated** with main

## Review Process

- Maintainers will review PRs within 1 week
- May request changes or clarifications
- Once approved, maintainers will merge
- GitHub Actions will automatically render and deploy to GitHub Pages

## Code of Conduct

- Be respectful and constructive
- Focus on the content, not the person
- Welcome newcomers and help them contribute
- Follow scientific integrity standards

## Questions?

Contact: [researchcommunity@michaeljfox.org](mailto:researchcommunity@michaeljfox.org)

## Recognition

Contributors will be acknowledged in the guide and release notes.

Thank you for helping improve this resource for the Parkinson's disease research community!
