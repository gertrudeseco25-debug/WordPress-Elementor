# DESIGNR homepage — Elementor Pro

These templates recreate the supplied screenshot using native Flexbox Containers and Heading, Text Editor, Button, Image, Icon List, and Accordion widgets. No custom CSS, scripts, or extra plugins are required. The screenshot represents a Shopify services business; the implementation runs in WordPress/Elementor.

## Import

1. Back up the site and use a staging page. Activate Elementor and Elementor Pro with Containers available.
2. In **Templates → Saved Templates → Import Templates**, import `designr-homepage.json`. Create a page, choose **Elementor Full Width**, then insert **DESIGNR — Homepage** from the template library's **My Templates** tab. Hide the page title through page settings if your theme displays it.
3. Import `designr-header.json` and `designr-footer.json` as saved container templates. In **Templates → Theme Builder**, create a Header and Footer, respectively, and insert the corresponding saved template. Set their display conditions for the homepage (or the whole site, if desired). They are separate from the homepage JSON and do not set display conditions automatically.
4. Configure **Site Settings → Global Colors**: Primary `#DDB7F7` (lavender), Secondary `#F4F2EF` (off-white), Text `#B8B8B8` (muted gray), Accent `#39BB87` (green). Headings and body text reference the relevant native global color IDs. Dark backgrounds and button treatments have explicit local values. Changing site globals affects other pages, so review those changes first.
5. Configure **Global Fonts → Text** to Inter, 16px, line height 1.7em. Body widgets reference this global font. Headings use editable local Oswald bold typography with responsive sizes to preserve the hierarchy. Oswald/Inter approximate the screenshot; select the actual licensed Figma fonts when available. Font loading depends on your site's Elementor settings/network policy. Template files do not install fonts or modify your global kit.
6. Replace the hero collage, project thumbnails, and portrait using each Image widget's Media Library picker; add image alt text there. Image widgets use Elementor's default placeholder until an image is selected. Replace the two Sample Logo strips with your own logo widgets/images. The three empty dashed review containers intentionally match the screenshot's blank cards; add real reviews or media when supplied.
7. Replace the footer's contact placeholders, verify all text and pricing, and connect booking buttons. They currently link to the homepage's `#contact` callout, not a booking service. Header section links work on the homepage; use homepage-qualified URLs if publishing that header on other pages. Footer navigation is editable text awaiting final destinations.
8. Review Elementor's desktop, tablet, and mobile previews, then test the published staging page at approximately 1440px, 1024px, 768px, and 390px. Desktop/tablet retain columns; mobile stacks content and wraps the logo/header links. Device padding, font sizes, image heights, and review-card heights are included. Site breakpoint customizations determine which device settings apply.

## Fidelity and validation

The supplied reference is a raster screenshot, not an inspectable Figma file. The templates approximate its dark palette, centered 1140px content area, condensed headings, lavender highlights, generous vertical spacing, rounded dashed cards, and section order. Exact spacing, font metrics, imagery, small text, and interactions cannot be recovered reliably from this image. Some small copy is transcribed approximately; service descriptions are starter copy. No client testimonials or contact details have been invented.

The header uses native link buttons instead of a menu plugin and stacks on mobile. Services use Elementor's native Accordion rather than custom code. Its initial open state and appearance may vary by Elementor version. Content remains editable in the Navigator; no section is flattened into an image.

JSON metadata, tree structure, unique element IDs, native widget types, anchor targets, and responsive container settings were checked locally. A WordPress runtime is not present here, so actual Elementor import, rendering, font loading, accordion behavior, and visual fidelity still require staging-site validation. These files are templates, not a full-site kit; they do not overwrite site globals automatically.
