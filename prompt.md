Build a standalone HTML + CSS + JS prototype for a homepage redesign of "Hollywood Aura Photography." 
The prototype will later be embedded into a WordPress site, so use CDN links for all libraries. 

Design goals:
- A modern, vibrant, and spiritual aesthetic inspired by rainbow aura themes.
- Hero Section:
  - Full-width hero with a subtle interactive rainbow particle or gradient background that reacts to cursor movement (use particles.js or tsparticles via CDN).
  - Overlay headline text: "Experience Your Aura Like Never Before" with two buttons: 
    1. "Book an Appointment" 
    2. "Learn More".
- Typography:
  - Use Google Fonts (Poppins or Montserrat for headings, Inter for body text).
- Styling:
  - Rounded, card-based sections with soft shadows and gradient borders.
  - Rainbow gradients applied subtly (e.g., as button backgrounds, section dividers).
- Sections to include:
  1. Hero Section (interactive rainbow background, headline, CTA buttons).
  2. Services Grid (3–4 cards: Aura Photography, Chakra Readings, Aura Booth for Events, Gift Cards).
  3. About Section (two-column layout with text on one side and an image on the other).
  4. Testimonials Section (stacked cards or simple slider using Swiper.js via CDN).
  5. Call-to-action footer (gradient background with "Book Now" button).

Technical:
- Use Tailwind via CDN for styling.
- Use `particles.js` or `tsparticles` via CDN for the hero animation background.
- Use `framer-motion` alternative (AOS.js via CDN) for scroll animations since this must run inside WordPress without a build process.
- Ensure fully responsive design (mobile, tablet, desktop).
- Deliver clean, modular HTML so WordPress content editors can copy-paste into Custom HTML blocks.
