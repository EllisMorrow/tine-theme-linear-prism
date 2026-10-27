# Local check summary

- Theme: Linear · Prism 0.1.1
- Manifest SHA-256: `9e7e404562a05400721c7aa13e488ba30a8b2fcf4f1323dd45c2f2d64a67faa4`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 12.26:1, title 12.26:1, link 5.39:1, tag 5.39:1, code 11.13:1, mark 10.6:1, chosen 10.49:1.
  - Dark: body 14.57:1, title 14.57:1, link 5.3:1, tag 5.3:1, code 12.88:1, mark 12.9:1, chosen 12.76:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
