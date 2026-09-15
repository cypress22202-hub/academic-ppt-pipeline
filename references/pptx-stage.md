# Stage 3: Editable PPTX reconstruction

## 1. Establish authorities

- Content authority: locked outline plus original evidence.
- Design authority: confirmed individual slide visuals.
- Accuracy authority for ambiguous symbols and data: original official PDF, guideline, label, or regulator document.

Do not redesign, rewrite the narrative, change page count, or use a visual-generation artifact as a factual source.

## 2. Build the presentation system

Use the Presentations workflow to create the requested aspect ratio, normally 16:9. Reconstruct the confirmed background, margins, title hierarchy, bilingual typography, colors, chart styles, modules, footer, and folio system consistently.

Choose fonts that remain usable in Windows PowerPoint. Verify CJK coverage, substitution behavior, line wrapping, and special symbols. Prefer common Windows families when they preserve the confirmed design.

## 3. Native editability requirements

Create these as native PowerPoint objects whenever present:

- Chinese and English titles, body copy, captions, values, units, axes, legends, and page numbers;
- fills, borders, dividers, brackets, arrows, connectors, cards, and callouts;
- timelines, participant flows, clinical pathways, process diagrams, and mechanism models;
- every quantitative chart and its literal editable data.

Name or group elements by logical role where the presentation API permits it so that titles, numbers, colors, arrows, data, and flow nodes can be edited independently.

Raster images are allowed only for genuinely complex medical/scientific illustrations, microscopy, photographs, subtle texture, or artwork that cannot be stably reconstructed with basic shapes. Crop them cleanly and retain adequate resolution. Never place the complete slide visual as a background or full-slide image.

## 4. Evidence and notes

Add relevant citations to speaker notes. Keep material qualifications visible when they affect interpretation, including hypothesis labels, exploratory analyses, historical controls, and nonconcurrent comparisons.

Do not introduce an external logo, brand asset, person, product packaging, UI, or claim unless explicitly supplied or approved.

## 5. Output

Deliver one final editable `.pptx`. Keep rendered previews, contact sheet, and validation receipt as QA artifacts unless the user requests them. Use a clear filename based on the project slug and selected visual direction.

