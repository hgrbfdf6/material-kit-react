# GitHub Copilot Usage Guide

## About GitHub Copilot

GitHub Copilot is an AI-powered coding assistant specifically designed to help developers write and maintain code more efficiently.

## What I Can Do

### 1. Code Writing & Modification
- Write new feature code
- Fix bugs
- Refactor existing code
- Add test cases
- Update documentation

### 2. Code Review
- Check code quality
- Identify potential issues
- Provide improvement suggestions
- Verify best practices

### 3. Project Maintenance
- Update dependencies
- Optimize build configurations
- Improve performance
- Fix security vulnerabilities

## Available Tools

### Development Tools
- **bash**: Execute command-line operations (build, test, run, etc.)
- **view**: View files and directory structure
- **edit**: Edit code files
- **create**: Create new files
- **grep/glob**: Search code content and files

### GitHub Integration Tools
- **list_commits**: View commit history
- **list_pull_requests**: Manage pull requests
- **list_issues**: View and manage issues
- **get_file_contents**: Get file contents
- **search_code**: Search code on GitHub

### Code Quality Tools
- **code_review**: Automated code review
- **codeql_checker**: Security vulnerability scanning
- **gh-advisory-database**: Check dependencies for security vulnerabilities

### Browser Tools
- **playwright**: Automated browser testing and UI validation

## Internet Access

I have **limited internet access**:
- ✅ Can access GitHub API and repositories
- ✅ Can access some allowed websites (via web_fetch tool)
- ❌ Many domains are restricted and cannot be directly accessed
- ❌ Cannot access internal network resources

If access to blocked domains is needed, users can be notified to request permissions.

## Model Information

I am a GitHub Copilot agent built on advanced AI language models, specifically optimized for software development tasks. My capabilities include:
- Understanding and writing multiple programming languages
- Understanding project context and codebase structure
- Following coding conventions and best practices
- Providing secure and high-quality code suggestions

## Working Principles

### Minimal Changes
I make the smallest, most precise changes possible to solve problems, avoiding unnecessary code modifications.

### Security First
- Automatically scan for security vulnerabilities
- Don't introduce new security issues
- Don't commit sensitive information to the codebase

### Quality Assurance
- Run existing test suites
- Verify code changes don't break existing functionality
- Follow project code style and conventions

## Limitations

### Cannot Do
- Cannot directly push code (must use report_progress tool)
- Cannot create new Pull Requests or Issues
- Cannot access private credentials
- Cannot execute force push or rebase operations
- Cannot modify other repositories

### Must Avoid
- Don't share sensitive data to third-party systems
- Don't commit keys or credentials to code
- Don't introduce security vulnerabilities
- Don't generate copyrighted content

## Application in This Project

This project is a Material-UI based React application template. I can help with:

1. **Develop New Features**: Add new pages, components, or functionality
2. **Fix Issues**: Solve bugs and technical problems
3. **Optimize Performance**: Improve code efficiency and loading speed
4. **Update Dependencies**: Safely update npm packages
5. **Improve UI/UX**: Optimize user interface and interaction experience
6. **Maintain Documentation**: Update and improve project documentation

## How to Collaborate with Me

1. **Provide Clear Requirements**: Describe in detail what you want to implement or solve
2. **Point Out Relevant Files**: If you know which files need to be modified, let me know
3. **Provide Context**: Share relevant background information and constraints
4. **Verify Results**: I will report progress, please verify changes meet expectations

## Contact and Support

If you have any questions or need specific help, please @githubcopilot in the issue, and I will respond promptly.

---

*This document was created on 2026-01-07 in response to questions in the PEG-748 daily sync issue.*
