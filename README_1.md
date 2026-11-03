# Pixel Stamp Maker

A browser-based stamp designer. Build round, oval, rectangular, square and octagonal stamps with curved text, icons and your own images, then download the finished design.

<!-- Replace with a real screenshot of the editor: docs/screenshot-editor.png -->
<!-- ![Pixel Stamp Maker editor](docs/screenshot-editor.png) -->

**Live demo:** _coming soon_ <!-- add GitHub Pages or hosted URL once verified -->

## Features

- **Stamp shapes** — round, oval, rectangle, square and octagon
- **Type on a path** — curved text that follows the stamp ring, plus straight text lines with bold/italic and font choices
- **Templates & icons** — start from a template or add icons from a categorised picker (Remix Icon)
- **Image upload** — place your own logo or artwork
- **Real-world sizing** — dimensions in centimetres and millimetres
- **Editing tools** — layers panel, alignment grid, undo and redo
- **Export & checkout flow** — download flow with PDF generation (jsPDF) and email confirmation (EmailJS); payment step is simulated
- **WordPress-ready** — packaged as a custom WordPress page template

## Built with

HTML5 · CSS3 · Vanilla JavaScript (SVG) · [jsPDF](https://github.com/parallax/jsPDF) · [EmailJS](https://www.emailjs.com/) · [Remix Icon](https://remixicon.com/) · WordPress (PHP page template)

## Project structure

| File | Purpose |
| --- | --- |
| `Index.html` | Standalone editor page, including PDF document upload |
| `Stamp-index.html` | Advanced editor variant with inline scripts |
| `Script.js` | Editor logic — shapes, text paths, layers, units, undo/redo |
| `Styles.css` | Editor styles |
| `Stamp-design.php` | WordPress page template version of the editor |

## Run locally

No build step is needed.

```bash
git clone https://github.com/Thamizhenthi-Vekatesan/Pixel-Stamp.git
cd Pixel-Stamp
# open Index.html in your browser, or serve the folder:
npx serve .
```

### Use in WordPress

1. Copy `Stamp-design.php` into your active theme folder.
2. In WordPress, create a page and choose **Pixel Stamp Maker** as the page template.
3. Replace the EmailJS service, template and public key with your own values, and restrict the key to your domain in the EmailJS dashboard.

## My role

UI/UX design and frontend development — interface design, SVG editor logic and WordPress integration. <!-- confirm before publishing -->

## License

<!-- Choose a license after confirming you own the rights to this code (see notes). -->
_License to be added._
