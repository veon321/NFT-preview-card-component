# Frontend Mentor - NFT preview card component solution

This is a clean, responsive, and modern solution to the NFT preview card component challenge on Frontend Mentor.

## The challenge

The challenge was to build an NFT preview card component and get it looking as close to the design as possible using HTML and CSS. The component needed to be fully responsive, handling both mobile and desktop layouts seamlessly while implementing professional active states (hover effects).

## Links

- Solution URL: [https://github.com/veon321/NFT-preview-card-component](https://github.com/veon321/NFT-preview-card-component)
- Live Site URL: [https://veon321.github.io/NFT-preview-card-component/](https://veon321.github.io/NFT-preview-card-component/)

## Built with

- Semantic HTML5 markup (utilizing `<main>`, `<article>`, and correct heading hierarchies)
- CSS Custom Properties (Variables)
- Flexbox layout (with smart `gap` properties for streamlined spacing)
- Modern CSS Math Functions (`clamp()` for fluid typography, dynamic paddings, and responsive container scaling)
- Fluid Overlay design pattern for advanced image hover interactions
- Completely Fluid Approach (transitioning seamlessly between screen sizes without rigid breakpoints)
- Google Fonts (Outfit)

## Features

- **No Media Queries (`@media`):** The entire responsiveness is handled dynamically. The component scales naturally using a fluid `width: clamp()` formula. It expands elegantly on desktop screens while gracefully shrinking to a safe minimum width on small mobile devices without any layout breakage.
- **Fluid Typography & Paddings:** Instead of rigid pixel steps, the card's font sizes, inner paddings, and structural margins scale smoothly and proportionally using `clamp()`. This guarantees perfect accessibility, adapting perfectly to different user browser zoom settings.
- **Advanced Interactive States:** - **Fluid Overlay Effect:** The main NFT image features a highly precise hover effect utilizing absolute positioning and opacity transitions. When hovered, a translucent cyan mask smoothly fades in, revealing the view icon (`icon-view.svg`) perfectly centered.
  - **Color-Shift Micro-interactions:** The title and creator's name dynamically transition to the primary cyan color upon hover, indicating clickability.
- **Flawless Asset Management:** Inline SVGs (`icon-ethereum.svg`, `icon-clock.svg`) are perfectly aligned with text elements using modern Flexbox properties, replacing old-fashioned, messy margin hacks.
