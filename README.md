# Academic PPT Pipeline

A personal Codex skill for turning literature, guidelines, or approved product information into an evidence-grounded academic presentation through three confirmed stages:

1. A page-by-page outline in table form.
2. Three ImageGen visual directions followed by a confirmed set of individual slide visuals.
3. A high-fidelity editable PowerPoint deck with native charts and validation.

The workflow keeps the confirmed story, evidence, visuals, and final PPTX aligned. It supports dynamic slide counts, global and per-slide density controls, source citations, Windows PowerPoint compatibility, and explicit confirmation gates.

## Install

Clone the repository into your personal Codex skills directory:

```bash
git clone https://github.com/cypress22202-hub/academic-ppt-pipeline.git ~/.codex/skills/academic-ppt-pipeline
```

Start a new Codex task if the skill list does not refresh immediately.

## Use

Invoke it explicitly:

```text
$academic-ppt-pipeline
```

It can also be selected automatically for requests to build a sourced academic presentation from literature, guidelines, or product materials.

## Key safeguards

- User confirmation is required after the outline, visual direction, and complete individual-slide visual set.
- Image-generated text and chart values are never treated as factual sources.
- Quantitative charts in the final PPTX must remain natively editable.
- Full-slide images cannot be used to simulate an editable deck.
- External evidence must be authoritative and explicitly cited.
