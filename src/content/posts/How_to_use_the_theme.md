---
title: How to Use the Theme
description: A comprehensive guide on how to use and customize the Adu Blog theme
pubDate: 2024-04-21
author: duchengbin-cg
type: post
tags:
    - guide
    - documentation
    - theme
---

# How to Use the Theme

This guide will help you understand how to use and customize the Adu Blog theme for your own projects.

## Getting Started

1. Clone the repository
2. Install dependencies
3. Start the development server

## Customization

### Site Configuration

The main site configuration can be found in `src/consts.ts`. Here you can modify:
- Site name
- Author information
- Social media links

### Styling

The theme uses UnoCSS for styling. You can customize the styles by modifying:
- `uno.config.ts` for global styles
- Individual component styles in the `src/components` directory

### Content

To add new content:
1. Blog posts go in `src/content/posts`
2. Projects go in `src/content/projects`
3. Authors go in `src/content/authors`

## Deployment

The theme is designed to work with any static site hosting service. We recommend:
- Vercel
- Netlify
- GitHub Pages

## Support

If you encounter any issues or have questions, please:
1. Check the documentation
2. Open an issue on GitHub
3. Contact the maintainers