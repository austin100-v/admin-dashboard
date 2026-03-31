# Admin Dashboard

A responsive admin dashboard built with vanilla HTML, CSS, and SVG icons — no frameworks or dependencies required. This project is done as an assignment from The Odin Project. Go to www.theodinproject.com to learn more about web programming

## Preview

The dashboard features a three-panel layout:
- **Sidebar** — navigation and settings links with icon support
- **Header** — search bar, notifications, user profile, and quick-action buttons
- **Main Content** — project cards, announcements, and a trending section

## Project Structure
```
admin-dashboard/
├── index.html
├── style.css
└── resources/
    ├── account-circle.svg
    ├── account-group.svg
    ├── bell-ring-outline.svg
    ├── card-account-details-outline.svg
    ├── cog.svg
    ├── eye-plus-outline.svg
    ├── help-box.svg
    ├── history.svg
    ├── home.svg
    ├── magnify.svg
    ├── message-reply.svg
    ├── note-multiple.svg
    ├── shield-check.svg
    ├── source-fork.svg
    ├── star-plus-outline.svg
    └── view-dashboard.svg
```

## Features

- **Sidebar Navigation** — Home, Profile, Messages, History, Tasks, Communities, Settings, Support, and Privacy links
- **Top Header** — Search input, notification bell, and user profile display
- **Project Cards** — Grid layout with title, description, and action icons (star, watch, fork)
- **Announcements Panel** — Stacked announcement entries with dividers
- **Trending Section** — List of trending users and their projects

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Layout (CSS Grid & Flexbox), custom properties, responsive styling |
| SVG | All icons via inline/external `.svg` files |
| Google Fonts | Roboto typeface |

## CSS Custom Properties

Theming is controlled via CSS variables defined in `:root`:
```css
--sidebar-color: #009be2;       /* Sidebar background */
--sidebar-text-color: #fff;     /* Sidebar text and card backgrounds */
--main-bg-color: #d4d4d4;       /* Main content background */
--left-border-color: #ff9100;   /* Project card accent border */
```

## Getting Started

No build tools needed. Just clone and open in a browser:
```bash
git clone https://github.com/your-username/admin-dashboard.git
cd admin-dashboard
open index.html
```

## Customization

- Swap out the user name (`Morgan Oakley`) in `index.html` to personalize the profile
- Update `--sidebar-color` in `style.css` to retheme the entire sidebar instantly
- Add or remove project cards by duplicating the `.project-card` block in `index.html`