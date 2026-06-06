# BAGIDOR Design System

This file is the visual source of truth for the BAGIDOR website.

## Brand Aesthetic

BAGIDOR should feel premium, masculine, refined, understated, traditional but modern, and easy to trust. The site should read as a premium cigar lifestyle product page, not a generic ecommerce page.

The overall tone is matte black, minimal, calm, and spacious. Use high contrast, warm metallic accents, and restrained typography. Avoid anything gimmicky, loud, smoky, cluttered, or overly decorative.

## Color Palette

| Color Name | Hex | Role |
| --- | --- | --- |
| Warm Black | `#161614` | Primary page background |
| Smoky Taupe | `#2D2925` | Secondary panels, section bands, cards |
| Champagne Gold | `#D8C9A3` | Eyebrows, highlights, premium accent |
| Burnished Copper | `#B68852` | Primary buttons, hover states, accent rules |
| Bone White | `#F6F2EA` | Primary text |
| Tobacco Brown | `#684833` | Subtle border warmth and secondary detail |

## Typography

- Headings should feel confident, spacious, and premium.
- Current heading stack: Georgia / Times-style serif for a refined traditional feel.
- Current body stack: Inter / system sans-serif for modern readability.
- Use uppercase section labels sparingly.
- Keep body copy readable and concise.
- Do not use overly decorative fonts.
- Do not scale font size directly with viewport width except via restrained `clamp()` ranges.
- Letter spacing should be 0 for normal body text and modestly positive for small uppercase labels.

## Layout

- Single-page scrolling static site.
- Black background throughout.
- Center content in max-width containers.
- Use generous section padding and clear vertical rhythm.
- Favor two-column layouts on desktop when pairing copy and media.
- Stack sections cleanly on mobile.
- Avoid nested cards.
- Cards should be reserved for repeated use cases, FAQs, social links, or framed tools.
- Keep border radius at `8px` or less.
- Use subtle dividers instead of heavy containers.

## Spacing

- Desktop sections should feel open and premium.
- Mobile sections should remain spacious without creating excessive scrolling.
- Use consistent gaps between repeated cards and controls.
- Avoid crowding CTAs, forms, or navigation links.

## Buttons

- Primary buttons use Burnished Copper with dark text.
- Hover/focus may shift to Champagne Gold.
- Secondary buttons are transparent with subtle Champagne Gold borders.
- Buttons use uppercase text, strong weight, and compact luxury styling.
- Tap targets must be at least 44px high.

## Images

- Use actual BAGIDOR assets, not generic stock imagery.
- Treat images as premium product/lifestyle visuals.
- Frame images with subtle borders and restrained shadows.
- Avoid smoke graphics, cliché cigar imagery, and decorative visual gimmicks.
- Use descriptive alt text for meaningful images.

## Navigation

- Navigation should be sticky, simple, light, and not visually heavy.
- Desktop navigation uses small uppercase links.
- Mobile navigation uses a compact menu button and full-width overlay list.
- Keep the brand wordmark visible.

## FAQ

- Use a simple accordion.
- Keep borders subtle.
- Use readable summaries and generous touch targets.
- Avoid heavy animation.

## Footer

- Minimal black footer.
- Small text.
- Subtle divider line above footer.
- Include copyright, website, email, and Privacy Policy placeholder.

## Accessibility

- Maintain strong contrast between text and background.
- Provide visible focus states through color/border changes.
- Include a skip link.
- Use semantic headings and landmarks.
- Use descriptive alt text for content images.
- Social icons can use empty alt text when adjacent visible text names the link.
- Respect reduced-motion preferences.

## Mobile Responsiveness

- Stack all major grids on small screens.
- Keep tap targets large.
- Ensure buttons and form fields span cleanly without text overflow.
- Do not allow navigation or cards to create horizontal scrolling.
- Use stable image aspect ratios to prevent layout shifts.

## Things to Avoid

- Cheesy smoke graphics
- Loud colors
- Flashy animations
- Cluttered layouts
- Cartoonish cigar icons
- Overly decorative fonts
- Heavy ecommerce styling
- Generic stock visuals
- Excessive gradients or visual effects
- Oversized UI text inside compact panels
