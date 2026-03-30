# AL Development Instructions

Two minimal, focused instruction files for Per Tenant Development in Business Central AL.

> **Note:** These are demonstration instruction files — published to share the concept and approach, not as production-ready standards. They reflect how I structure VS Code Copilot instructions in my own AL development workflow. Use them as a starting point and adapt to your team's coding standards and project needs.

## Files

### `general.instructions.md`
Universal development principles and clean code practices:
- PTE context and development focus
- Core principles (YAGNI, KISS, DRY, Always Works™)
- Code organization and consistency
- Testing and error handling basics

### `al-best-practices.instructions.md`
AL-specific best practices covering:
- Code style and naming conventions
- 5 core performance optimization rules with examples
- Modern error handling patterns (ErrorInfo, TryFunctions)
- Events, extensibility, and documentation standards
- Code quality checklist

## Installation

VS Code - chose one location based on your setup:

### Option 1: Project-Level (Recommended for Team)
Add both files to your AL project's `.github/instructions/` folder:
```
YourProject/
├── .github/
│   └── instructions/
│       ├── general.instructions.md
│       └── al-best-practices.instructions.md
```

### Option 2: User-Level (VS Code Global)
Add both files to your user's VS Code prompts folder:
```
C:\Users\<username>\AppData\Roaming\Code\User\prompts\
```

## Usage

These files guide agent in understanding your development standards. Place them in your preferred location and agent will apply these guidelines when working with your AL project.

**Start simple, evolve based on your team's experience and needs.**

## License

MIT License

Copyright (c) 2026 Milos Baic

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
