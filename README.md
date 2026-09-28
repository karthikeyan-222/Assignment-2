# Flexbox Quest

A mini game interface built with only HTML and CSS Flexbox. It is a visual layout, not a playable game.

## Files

```text
flexbox-quest/
├── index.html    page structure
├── style.css     all styling and layout
├── README.md     this file
└── VIVA.md       viva questions and answers
```

## How to run

1. Put all files in one folder.
2. Open `index.html` in a browser (double-click it).
3. Resize the window to see the responsive layout.

## Page sections

| Section | HTML tag | Class | What it shows |
| --- | --- | --- | --- |
| Header | `<header>` | `game-header` | Title, Lives, Coins, Level, Score, Pause and Menu buttons |
| Game area | `<section>` | `game-area` | Message, player, star, three platforms |
| Controls | `<div>` | `panel controls` | Arrow buttons and Jump button |
| Inventory | `<div>` | `panel inventory` | Eight items that wrap onto new lines |
| Quest | `<div>` | `panel quest` | Three quests with progress on the right |
| Display Lab | `<section>` | `display-lab` | Block, inline, inline-block and flex experiment |
| Footer | `<footer>` | `game-footer` | Footer text |

## CSS concepts used

| Concept | Where it is used |
| --- | --- |
| `display: flex` | Header, game area, scene rows, panels, controls, inventory, quest items |
| `display: block / inline / inline-block` | Display Lab (`.box`, `.tag`, `.chip`) |
| `flex-direction` | Column in `.game-area`, `main` and the media query |
| `justify-content` | Header, scene rows, control rows, quest items |
| `align-items` | Header, game area, control rows, quest items |
| `flex-wrap` | `.inventory-items`, `.game-header`, `.game-info` (mobile) |
| `gap` | Header, panels, inventory, controls |
| `flex: 1` | `.panel` and `.flex-demo .box` |
| Margin and padding | Every section and panel |
| Border and border-radius | Header, panels, items, buttons |
| Background color, color, font-size, font-family, width, height | Throughout `style.css` |
| `@media (max-width: 768px)` | Bottom of `style.css` |

## Responsive behavior

| Screen width | Result |
| --- | --- |
| 1440px and 1024px | Three panels in one row |
| 768px and below | Panels stack in one column, header stacks, platforms and player shrink |
| 375px | Everything stacked, no horizontal scrolling |

## Assignment rules followed

- HTML and CSS only
- No CSS Grid
- No `position: absolute` or `position: fixed`
- No JavaScript
- No CSS framework
- No random margins used to force positions