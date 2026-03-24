# Calculator — AbnbCalc
GitHub: zee78900/abnbcalc (public)
Live: deployed as static HTML

---

## What This Is
Vacation rental true-cost calculator. Shows the all-in price of any STR stay including platform fees (Airbnb/VRBO/direct), taxes, pool heating, resort fees, pet fees, extra guest fees, and credit card processing.

---

## Files

| File | Purpose |
|---|---|
| `index.html` | Entire app — single HTML file (no build step) |
| `amortization_inputs/` | Amortization input data (local only) |
| `amortization_inputs.zip` | Zip backup |
| `Copy of Claude-by-Anthropic-for-Excel.xlsx` | Claude AI Excel add-in reference |
| `memory/` | Claude Code memory files (gitignored) |

---

## Usage
Open `index.html` in any browser. No server needed.

## For AI Agents
- Single-file app — all HTML, CSS, and JS in `index.html`
- Supports Airbnb, VRBO, and direct booking fee structures
- Has dark/light mode toggle, responsive layout
- `memory/` folder is Claude Code session memory — ignore for app purposes
