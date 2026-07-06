# Project Goal

## North Star

Provide a small, modern CSS reset that gives authors a practical starting point for accessible, predictable browser defaults while crediting and learning from community reset patterns.

## Who This Is For

This project is for CSS authors and maintainers who want a focused reset stylesheet they can read, copy, and adapt into their own sites and projects.

## Core Goals

- Keep `reset.css` focused on browser defaults that commonly get in the way of reliable page styling.
- Favor accessibility and user preferences, including readable text defaults, inherited form typography, responsive media behavior, stable scrolling behavior, and respect for platform font sizing.
- Use modern CSS when it improves the baseline experience, while making support expectations explicit through comments and linting.
- Document meaningful community influences and source material so maintainers can understand why a rule exists.
- Maintain a simple project shape: one primary reset file, lightweight documentation, and formatting/linting tools that make changes reviewable.
- Treat the repository as a copyable CSS resource rather than a JavaScript package with an application entry point.

## Success Looks Like

- The reset remains understandable enough to audit before use.
- Each rule has a clear reason to exist and avoids surprising project-specific styling.
- CSS linting and formatting stay clean.
- Browser support tradeoffs are intentional, especially for newer CSS properties.
- The README and source comments continue to credit relevant community work.
- Consumers can quickly decide whether the reset fits their project and how to adapt it.

## Non-Goals

- This is not a CSS framework, component library, design system, or utility class toolkit.
- This project should not prescribe a visual style, spacing scale, color system, typography scale, or layout system.
- The reset should not grow into a broad compatibility layer or polyfill collection for every browser difference.
- It should not hide opinionated application defaults behind the name of a reset.
- It should not add build complexity unless distribution needs clearly require it.

## Principles and Constraints

- Prefer plain CSS that is easy to inspect over generated output.
- Keep comments tied to rationale, browser support, or attribution rather than restating obvious declarations.
- Treat accessibility, readability, and user-controlled settings as constraints, not optional enhancements.
- Add new reset rules only when they solve a broadly shared authoring problem.
- Be cautious with defaults that depend on project-specific custom properties or external CSS.
- Preserve license clarity and attribution for all borrowed or adapted ideas.
- Use MIT as the authoritative project license.
- Avoid requiring consumer-defined custom properties for core reset behavior.

## Current Focus

The repository currently centers on `reset.css`, with npm metadata, Prettier, Stylelint, and Dependabot supporting maintenance. Near-term work should keep the reset concise, improve documentation where usage expectations are unclear.
