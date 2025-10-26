+++
title = "Building an Automated Pipeline: From EvolutionVault to BlogVault"
slug = "draft-article"
date = "2025-10-25 10:00:00"
draft = false
tags = ["automation", "blog", "hugo", "cloudflare"]
categories = ["technology"]
+++

## Overview

I built a system that automatically copies articles created in EvolutionVault to BlogVault, pushes them to GitHub, and automatically deploys them using Cloudflare Pages.

## System Architecture

### 1. Article Creation Environment
- **EvolutionVault**: Article creation and management 
- **Format**: Markdown with YAML frontmatter

### 2. Automation Scripts
- **Python script**: Article conversion, copying, and Git operations
- **Batch file**: Execution in Windows environment
- **Configuration file**: Management of various settings

### 3. Deployment Environment
- **BlogVault**: Hugo site
- **GitHub**: Version control and CI/CD
- **Cloudflare Pages**: Automatic deployment

## Process Flow

1. **Article Creation**: Create article in EvolutionVault
2. **Format Conversion**: Convert to Hugo format
3. **Copy**: Copy to BlogVault
4. **Git Operations**: Stage, commit, and push
5. **Auto Deploy**: Update site on Cloudflare Pages

## Usage

### Basic Usage
```bash
# Execute batch file
blog_automation.bat

# Or directly run Python script
python blog_automation.py
```

### Specify Particular Article
```bash
python blog_automation.py "article_filename.md"
```

## Technical Details

### Article Format Conversion
- YAML frontmatter parsing
- Conversion to Hugo format
- Metadata preservation

### Git Operations
- Automatic staging
- Commit message generation
- Push to remote repository

### Error Handling
- File existence verification
- Git operation error handling
- Detailed error messages

## Future Improvements

1. **UI Enhancement**: More user-friendly interface
2. **Batch Processing**: Bulk processing of multiple articles
3. **Templates**: Automatic generation of article templates
4. **Notifications**: Deployment completion notification feature

## Summary

This automation system enables efficient handling of the entire process from article creation to publication. It significantly reduces manual operations, allowing more time to focus on content creation.

## References

- [Hugo Official Documentation](https://gohugo.io/)
- [Cloudflare Pages](https://pages.cloudflare.com/)
- [GitHub Actions](https://github.com/features/actions)