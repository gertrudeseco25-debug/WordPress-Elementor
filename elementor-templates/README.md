# Import the responsive hero

1. On your WordPress site, activate Elementor and Elementor Pro. Use a current version with Containers enabled (older versions may call this Flexbox Container).
2. Open **Templates → Saved Templates → Import Templates**, choose `responsive-hero.json`, and import it.
3. Edit a page with Elementor, click the template library folder icon, open **My Templates**, and insert **Responsive Hero Starter**. You can also import the JSON using the library's upload icon.
4. Select the Image widget and choose an image from your Media Library. It uses Elementor's built-in placeholder by default; no image file or external image service is included. Set descriptive alt text in the Media Library.
5. Edit the heading, paragraph, button label, and button link. The starter link is `#contact`; change it to your destination or add a matching target.

The single hero uses native containers, Heading, Text Editor, Button, and Image widgets. Desktop and tablet use two columns; mobile stacks the text above the image. Padding and heading/body font sizes have explicit desktop, tablet, and mobile values. Use Elementor's responsive preview to review each device; your site's breakpoint settings determine when each layout applies.

For Figma handoff, replace the example copy and image, then adjust spacing, colors, and typography in Elementor. All content and styling remain editable; no custom HTML, CSS, JavaScript, or extra plugins are required. Site theme and global styles can affect the final appearance.

This is a small starter template, not a full page or site. Import and visual rendering must be checked on your WordPress installation.

## Screenshot-based homepage

Use [designr-homepage.json](designr-homepage.json) for the homepage content. Header and footer are separate in [designr-header.json](designr-header.json) and [designr-footer.json](designr-footer.json). Follow the [homepage import and customization guide](designr-import-guide.md) for global styles, placeholders, Theme Builder setup, and validation limits.
