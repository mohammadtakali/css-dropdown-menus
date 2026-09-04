# CSS Navigation Menus Collection

A collection of pure HTML & CSS navigation menu components — dropdown menus and full mega menus — built as a series of practice exercises, each one adding a new interaction pattern.

**[Live demo](https://mohammadtakali.github.io/css-dropdown-menus/)**

## What's inside

| # | Demo | Description |
|---|------|-------------|
| 01 | [Dropdown menu v1](01-dropdown-menu-v1/index1-menu.html) | Basic dropdown shown/hidden with `display: block/none` on hover. |
| 02 | [Dropdown menu v2](02-dropdown-menu-v2/index2-menu2.html) | Dropdown with a smooth `opacity` / `visibility` transition. |
| 03 | [Dropdown menu v3](03-dropdown-menu-v3/index3-menu3.html) | Dropdown that expands with an animated `height` transition. |
| 04 | [Dropdown with flyout](04-dropdown-with-flyout/index4-menu4.html) | Two-level dropdown with a nested right-side flyout submenu. |
| 05 | [Mega menu v1](05-mega-menu-v1/index5-MegaMenu.html) | Full-width mega menu using an `opacity` / `visibility` transition. |
| 06 | [Mega menu v2](06-mega-menu-v2/index5B-MegaMenu2.html) | Full-width mega menu that expands with a `height` transition. |
| 07 | [Final menu v1](07-final-menu-v1/index6-FinalMenu.html) | Mega menu that slides in from the side by animating `left`. |
| 08 | [Final menu v2](08-final-menu-v2/index6B-FinalMenu2.html) | Alternate timing/easing of the sliding mega menu. |
| 09 | [Mixing dropdown menu with mega menu](09-mixing-dropdown-with-megamenu/index7-mixing-dropdown-megamenu.html) | Right-aligned navbar combining a dropdown submenu and a mega menu in one nav. |

## Features

- Pure HTML & CSS — no JavaScript, no frameworks, no build step
- Uses native CSS nesting (`&:hover { ... }` inside selectors)
- Different show/hide techniques compared side by side: `display`, `opacity`/`visibility`, `height`, and `left` position transitions
- Responsive layout with Flexbox

## Tech stack

- HTML5
- CSS3 (Flexbox, CSS nesting, transitions)

## Running locally

No build tools or dependencies are required.

1. Clone the repository:
   ```bash
   git clone https://github.com/mohammadtakali/css-dropdown-menus.git
   cd css-dropdown-menus
   ```
2. Open `index.html` in your browser, or serve the folder with any static server, e.g.:
   ```bash
   npx serve .
   ```

## Browser support note

This project uses native CSS nesting syntax (`&` inside a selector block). It works in current versions of Chrome, Edge, Safari, and Firefox. If you need to support older browsers, the nested rules should be flattened into standard CSS selectors.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
