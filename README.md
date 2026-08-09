# Freemaged

Freemaged is a free, lightweight, and privacy-focused image editor that runs directly in your browser. All processing happens on your device, which means your images are never uploaded to a server. It's fast, secure, and ready when you are.

## Development

The project uses hand-written CSS and vanilla JavaScript with zero dependencies — no build step, no frameworks, no CDNs. Styles, inline SVG icons and scripts all live inside the `index.html` and `about/index.html` files, so both pages work fully offline.

- `index.html` – The main image editor application.
- `about/index.html` – The separate "About" page, which is also self-contained.

## Running

### Online (Recommended)

The easiest way to use Freemaged is to visit the official website:
https://freemaged.com

### Locally

If you prefer to run the editor offline, you can download the project and open index.html directly in any modern web browser. No build step or server is required.


## Version History

- **v1.1** – Improved SEO with additional meta tags and sitemap support.
- **v1.2** – Enhanced mobile experience by allowing the tool panel to be hidden on small screens.
- **v1.2.1** – Fixed mobile toggle reliability on touch devices.
- **v1.3** – Added a new mobile slider menu, version number visible next to the title, instant start for cropping and drawing, allows for multiple drawings, added quick optimization for mobile, reordered footer links.
- **v1.3.1** – Enhanced performance with optimized resource loading and improved accessibility for screen readers and navigation.
- **v2.0** – Full UI redesign ("refined dark studio") with a dark/light theme toggle that remembers your choice, drag-and-drop uploads, a thumbnail strip with per-image remove, additive uploads that add to the current session instead of replacing it, `Cmd/Ctrl+Shift+Z` for redo, a fix for pasting text into the file name and target-size fields, and dropped CDN dependencies (Tailwind and Font Awesome replaced by hand-written CSS and inline SVG icons) so the editor runs completely offline. Drawing gained new shape tools — line, rectangle, and ellipse alongside pen and a redrawn, much crisper arrow — with Shift to constrain (45° angles, squares, circles), plus working touch drawing on mobile. The optimization presets were rebuilt around a desktop/mobile pair for responsive website sections — export either size or both at once — plus platform presets for Shopify product images and Firebase/CMS uploads.
- **v2.1:** Added percentage batch resizing, batch transforms and adjustments, batch preset exports, locally saved custom optimization presets, a text and watermark tool, live straighten and custom rotation, hold-to-compare, copy and native share actions, and proper wheel, pan, pinch, fit, and 1:1 zoom controls. Crop selections now keep their chosen aspect ratio even when a handle is dragged beyond the image boundary, and crop and drawing coordinates remain correct while zoomed. Preset cards now use a full-height labeled Download action, and animated GIF imports clearly report that they are flattened to a still frame.
- **v2.1.1:** Tightened the editor hierarchy with a full-width primary Choose Files action, a compact split footer, and a consistently sized 1:1 canvas control. The former refresh action is now an explicit Clear Session button with a confirmation dialog that explains exactly what will be removed.
- **v2.1.2:** Matched the vertical padding and height of the primary Choose Files and Reset Active Image actions for a more consistent control rhythm.


## Made by

This app was made by Francisco Fernandez with the help of AI.\
[fran.md](https://fran.md)
