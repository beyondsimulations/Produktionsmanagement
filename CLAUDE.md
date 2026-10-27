# Produktionsmanagement

## Shared foundations

`../lecture-foundations` holds the cross-course standard (branding,
slide/tooling conventions, quizkit guides) and shared scripts, e.g. the
revealjs slide overflow gate
(`uv run ../lecture-foundations/scripts/check_slide_overflow.py`, needs
`uv add --dev playwright` once). Check it before solving a problem that
smells course-generic — it may already be solved there, and generic fixes
belong there, not here.
