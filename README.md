# kb-Phenomics

An LLM Wiki Obsidian vault for **Phenomics** research literature.

## Structure

```
.
├── ko/        # Korean notes
│   ├── articles/
│   └── pdf/
├── en/        # English notes
│   └── articles/
└── tools/     # Shared utilities (git submodule)
    └── git@github.com:taejoonlab/kb-tools.git
```

## Setup

1. Clone with submodules:
   ```bash
   git clone --recurse-submodules git@github.com:taejoonlab/kb-Phenomics.git
   ```

2. Open the folder as an Obsidian vault.

3. (Optional) Enable the Obsidian Git plugin for auto-commit and sync.

## Tools

The `tools/` directory is managed as a separate submodule repository. It is excluded from the Obsidian file explorer via `userIgnoreFilters` in `.obsidian/app.json`, but remains under git version control.
