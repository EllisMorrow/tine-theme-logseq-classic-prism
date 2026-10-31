# Local check summary

- Theme: Logseq Classic · Prism 0.1.1
- Manifest SHA-256: `149ca374b9a5681084cb72643b678bd7431215c60c21972267f3c64cf3267327`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 10.46:1, title 18.51:1, link 5.75:1, tag 5.75:1, code 9.77:1, mark 13.43:1, chosen 7.63:1.
  - Dark: body 7.05:1, title 5.61:1, link 7.08:1, tag 7.08:1, code 7.81:1, mark 13.43:1, chosen 4.55:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
