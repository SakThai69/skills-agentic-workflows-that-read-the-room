```markdown
# skills-agentic-workflows-that-read-the-room Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill demonstrates how to develop agentic workflows in TypeScript that can "read the room"—that is, interpret context and adapt behavior accordingly. The repository showcases clean code conventions, structured commit messages, and modular code organization without reliance on a specific framework. It is ideal for developers seeking to build context-aware automation or agentic systems.

## Coding Conventions

### File Naming
- **Style:** kebab-case
- **Example:**  
  ```
  agent-context-manager.ts
  room-state-reader.ts
  ```

### Import Style
- **Style:** Relative imports
- **Example:**
  ```typescript
  import { analyzeRoom } from './room-analyzer';
  ```

### Export Style
- **Style:** Named exports
- **Example:**
  ```typescript
  export function readTheRoom(context: RoomContext): RoomState { ... }
  ```

### Commit Messages
- **Pattern:** Conventional commits with `chore` prefix
- **Example:**
  ```
  chore: update room state analyzer logic
  ```

## Workflows

### [No Explicit Workflows Detected]
There are currently no automated workflows (such as CI/CD or linting) detected in this repository.

## Testing Patterns

- **Test File Pattern:** `*.test.*`
- **Testing Framework:** Not explicitly detected
- **Example:**
  ```typescript
  // room-analyzer.test.ts
  import { analyzeRoom } from './room-analyzer';

  describe('analyzeRoom', () => {
    it('returns correct room state', () => {
      // test implementation
    });
  });
  ```

## Commands

| Command | Purpose |
|---------|---------|
| /read-the-room | Analyze current context and return room state |
| /run-tests     | Execute all test files matching *.test.*      |
| /update-agent  | Update agent logic based on new requirements  |
```