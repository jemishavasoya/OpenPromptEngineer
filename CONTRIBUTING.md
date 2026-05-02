# 🤝 Contributing to OpenPromptEngineer

Thank you for considering contributing to OpenPromptEngineer! This document outlines the guidelines for submitting UI components and AI prompts.

---

## 📋 Table of Contents

- [How to Contribute](#how-to-contribute)
- [UI Component Submission Guidelines](#ui-component-submission-guidelines)
- [AI Prompt Submission Guidelines](#ai-prompt-submission-guidelines)
- [Pull Request Process](#pull-request-process)
- [Code of Conduct](#code-of-conduct)

---

## 🚀 How to Contribute

1. **Fork** this repository
2. **Clone** your fork to your local machine
3. Create a **new branch** for your contribution (`git checkout -b feature/my-awesome-component`)
4. Make your changes following the guidelines below
5. **Commit** your changes (`git commit -m 'Add awesome hero section'`)
6. **Push** to your branch (`git push origin feature/my-awesome-component`)
7. Open a **Pull Request**

---

## 🎨 UI Component Submission Guidelines

### ✅ Required Files

Every UI component submission **MUST** contain **TWO files** inside its own folder:

1. **Code file** - The actual implementation
   - `code.dart` (for Flutter)
   - `code.tsx` (for React)
   - `code.html` (for HTML/CSS)

2. **Visual preview** - A screenshot or recording
   - `preview.png` OR `preview.gif`
   - Must clearly show what the component looks like
   - Recommended size: 1200x800px or similar aspect ratio

### 📁 Folder Structure Example

```
ui-prompts/
└── flutter/
    └── gradient-hero-section/
        ├── code.dart
        └── preview.png
```

```
ui-prompts/
└── react-tailwind/
    └── animated-landing-hero/
        ├── code.tsx
        └── preview.gif
```

### 📝 Naming Conventions

- **Folder names**: Use kebab-case (e.g., `gradient-hero-section`, `animated-card-stack`)
- **File names**: Always use `code.[extension]` and `preview.[png|gif]`
- Be descriptive but concise

### 🎯 Component Requirements

- **Self-contained**: Component should work with minimal dependencies
- **Commented**: Add brief comments explaining key sections
- **Responsive**: UI should work on different screen sizes (when applicable)
- **Clean code**: Follow the language/framework best practices
- **No external assets**: Avoid dependencies on external images/fonts unless absolutely necessary

### ❌ What NOT to Submit

- Components without preview images
- Copyrighted or plagiarized code
- Malicious or inappropriate content
- Incomplete or broken code
- Components with excessive dependencies

---

## 🤖 AI Prompt Submission Guidelines

### ✅ Required Files

Every AI prompt submission **MUST** contain:

1. **Prompt file** - The actual prompt text
   - `prompt.txt` or `prompt.md`

2. **Example output** - Visual result from the prompt
   - `example.png` or `example.jpg`
   - Shows what the prompt generates

### 📁 Folder Structure Example

```
ai-prompts/
└── midjourney/
    └── cyberpunk-cityscape/
        ├── prompt.txt
        └── example.png
```

### 📝 Prompt Requirements

- **Clear and specific**: Prompt should be well-structured
- **Reproducible**: Others should get similar results
- **Documented**: Include any special parameters or settings used
- **Original**: Don't copy prompts verbatim from paid sources

---

## 🔄 Pull Request Process

1. **Ensure your submission follows all guidelines above**
2. **Test your code** before submitting
3. **Write a clear PR title**: e.g., "Add gradient hero section for Flutter"
4. **Describe your submission** in the PR description:
   - What does it do?
   - Any special features or techniques used?
   - Screenshot/GIF (if not already in the folder)

5. **Wait for review**: Maintainers will review your PR and may request changes
6. **Respond to feedback**: Address any requested changes promptly

### PR Title Format

- ✅ Good: `Add animated landing hero for React + Tailwind`
- ✅ Good: `Add cyberpunk cityscape prompt for Midjourney`
- ❌ Bad: `Update`
- ❌ Bad: `New component`

---

## 🛡️ Code of Conduct

### Our Standards

- Be respectful and inclusive
- Provide constructive feedback
- Focus on what is best for the community
- Show empathy towards other contributors

### Unacceptable Behavior

- Harassment or discriminatory language
- Trolling or insulting comments
- Publishing others' private information
- Any conduct that would be inappropriate in a professional setting

---

## ❓ Questions?

If you have questions about contributing, feel free to:
- Open an issue with the `question` label
- Reach out to the maintainers

---

## 🌟 Recognition

All contributors will be featured in our README's **Core Contributors** section. Your GitHub avatar will be displayed as a thank you for your contribution!

---

**Thank you for making OpenPromptEngineer better! 🚀**
