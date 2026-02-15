# Latreis Evals Development Workflow

This document describes the standard workflow for managing work in the Latreis Evals repository.

## Process Overview

1. **New work starts with GitHub issue**
   - All work begins with creating a GitHub issue
   - Issues should have appropriate labels and milestone assignments

2. **Issue gets assigned to agent**
   - Agents self-assign or are assigned to issues
   - Assignment indicates work has begun

3. **Agent updates issue as they work**
   - Progress updates posted as comments
   - Status labels updated as work progresses

4. **Code goes to repo**
   - Code changes submitted via pull requests
   - PRs reference the related issue

5. **Issue closed when code merged**
   - Issues are closed when the related PR is merged
   - Final verification that requirements are met

## Label System

- **Type**: `type:feature`, `type:bug`, `type:docs`, `type:refactor`
- **Component**: `component:pricing`, `component:storage`, `component:cli`, `component:integration`, `component:parser`
- **Priority**: `priority:critical`, `priority:high`, `priority:medium`, `priority:low`
- **Phase**: `phase:1`, `phase:2`, `phase:3`, `phase:4`
- **Status**: `status:backlog`, `status:ready`, `status:in-progress`, `status:review`, `status:done`

## Milestones

- **Phase 1: Foundation** (due 2026-02-28) - cost tracking, basic evals
- **Phase 2: Reporting** (due 2026-03-15) - dashboards, analytics
- **Phase 3: Automation** (due 2026-03-30) - automated evals
- **Phase 4: Team rollout** (due 2026-04-15) - multi-agent

## Best Practices

- Create an issue before writing code
- Keep issues focused on a single task
- Update status labels as work progresses
- Link PRs to issues
- Close issues when work is complete