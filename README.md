<div align="center">

# The Cold War: A Contest of Ideologies

An interactive, data-rich educational website about the history and global impact of the Cold War, 1947–1991.

[View the live site](https://coldwarweb.netlify.app) · [Report an issue](https://github.com/YanYihann/Cold-War-Web/issues)

[![HTML](https://img.shields.io/badge/HTML5-single--page-E34F26?logo=html5&logoColor=white)](index.html)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

</div>

## About

This responsive single-page experience combines narrative storytelling, a historical timeline, a global story map, and animated data visualizations. It is designed as an approachable educational presentation rather than a comprehensive historical archive.

## Highlights

- Scrollable chronology of major Cold War events
- Knight Lab TimelineJS and StoryMapJS integrations
- Chart.js visualizations for economic, military, and nuclear data
- Responsive layout built with Tailwind CSS via CDN
- Curated links to declassified documents, speeches, photographs, and videos

## Run locally

No build step is required.

```bash
git clone https://github.com/YanYihann/Cold-War-Web.git
cd Cold-War-Web
python -m http.server 8000
```

Open `http://localhost:8000`.

## Project structure

```text
.
├── index.html   # Markup, styling, content, and interactions
├── LICENSE      # MIT License
└── README.md
```

## External services and sources

The page loads Tailwind CSS, Font Awesome, Google Fonts, Chart.js, and Knight Lab embeds from public CDNs, so an internet connection is required for the complete experience.

Historical reference links include the CIA Reading Room, the National Security Archive, and C-SPAN. These third-party sources retain their own terms and copyright.

## Limitations

- The site is educational and should not be treated as a peer-reviewed historical reference.
- Data points and narrative claims should be checked against the linked primary sources before academic citation.
- CDN-hosted dependencies are not pinned locally.

## License

Project code is available under the [MIT License](LICENSE). Third-party content and embedded media are not covered by that license.


