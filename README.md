# Prowl GitHub Pages site

Static landing page and release download for Prowl Forge 1.8.9. The site includes the v0.1.41 JAR in `public/downloads/` and deploys through GitHub Pages using `.github/workflows/pages.yml`.

## Publish with GitHub Pages

1. Create a **public** GitHub repository for the site and upload the contents of this folder to its `main` branch.
2. In the repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. Push to `main`, or run **Deploy Prowl site** from the **Actions** tab. The workflow publishes the site and reports its URL.

The download button points to the bundled JAR. When releasing a new version, replace the JAR in `public/downloads/` and update the version text and filename in `public/index.html`.

## Before sharing

- This site repository contains the release JAR, not the source project or any personal configuration files.
- Do not upload `prowl.properties`, stats caches, API keys, or other local configuration.
- Prowl currently has a Hypixel API-key field. Hypixel's published policy says API keys should not be entered into third-party mods; the site calls this out and links to the policy. Review the current policy before distributing or using API-backed features.
- The page and mod are independent projects and are not affiliated with Hypixel or Mojang.
