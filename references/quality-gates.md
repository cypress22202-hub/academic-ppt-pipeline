# Quality gates

## Cross-stage checks

- Current artifacts match the manifest stage and locked version.
- Page count, order, titles, and page functions match the locked outline.
- All external additions have exact citations.
- No downstream artifact was retained after an upstream locked artifact changed.

## Visual-set checks

- Exactly one independent 16:9 image exists for every slide.
- Prominent text is readable; key values and chart relationships are correct.
- Layout, spacing, color, chart, icon, footer, and page-number systems are consistent.
- No duplicate, missing, or extra slide and no unauthorized visual asset.

## PPTX checks

- Slide count and slide size are exact.
- Titles, data, units, dose order, negative signs, percentages, confidence intervals, P values, and special characters match the source.
- Text has no overflow, clipping, collision, unintended wrapping, or missing glyphs.
- Quantitative charts are native and editable; chart screenshots are rejected.
- All practical layout elements can be individually selected and edited.
- Raster use is limited to approved complex visuals and never covers the whole slide.
- Speaker notes contain relevant source citations.

Render every final slide and compare it side by side with the confirmed visual for composition, module boundaries, visual focus, whitespace, color, line weight, chart relationships, and crop quality. Iterate until material deviations are resolved.

Run the Presentations finalizer with explicit slide count, expected slide size, approved font families, and required native-chart owner slides. Treat structural or layout findings as failures. Review warnings manually and eliminate avoidable warnings before delivery.

