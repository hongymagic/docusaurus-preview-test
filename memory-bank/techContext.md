# Technical Context

## Technology Stack
- Docusaurus 3.x
- TypeScript
- React
- MDX
- Biome (for linting and formatting)

## Development Setup
1. Package Management
   - PNPM workspace structure
   - Workspace packages in /packages
   - Documentation in /docs

2. Build Tools
   - TypeScript compiler
   - Biome for code quality
   - Lefthook for git hooks

3. Development Environment
   - VSCode configuration provided
   - Recommended extensions
   - Debugging configurations
   - Task definitions

## Technical Constraints
1. Code Quality
   - Strict TypeScript mode
   - Biome linting rules
   - Consistent code formatting

2. Documentation Structure
   - Markdown/MDX files
   - Organized directory structure
   - Version-controlled content
   - Sidebar configuration

3. Performance Requirements
   - Fast build times
   - Optimized asset loading
   - Efficient search functionality
   - Mobile responsiveness

## Dependencies
1. Core Dependencies
   - @docusaurus/core
   - @docusaurus/preset-classic
   - React
   - TypeScript

2. Development Dependencies
   - @biomejs/biome
   - lefthook
   - TypeScript compiler
   - VSCode configurations

3. Project Structure
   ```
   /
   ├── docs/               # Docusaurus project
   │   ├── blog/          # Blog posts
   │   ├── docs/          # Documentation
   │   ├── src/           # Custom components
   │   └── static/        # Static assets
   ├── packages/          # Workspace packages
   └── memory-bank/       # Project documentation
   ```

## Configuration Files
1. Root Level
   - biome.jsonc (Biome configuration)
   - pnpm-workspace.yaml (Workspace config)
   - lefthook.yml (Git hooks)
   - .editorconfig (Editor settings)

2. Docusaurus Config
   - docusaurus.config.ts
   - sidebars.ts
   - tsconfig.json

3. VSCode Settings
   - settings.json
   - extensions.json
   - launch.json
   - tasks.json
