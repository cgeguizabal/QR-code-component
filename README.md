# QR Code Component

This is a clean and modern QR code card component designed to showcase a QR code with a short promotional message. It uses CSS Grid and Flexbox for layout, a soft color palette, and responsive typography with the "Outfit" font.

---

## Features

- **Full viewport centering:** The component is perfectly centered vertically and horizontally using Flexbox.
- **Card layout:** Uses CSS Grid to layout the QR code image and accompanying text side by side on larger screens.
- **Rounded corners:** Both the card container and the QR image have smooth rounded corners.
- **Custom color palette:** Uses CSS variables for consistent theme colors (white, light gray, gray, dark blue).
- **Responsive typography:** Clear headings and paragraph text with appropriate spacing and line height.
- **Attribution section:** Small footer with challenge and author credits styled separately.

---

## Usage

1. Include the "Outfit" font from Google Fonts.
2. Use the provided CSS variables for easy theme adjustments.
3. Wrap your QR code image and text content inside `.container` within `.wrapper`.
4. Add attribution below the card if desired.
5. Make sure to replace the QR image path with your own QR code image.

---

## Technologies

- HTML5 semantic tags (`<main>`, `<header>`, `<article>`)
- CSS3 Grid and Flexbox
- CSS Variables for colors and spacing
- Google Fonts

---

## Code Structure

- Global reset and box-sizing applied to all elements.
- Root-level CSS variables for colors.
- `.wrapper` uses Flexbox for centering the card.
- `.container` is a grid container for QR and text.
- `.qr img` styled with border radius and full size.
- `.container2` holds text content with grid and padding.
- `.title` and `.text` style headings and paragraphs with color and spacing.
- `.attribution` uses Flexbox and small text styling.

---

## Example

```html
<div class="wrapper">
  <main class="container">
    <div class="qr">
      <img src="assets/img/image-qr-code.png" alt="QR" />
    </div>
    <div class="container2">
      <header class="title">
        <h3>Improve your front-end skills by building projects</h3>
      </header>
      <article class="text">
        <p>
          Scan the QR code to visit Frontend Mentor and take your coding skills
          to the next level
        </p>
      </article>
    </div>
  </main>
</div>
<div class="attribution">
  Challenge by
  <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
  Coded by <a href="#">Guillermo Eguizabal</a>.
</div>
