# Building with AI

I use AI to accelerate implementation while keeping problem definition, constraints, decision rules, and validation explicit.

## Working loop

1. **Define the problem** — Write down the user, workflow, and outcome before choosing a solution.
2. **Set constraints** — Make scope, safety, provenance, and known limitations explicit.
3. **Specify decision rules** — Turn judgment calls into testable rules where possible.
4. **Implement with AI** — Use AI tools to draft, code, troubleshoot, and iterate faster.
5. **Validate the workflow** — Check the result against the intended use, not just whether the output looks complete.
6. **Document the boundary** — State what works, what remains a prototype, and what still needs verification.

## Before I call something done

- The output addresses the original workflow, not just the prompt.
- Important assumptions and decision rules are visible.
- Claims are traceable to evidence or clearly labeled as examples.
- Known limitations and unfinished pieces are documented.
- A future reader can tell what was validated and what was not.

## Iteration rule

When validation exposes a gap, I change the smallest useful thing that addresses it, then validate again. That keeps iteration tied to evidence instead of adding scope by default.

This is the operating method behind the projects and experiments I publish here.