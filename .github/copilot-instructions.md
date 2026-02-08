# AI Coding Instructions for HTML ilk ders

## Project Overview

This is a beginner HTML learning project (Turkish: "HTML ilk ders" = "HTML first lesson"). Currently contains a minimal `index.html` file. This is a foundational project designed to teach HTML basics and is expected to grow with additional lessons and examples.

## Project Structure

- `index.html` - The main HTML entry point with a basic HTML5 template
- `.github/copilot-instructions.md` - This guidance file for AI agents

## Key Patterns & Conventions

### HTML Structure
- Follow HTML5 standards (`<!DOCTYPE html>`, proper `<meta>` tags for charset and viewport)
- Always use `lang="en"` or appropriate language code in `<html>` tag
- Include essential meta tags for character encoding and responsive design
- Use semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<footer>`, etc.) when content grows

### File Organization (as project expands)
- Keep related styles inline or in separate `styles.css` in the root directory
- Create `scripts/` directory for JavaScript files if needed
- Create `assets/` or `images/` directory for images and media
- Each lesson concept should have its own comment section or separate HTML file

### Accessibility & Best Practices
- Always include descriptive `<title>` tags
- Use proper heading hierarchy (`<h1>` → `<h2>` → `<h3>`)
- Include alt text for all images
- Test with browser DevTools (F12) for layout and console errors

## Development Workflow

- Open `index.html` directly in a browser (no build steps needed)
- Use browser dev tools (F12) to debug HTML, inspect elements, and test responsive design
- Refresh browser (Ctrl+Refresh or Cmd+Shift+R for hard refresh) to see changes
- For learning purposes, add comments above new concepts

## Learning Context

This project is for teaching HTML fundamentals. When adding content:
- Include explanatory comments for non-obvious HTML features
- Use clear, descriptive element names and IDs
- Build incrementally - don't overwhelm with complex structures
- Test in modern browsers (Chrome, Firefox, Safari, Edge)
