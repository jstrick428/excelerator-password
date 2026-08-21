# Excelerator Password App Store Web Pages

This folder contains the small static website intended to provide public App Store Privacy Policy and Support pages for Excelerator Password.

## Purpose

The site contains:

- A simple landing page.
- A Privacy Policy page.
- A Support page.

These files are independent from the macOS application bundle. No application source code should be published from this folder.

## Local Preview

From this folder, run:

```sh
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## GitHub Pages Structure

The site is designed to work as a project GitHub Pages site, such as:

```text
https://USERNAME.github.io/excelerator-password/
```

No final GitHub username or public URL is hardcoded. Links are relative so the pages can be served from a project subpath.

## Final URLs Still Needed

Before App Store submission, create final public URLs for:

- Privacy Policy.
- Support.

Those URLs can then be added to the appropriate App Store metadata and, after approval, to the app's Help menu configuration if desired.

## Identity

Product: Excelerator Password

Owner / copyright holder: Justin Matthew Strickler

Support contact: jmsdesignnyc@gmail.com

Do not associate this website with unrelated branding, ownership, publisher, privacy, or support identities.

Existing application bundle identifiers are technical identifiers only and are not product ownership statements.

## Privacy

The static pages do not include analytics, cookies, tracking scripts, third-party fonts, third-party scripts, or a backend.
