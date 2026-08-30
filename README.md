# Abdul Mohaimen Portfolio — Fixed v7

## What was fixed
- The fixed navigation no longer overlaps the hero image/content.
- The hero starts below the navigation using the same CSS variable as the header height.
- Mobile navigation uses the correct 70px header offset.
- Section navigation accounts for the fixed header and preserves the bottom-to-top curtain transition.
- Hero image is preloaded, uses WebP, `fetchpriority="high"`, async decoding, and GPU-friendly transforms.
- Project/secondary images use optimized WebP assets and lazy loading.
- Project thumbnails are preloaded so the orbit and handoff feel smoother.
- Local image references were checked and all referenced local images exist.
- JavaScript syntax was checked successfully.

## Email
The original project used `hello@example.com`, which is a placeholder and is not your real email. I did not invent a personal email address.

Before publishing, edit this one line near the bottom of `index.html`:

    email: 'YOUR_EMAIL_ADDRESS_HERE',

The site then automatically applies the address to the email/contact links and generates the project inquiry subject/body.

## Hero image
The optimized hero image is:

    images/ChatGPT Image Aug 25, 2026, 11_07_41 PM.webp

The original PNG is retained as a source asset, but the browser uses the optimized WebP for normal loading.

## Run
Open `index.html` directly in a browser, or serve the folder from any static web server.
