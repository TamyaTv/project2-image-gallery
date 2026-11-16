# NYC Landmarks — Site Map

All seven HTML pages are in the project root. The home page links to each landmark page, and every page shares the same header, navigation, and footer.

| Page | Filename |
| --- | --- |
| Home | `index.html` |
| Statue of Liberty | `landmark-liberty.html` |
| Empire State Building | `landmark-empire.html` |
| Staten Island Ferry | `landmark-ferry.html` |
| Wonder Wheel | `landmark-wonder.html` |
| Yankee Stadium | `landmark-yankee.html` |
| Roosevelt Island Tramway | `landmark-tram.html` |

## Shared landmark-page structure

Each landmark page contains a breadcrumb, landmark name as the `h1`, short introduction, art-directed hero image with descriptive alt text and linked photo credit, an About section, a Directions section with Google Maps and Apple Maps links, official visitor information, and previous/next navigation.

## Navigation order

The primary navigation links to Home and all six landmark pages. Previous/Next links loop through the landmarks in this order:

Statue of Liberty → Empire State Building → Staten Island Ferry → Wonder Wheel → Yankee Stadium → Roosevelt Island Tramway → Statue of Liberty

## Responsive behavior

The site uses flexible images, a fluid CSS Grid card layout, Flexbox navigation, and breakpoints at 900px and 600px. Hero images use the square versions at 600px and below and the original landscape versions above 600px.
