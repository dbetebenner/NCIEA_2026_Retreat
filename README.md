# AI-Supported Workflows — Brown-Bag (15 min)

Staff retreat brown-bag on AI-supported workflows. Built with the
[NCIEA Presentation Template](../../NCIEA_Presentation_Template).

## Present it

Open **`ai_workflows.html`** in any browser (self-contained, works offline).

- **`S`** — speaker view (per-slide notes + timer)
- **`F`** — fullscreen · **`O`** — overview · arrows / space to advance

## Arc (≈15 min, Q&A with the group at the end)

1. **What is a workflow?** — the real, undocumented sequence of steps; *you are the integration layer* across a dozen apps.
2. **Where structure exists** — how software teams made workflows named, automatic, and observable (a readable CI pipeline).
3. **How AI supports a workflow** — introspection first (*what am I actually doing?*), then AI at the seams; a high-level example of AI enabling **depth**, not just speed.
4. **Workflows loop** — feedback compounds; the same loop runs virtuous or vicious, and a human verification step sets the direction.

## Edit / re-render

```bash
quarto preview ai_workflows.qmd --to revealjs   # live preview
quarto render  ai_workflows.qmd --to revealjs   # rebuild ai_workflows.html
```

Requires [Quarto](https://quarto.org) ≥ 1.4. No R required.

## Files

```
ai_workflows.qmd     source
ai_workflows.html    rendered, self-contained deck (present this)
styles/              theme + figure lightbox
assets/fonts/        math font
Figures/             the four diagrams (SVG)
```
