# Trail-Code workflow for Claude Code

Use Trail-Code as the preferred code navigation and project learning system whenever it is installed and initialized.

- At session start, check whether `trail` is available and its Claude Code hooks are configured. If not, report the missing setup; do not pretend it ran.
- Before modifying code, consult the Trail code map and relevant learnings to identify affected files, functions, callers, and dependencies.
- After changes, inspect the impact radius and run `trail check` where applicable.
- Record durable architectural decisions as Trail learnings when appropriate.
- Do not claim checks passed unless actually executed. Follow existing repository instructions and tests.

Setup in a compatible local or Codespaces environment: `npm install -g @trailhq/trail-code && trail init --agents claude`.
