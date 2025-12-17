# AL Development Instructions

Two minimal, focused instruction files for Per Tenant Development in Business Central AL.

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

Choose one location based on your setup:

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

These files guide Claude Code in understanding your development standards. Place them in your preferred location and Claude will apply these guidelines when working with your AL project.

**Start simple, evolve based on your team's experience and needs.**
