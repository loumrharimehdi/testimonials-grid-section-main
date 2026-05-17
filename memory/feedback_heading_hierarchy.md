---
name: feedback-heading-hierarchy
description: When suggesting heading levels (h1-h6), favor semantic/document structure over visual size in the design. User pushed back when I suggested matching heading level to visual prominence.
metadata:
  type: feedback
---

In a testimonial card structure (`<article>` with author header + quote), user prefers `<h2>` for the author name and `<h3>` for the testimonial summary — even though visually the summary is larger than the name in the design.

**Why:** Heading hierarchy should reflect the logical structure of the document, not the visual size of the text. The author identifies the article (like a blog post title), and the summary is content within it. CSS handles visual size independently.

**How to apply:** When reviewing or suggesting heading levels, don't recommend swapping h2/h3 based on which one looks bigger in the design. Validate the user's semantic choice. Only suggest changes if the hierarchy is genuinely broken (e.g., skipping levels, multiple h1s, etc.).
