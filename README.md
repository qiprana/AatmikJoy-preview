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
