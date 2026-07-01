DevFlow — Landing Page

A landing page for DevFlow, a fictional cloud task manager for programming teams. Built as a Bootstrap 5 course project, inspired by a reference template but with our own subject, content, and design.

To view: just open index.html in a browser, no build step needed.

The idea

DevFlow's pitch is a task board that updates itself as your team writes code — merge a PR and the card moves to "Done" on its own. The design leans into that: a kanban board is the hero visual, and status colors (backlog / in progress / review / done) repeat as a small design system throughout the page.

Tech

Bootstrap 5.3 (CDN) — grid, navbar, carousel
Bootstrap Icons + Google Fonts (Space Grotesk, Plus Jakarta Sans, JetBrains Mono)
No build tools, no custom JavaScript — all interactivity (mobile menu, scroll-spy nav, testimonial carousel) runs on Bootstrap's own data-bs-\* attributes

Sections

Navbar → Hero → Trusted-by strip → Features → How it works → Product showcase → Testimonials (carousel) → Pricing → CTA → Footer

Notes

Fully responsive; fixed an early bug where the kanban grid overflowed on mobile (minmax(0,1fr) on the grid columns).
Palette, typography, and the kanban-flow concept are original — only the general section order follows the reference template, as required by the assignment.

Credits

Structure inspired by Bootsland (reference template from the assignment). Everything else is original work.
