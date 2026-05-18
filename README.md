Project Overview

This project is a redesign and implementation of a personal portfolio webpage. The goal was to take an existing layout, analyze its structure, and rebuild it using modern, semantic HTML and clean, organized CSS. The redesign emphasizes readability, visual hierarchy, and consistent styling across all sections, including About, Portfolio, and Contact.
The project also required matching a provided mockup as closely as possible. This included replicating the color palette, typography, spacing, and layout decisions. Flexbox was used to create a horizontal layout for the Portfolio section, and careful attention was given to alignment, spacing, and responsiveness. Throughout the process, I iterated on the design, debugged layout issues, and refined the structure to ensure the final result matched the mockup both visually and structurally.

Original vs. Revised Layout

Original Layout
• 	Sections stacked vertically with minimal styling
• 	No consistent spacing or typography
• 	Portfolio items displayed in a vertical column
• 	Contact section lacked structure and visual hierarchy
• 	No clear alignment or spacing rules

Revised Layout
• 	Clean, centered layout with consistent margins and padding
• 	Serif headings paired with sans‑serif body text for contrast
• 	Portfolio section redesigned using Flexbox to create a horizontal, evenly spaced layout
• 	Contact section styled to match the mockup, including numbered list alignment and spacing
• 	Improved color palette and borders for visual cohesion
• 	Images styled with borders and consistent sizing

Redesign Mock‑Up

The mockup guided:
• 	Section spacing
• 	Typography choices
• 	Background colors
• 	Portfolio layout (three items horizontally)
• 	Contact section formatting (centered intro + left‑aligned numbered list)

Implementation Plan
1. 	Rebuild HTML using semantic tags (, , , )
2. 	Apply global typography and color styles
3. 	Implement Flexbox for the Portfolio section
4. 	Style images and text blocks to match the mockup
5. 	Recreate the Contact section with proper list alignment
6. 	Debug spacing, alignment, and CSS overrides
7. 	Final pass to ensure visual consistency

Design Trade‑Offs
• 	Kept images in their original aspect ratio instead of forcing portrait cropping to preserve authenticity
• 	Balanced mockup accuracy with accessibility (e.g., readable font sizes, adequate contrast)
• 	Chose Flexbox over CSS Grid for simplicity and assignment requirements
• 	Avoided overly complex animations to maintain clarity and performance

AI Tools Used & Justification

Windsurf and Microsoft Copilot was used during development for:
• 	Debugging CSS layout issues (e.g., Flexbox not applying due to unsaved file)
• 	Explaining why global CSS rules affected specific sections
• 	Helping refine spacing and alignment to match the mockup
• 	Generating this README in a structured, professional format

Justification:
Windsurf and Copilot accelerated troubleshooting, provided clear explanations of CSS behavior, and helped ensure the final layout matched the mockup accurately. All code decisions were reviewed and implemented manually.

Key Decisions, Challenges & Learning Moments

Key Decisions
• 	Using a wrapper div () as the Flexbox container
• 	Keeping images uncropped to maintain original proportions
• 	Using  to fix spacing in the Contact section
• 	Applying section‑specific CSS to override global image rules

Challenges
• 	Flexbox layout not applying due to unsaved CSS file
• 	Global  rule overriding Portfolio image styling
• 	Numbered list spacing in the Contact section not matching the mockup
• 	Ensuring consistent spacing across all sections

Debugging & Troubleshooting Moments
• 	Ident