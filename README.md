# Aatmik Joy — Preview

This repository hosts the **review-only** version of [Aatmik Joy](https://aatmikjoy.me/).

The website source is maintained in [qiprana/AatmikJoy](https://github.com/qiprana/AatmikJoy), currently on branch `feature/today-self-care-planner`.

A GitHub Actions workflow in this repository publishes that branch to GitHub Pages. This repository does **not** publish the production `main` branch or modify the live website.

## Preview update

The homepage visual refresh is available on the source feature branch. Preview branch includes approved bright header logo and separate symbol asset.

## Enable the preview

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. Open **Actions → Deploy Aatmik Joy preview → Run workflow** if it hasn't run automatically.
4. Visit the deployment URL from the workflow or Settings → Pages.
5. To use `preview.aatmikjoy.me`, configure it as the Pages custom domain and create the DNS CNAME record `preview → qiprana.github.io` with your DNS provider.

The deployment workflow strips the production `CNAME` file and writes one for `preview.aatmikjoy.me`. It also adds `robots.txt` asking search engines not to index the preview.

**Warning:** This is a public preview site. It is not password protected. Avoid entering sensitive private information while testing. The self-care planner saves data in your browser.

Preview refresh: approved bright AatmikJoy branding assets integrated into feature branch.

Preview refresh: home copy refined to preserve 'space' only for the purpose statement.

Preview refresh: approved alternating sage (#E2ECDD) and warm ivory (#FFFCF6) homepage design; purpose and hero copy revised.

Preview refresh: reduced header branding scale and softened hero and sage/ivory transitions for visual review.

Preview refresh: original lightweight AatmikJoy text wordmark, no tagline or boxed artwork in the header.

Preview refresh: reverted text-only header experiment to previous image logo.

Preview refresh: wordmark with waves, smaller hero title, removed homepage 'Take a moment for yourself' button.

Preview refresh: reduced header wave mark and hero headline sizing across desktop, tablet and mobile.

Preview refresh: centered logo/waves with stacked, significantly smaller hero headline and tagline.

Preview refresh: refined tapered two-wave logo detail to match the supplied screenshot.

Preview Today page refined: suggested care and nature rhythms can be added to a personal plan; custom practices and self-reflection remain available.

Preview Today layout: compact inspiration, expandable example picker, custom self-care plan, single centering invitation, and private journal.

Today education preview: rotating Ayurvedic/Yogic daily insights and optional three-week pattern reflection, without changing the live site.

Today preview education: explain gradual adjustment, why abrupt change can be hard to sustain, and caution about medically risky withdrawal.

Preview layout repair: versioned Today CSS/JS URLs and a fallback for heading/cards to prevent stale unstyled page rendering.

Today preview studio (2026-11-11): private emotion flush, meditation/eye-rest/alternate-nostril practice timers with halfway nudges and end chime, opt-in emotional prompts, daily thought and saved journal.

Preview refresh (2026-11-18): merged approved editorial v7 experience from feature/today-self-care-planner. Homepage, Explore, voice/story content, transitions and navigation; retained Today and Reflections implementations.

Preview refresh (2026-11-18): Reflections and Products now share the full-width sage-and-ivory background transitions used by Home and Explore; card and search surfaces aligned.

Preview refresh (2026-11-18): original Grandmom wording restored verbatim, Reflections heading simplified, Products project count removed, and page-header ornaments switched to the approved AatmikJoy waves.

Preview refresh (2026-11-18): What is AatmikJoy is now a regular reflection article rather than a separate page; both article templates share the sage-and-ivory visual identity and updated navigation. Homepage wisdom and closing invitation copy refined.

Preview refresh (2026-11-18): centered Reflections page title, original AatmikJoy wave mark and introductory copy; unified Reflections and Connect hero spacing/typography with Explore.

Preview refresh (2026-11-18): softened the dark-green purpose section, unified AatmikJoy wave marks and editorial headings on Explore, Reflections, Connect and Products, and blended Reflections into the sage-and-ivory library background. Production unchanged.

Preview refresh (2026-11-18): Home watercolor-to-purpose transition now uses pale sage matching the rest of the site, with readable deep-green headings instead of a dark olive overlay.

Preview refinement (2026-11-18): Reflections topic filters moved beneath the centered introduction, enlarged for clearer navigation; search, presentation controls, card spacing and typography refined in the existing AatmikJoy palette, with original article links and JS behavior preserved.

Preview refinement (2026-11-18): simplified Reflections cards to one accessible full-card link, removed repetitive read/source labels and arrows, and added an expandable Show more control (8 at a time) while preserving topic filters and search.

Preview refinement (2026-11-18): reduced Reflections topic filter dimensions, font sizes, spacing and shadows to suit the understated editorial layout; functionality unchanged.

Preview refinement (2026-11-18): reduced excessive vertical space after reflection article introductions and tightened opening-to-content spacing consistently on Explore, Connect, Reflections, and Products, preserving visual gradients and copy.

Emergency preview fix (2026-11-18): resolved JavaScript startup crash in Reflections filter listeners by using the multi-element selector, restoring all site navigation and reflection filters.

Preview refresh (2026-11-18): versioned fixed app.js to force cache refresh after navigation hotfix; startup selector typo corrected.

Preview refinement (2026-11-18): restore home hero watercolor to unfiltered original color and brightness; preserve a narrow pale-sage gradient only at the bottom edge rather than washing over the full image.

Preview styling (2026-11-19): balanced homepage watercolor brightness to a gentle middle exposure and alternated white/pale-sage wellbeing cards while preserving the established soft chapter transitions.

Preview visual adjustment (2026-11-19): gently lightened the original watercolor hero, cropped the chalky left edge, preserved the AatmikJoy logo, and kept only a small pale-sage fade along the bottom.

Preview visual update (2026-11-19): raised the homepage watercolor brightness to 1.13 and softened contrast to 0.96 while retaining the established crop, text and short bottom blend.

Preview hero review (2026-11-19): settled watercolor between washed-out and overbright states with brightness 1.05, saturation .99, contrast 1.02, a modest crop, and a late soft bottom fade. Other page content unchanged.

Preview visual review (2026-11-19): softer AatmikJoy watercolor hero with restrained saturation and contrast, slight warm translucent veil and bottom-only fade. The existing hero art and other pages are unchanged.

Preview hero restore (2026-11-19): restored only the original homepage hero-image styling from the user-provided AatmikJoy_seamless_transitions_all_pages_v7.html. Other layout, text, logo, and page sections are unchanged.

Preview seam fix (2026-11-19): preserve uploaded-v7 homepage hero artwork and tone; extend only its lower transition so dark-green image tint blends smoothly into the following pale sage (#DEEADC) without a horizontal edge.
