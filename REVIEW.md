# Website review

Reviewed 28 October 2026.

## Fixes made

- Restored the intro paragraph break on phones. The old mobile rule hid the breaks and joined two sentences together.
- Resized the narrow-screen heading and improved mobile paragraph readability.
- Replaced clipped mobile map overlays with a full island and a two-column set of destination buttons.
- Enlarged mobile map controls and header/close targets.
- Allowed navigation to wrap on narrow case-study pages.
- Kept the profile photo above the biography on phones to prevent cramped text.
- Corrected borders in the two-column destination grid.
- Improved dialog naming, viewport height handling and background scroll locking.
- Allowed long contact details and buttons to wrap.
- Stacked case-study action links and the process steps where necessary.
- Matched the browser theme colour to the purple design.

## Checks completed

- Homepage checked at frame widths of 320, 375, 390, 430, 768, 1024 and 1280 CSS pixels in Chromium. Traditional frame scrollbars reduce the content area by 15px.
- No page-level horizontal overflow found at those widths.
- All six dialogs opened and closed at 320px and 390px frame widths, with no internal horizontal overflow.
- Quick view toggled on and back to the island.
- Photo viewer opened, moved forward and backward, and closed with Escape while leaving the gallery open.
- All six case-study pages loaded at 320px frame width without horizontal overflow.
- The GHL screenshot loaded when scrolled into view. The return link reopened the workshop.
- Desktop hero checked visually after the responsive changes.
- All 46 static HTML local asset/link references resolve.
- All included JPEG files validate, and the CV PDF is present.
- JavaScript syntax check passed.
- No preview-origin JavaScript errors were reported by the browser log check.

## Limits and final deployment check

Phone-sized browser frames were used, not physical iOS or Android devices. Safari and Firefox were not tested. Native mobile keyboard, browser chrome, touch gestures and device performance may differ.

External sites and Google Drive sharing permissions were not exhaustively tested. Test the PDF links in an incognito window before sharing the final URL.

The package has not been deployed to your Vercel account. After deployment, open the final URL on your phone, check the CV and a case-study link, and confirm the site is accessible to visitors without signing in.
