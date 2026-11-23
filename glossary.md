# Glossary

Plain-English definitions of the technical terms I've run into, with where I met each one.

| Term | Plain-English meaning | Where I saw it |
|------|-----------------------|----------------|
| CSS variable | A named value defined once, like `--accent`, and reused with `var(--accent)`. Change one line and every place that uses it changes. | The color list at the top of my website's CSS |
| Cascade | The rule for which CSS wins when several rules touch the same element. Later and more specific rules beat earlier, general ones. | My toggle bullets picked up divider lines meant for the Experience list until I overrode them |
| Specificity | How precisely a CSS selector points at an element. More precise selectors win, regardless of order. | The `li:last-child` rule that kept re-adding a border |
| Flexbox | A layout mode that arranges items in a row or column, with wrapping and spacing handled for me. | The tag pills and buttons on my website |
| Grid | A layout mode with rows and columns. | The "What I bring" cards: one column on a phone, two on a desktop |
| Media query | A CSS condition that applies rules only on certain screens or settings. | Wide screens (720px and up), devices with a mouse, and visitors who prefer less motion |
| Semantic tags | HTML tags that say what content is (`header`, `main`, `section`, `footer`), not just how it looks. | The structure of my website's page |
| details/summary | Native HTML for a show-and-hide block. Closed by default, no JavaScript needed. | The "Show details" toggles on my Experience cards |
| Commit vs push | A commit saves a snapshot on my computer. A push uploads it to GitHub, where others can see it. | The toggle commit sat unpushed until the next push |
| Squash | Combining several commits into one. It rewrites history, so I avoid it after pushing. | Offered when a commit message named two changes but held one |
| Line endings (LF/CRLF) | Windows and Unix mark the end of a line differently. Git warns when it converts between them. | The harmless warning on nearly every commit |
| GitHub Pages rebuild | After a push, GitHub republishes the site. It takes a minute or two to go live. | Every website push |
| `aria-labelledby` | An attribute that tells screen readers which heading names a section. | The "What I bring" section |
| `:focus-visible` | Styles the outline shown when someone navigates with a keyboard. | The outline on my links, buttons and toggles |
| `prefers-reduced-motion` | A media query for visitors who ask their device to limit animation. | The fade-in and card-lift effects |
