# NYC Landmarks

## Project Overview

The NYC Landmarks website is a place where people can explore six well-known landmarks around New York City. It will have photos, short introductions, and individual pages with more information and useful visitor links. I want it to feel clean and modern, with simple typography, natural colors, and spacing that makes the information easy to follow. The goal is to help people learn about the landmarks and find useful information whether they are planning at home or using their phone while out in the city.

## Target Audience

People who want information about some of New York City's major landmarks. They may be comparing places to visit while planning at home or looking up information on a phone while traveling around the city. The site should help them quickly understand what each landmark offers and find links to visitor information and directions.

## Goals

### User Goals

- Pick landmarks of interest by browsing images, short introductions, and more detailed landmark pages.
- Find links to directions, transportation, and visitor information to help plan a trip to a landmark.
- Scan headings, text, and navigation easily while using the site on the go.

### Creator Goals

- Improve my responsive web design skills by learning how to use media queries along with flexible layouts and images.
- Get more comfortable organizing a website with multiple pages and making the navigation easy to use.
- Finish a website that I can add to my portfolio and feel comfortable showing to other people.

## Scope of Work

A responsive NYC landmarks website with **seven pages total**:

- One home page, `index.html`.
- Six individual landmark pages, with landmark text, images, and links.

The site architecture is defined in the `site-map.md` file.

Reuse a consistent header, navigation, and footer across all pages. Link the home-page landmark cards to their detail pages and add Previous/Next links through the six landmarks. Combine fluid layouts and flexible media with media queries so the site works on small and large screens. Continue using the visual direction and styles documented in `design.md`.

The site is an informational guide. Ticket booking, accounts, live transit data, and a custom trip planner are outside this project's scope; link to appropriate visitor-information sources instead.

## Content Summary

| Page | Content |
| --- | --- |
| Home | Introduction to NYC landmarks, embedded video, featured landmark image and text, and six credited landmark cards linking to their pages. |
| Statue of Liberty | Introduction, hero image, About text covering its history and present use, and More Info links including visitor information and directions. |
| Empire State Building | Introduction, hero image, About text covering its history and present use, and More Info links including visitor information. |
| Staten Island Ferry | Introduction, hero image, About text covering its history and present use, and More Info links including schedules and directions. |
| Wonder Wheel | Introduction, hero image, About text covering its history and present use, and More Info links. Additional landmark images where applicable. |
| Yankee Stadium | Introduction, hero image, About text covering its history and present use, and More Info links including the visitor reference guide. |
| Roosevelt Island Tramway | Introduction, hero image, About text covering its history and present use, and More Info links including riding information and directions. |

Preserve the landmark text, links, and photo credits.

## Success Criteria

Use this checklist when building and reviewing the finished project.

- [ ] The home page and six landmark pages are complete and linked.
- [ ] Fluid layouts and flexible images/video adapt to the available space.
- [ ] Media queries produce appropriate mobile and desktop layouts; a tablet layout may be added where useful.
- [ ] Responsive navigation provides access to Home and all six landmarks on small and large screens.
- [ ] Every landmark page has its landmark name as the `h1`, a hero image, the landmark content and links, and working Previous/Next links.
- [ ] All pages reuse a consistent header, navigation, and footer.
- [ ] Typography follows a consistent hierarchy; colors and spacing make content easy to scan and agree with `design.md`.
- [ ] HTML uses semantic elements, including `header`, `nav`, `main`, and `footer`, with logical headings and links that describe their destinations.
- [ ] Informative images have meaningful alternative text, decorative images have empty alternative text, and text/background colors have sufficient contrast.
- [ ] Navigation and other controls work with the keyboard and have visible focus.
- [ ] Photo credits and source links are preserved, and internal links and file paths work on the published site.
- [ ] The site is checked at narrow and wide widths, HTML/CSS are validated, and the final version is committed and published.

## Documentation

- **[README.md](README.md)** — This project's overview, audience, goals, scope, content summary, and success criteria. Keep it current as project decisions change.
- **[site-map.md](site-map.md)** — The page list, exact filenames, shared page structure, and navigation relationships.
- **[design.md](design.md)** — The site's typography, colors, spacing, and other visual design decisions.
- **[.github/copilot-instructions.md](.github/copilot-instructions.md)** — Project-specific instructions for GitHub Copilot, including content preservation, development standards, and verification. The planning documents also support work without AI.


## Finished site implementation (Project 3)

The current build includes the home page and six individual landmark pages. Each landmark page uses the same navigation and footer, a responsive hero image, landmark background information, Google Maps and Apple Maps directions, an official visitor-information link, and previous/next navigation. The home page links to every landmark page.

### Responsive design

- Flexible images and video scale to their containers.
- CSS Grid creates a fluid landmark-card layout.
- Flexbox keeps the navigation and previous/next controls usable at different widths.
- Breakpoints at 900px and 600px adjust navigation and content layout.
- The hero `picture` element serves square images on smaller screens and original images on larger screens.

### Local preview

Open `index.html` in a browser. Keep `tokens.css`, `style.css`, all landmark HTML files, and the `images` folder together in the same project directory.
