# Tailwind CSS @apply Directive Bug with Pseudo-selectors

This repository demonstrates a bug in Tailwind CSS where the `@apply` directive fails to apply styles containing pseudo-selectors like `:hover`, `:focus`, and `:active`.  The issue is specifically when those pseudo-selectors are used within a custom style directive. 

The `bug.css` file shows the problematic code, and `bugSolution.css` presents a workaround. This bug can lead to unexpected behavior and inconsistencies in your styling, particularly when using custom style directives.

## Reproduction Steps

1. Clone this repository.
2. Compile the CSS (if necessary).
3. Observe the unexpected behavior in the example HTML (or your own, emulating the problem)
4. Compare to the solution's behavior

## Workaround

See the `bugSolution.css` file for a workaround that avoids using `@apply` in scenarios with pseudo-selectors inside custom styles.