# A1Gh0st GitHub Pages: Style and Readability Rules

## Purpose
Keep all portfolio pages visually consistent with the A1Gh0st dark navy/cyan theme, including long technical learning journals.

## Known rendering problem
**Observed on the November 20, 2026 Kali Linux lesson page:** The "Commands Covered" Markdown table and fenced Bash example rendered with bright white or near-white backgrounds while the text remained light. This made both elements difficult to read.

**Cause to avoid:** Unstyled Markdown tables and fenced code blocks are transformed by Jekyll/GitHub Pages and may inherit the site's default light-theme styles. Styling only the page's `body` and generic `pre, code` selectors is not sufficient to guarantee readable output.

## Required style rules
1. **Contrast comes first.** Table headers, every alternating row, code panels, inline commands, and borders must be legible on the actual deployed website.
2. **Technical data:** Prefer dark HTML/CSS grid components with explicitly set header, row, and cell backgrounds/text colors over raw Markdown tables. Keep columns aligned, borders consistent, and wide content horizontally scrollable on phones.
3. **Command examples:** Prefer a dedicated dark terminal panel with a dark code background and light monospace text over an unstyled triple-backtick block. Preserve whitespace and make long lines scroll horizontally.
4. **Fallback protection:** The site stylesheet `assets/main.scss` includes high-specificity dark overrides for Markdown tables and highlighted code blocks. Do not remove these overrides without a deployed-site visual test.
5. **Use the established palette:** page `#090d16`, dark cards `#101827`, alternating rows `#142236`, headers `#173047`, cyan accent `#00e5ff`, readable text `#e2e8f0`.
6. **Accessibility:** Ensure good text/background contrast; supply labels for any grid using `role="table"` and make code blocks selectable.
7. **Content integrity:** Do not imply Kali commands were actually run, vulnerabilities confirmed, or a lab completed unless supported by evidence. Keep dates, source links, and status accurate.
8. **Privacy:** Do not publish personal names, real user directories, hostnames, MAC addresses, API keys, tokens, or private network identifiers unintentionally.

## Release checklist for each new technical report
- [ ] Open the **deployed GitHub Pages URL** after it builds, not only the GitHub Markdown preview.
- [ ] Inspect table header colors, every row, cell borders, command styling, and all code blocks.
- [ ] Check desktop and narrow/mobile layouts for clipping and horizontal scroll behavior.
- [ ] Confirm no white or washed-out content panels remain against the dark background.
- [ ] Verify links and page navigation still work.
- [ ] Compare technical claims with the actual learning transcript and submitted screenshots.

## Where the fix was applied
- `kali-virtualbox-2026-11-20.md`: Replaced the unreadable Markdown commands table with a dark responsive command grid; replaced the default Bash code fence with a dark terminal example.
- `assets/main.scss`: Added site-wide table/highlight color safeguards.

**Note:** Repository changes alone do not prove that the site has visually rendered correctly; confirm after GitHub Pages finishes rebuilding.
