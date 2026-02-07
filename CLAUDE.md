# IDEO Design Method Cards Skill

## Project Structure

This is a Claude Code skill (not a traditional codebase). The skill helps users apply IDEO's 51 Design Method Cards for product design, user research, and workshop planning.

- `SKILL.md` — Main skill file with interaction logic, classification engine, and four operating modes
- `references/method-database.md` — All 51 methods with structured metadata
- `references/facilitation-guides.md` — Step-by-step facilitation playbooks
- `references/combination-recipes.md` — Pre-designed method sequences for common scenarios
- `references/workshop-templates.md` — Output templates for artifacts
- `examples/` — Sample outputs demonstrating skill usage

## Key Design Decisions

- Methods are categorized using IDEO's original four lenses: LEARN, LOOK, ASK, TRY
- Recommendations always span 2+ categories to fight lens bias
- Quick mode caps at 5 methods to prevent decision paralysis
- Every recommendation includes rationale, time estimates, and adaptation tips
- The challenge classification engine maps user signals to methods via a decision matrix

## Editing Guidelines

- When adding or modifying methods, update both `method-database.md` and `facilitation-guides.md`
- Method metadata fields must stay consistent across all entries (category, phase, duration, team size, difficulty, remote-friendliness, budget)
- Combination recipes in `combination-recipes.md` should only reference methods that exist in the database
- Workshop templates use `{{PLACEHOLDER}}` syntax for dynamic content
