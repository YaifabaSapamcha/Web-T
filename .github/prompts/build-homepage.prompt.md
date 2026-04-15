---
name: build-homepage
description: Generate a dark premium style homepage HTML with links to specified HTML files. Use when: creating a homepage that connects multiple HTML pages with a luxurious dark theme.
---

Generate a complete HTML page for a homepage with the following structure and styling:

## Layout and Sections
1. **Hero Section**: Full black background, large white centered text "Welcome to My Website", minimal grey subtitle "Explore the pages below".

2. **Cards Section**: Display links to the HTML files as cards. Each card should have:
   - Charcoal background (#1C1C1C)
   - Rounded corners (12-16px)
   - Soft shadow or glow
   - White text for the file name (e.g., "Q1", "Q2", etc.)
   - Links to {{files}} (provide the list of files, e.g., "Q1.htm, Q2.htm, ..., Q12.htm")

3. **CTA Section**: Inverted style with white background, black text, perhaps "Get Started" or similar.

## Color Palette
- Pure black: #000000 (main background)
- Charcoal: #1C1C1C (cards/sections)
- Dark grey: #2A2A2A
- Light grey: #B0B0B0 (secondary text)
- White: #FFFFFF (headlines)

## Requirements
- Make it responsive with basic CSS (flexbox or grid).
- Include proper HTML structure with <!DOCTYPE html>, <head>, <body>.
- Add minimal inline CSS for the dark premium style.
- Ensure links open in the same tab or new tab as appropriate.

Output the full HTML code.