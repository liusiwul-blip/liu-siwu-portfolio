# Liu Siwu (Mc) — Interior Design Portfolio

This repository hosts the static portfolio website for GitHub Pages.

## Publish the current portfolio archive

1. Download `Liu_Siwu_Portfolio_Site_v1.zip` from the ChatGPT conversation.
2. In this repository, choose **Add file → Upload files** and upload the ZIP to the repository root. Keep the filename `Liu_Siwu_Portfolio_Site_v1.zip` (or use `portfolio-site.zip`). Commit the upload to `main`.
3. Before the first deployment, open **Settings → Pages → Build and deployment → Source**, and select **GitHub Actions**.
4. The workflow at `.github/workflows/deploy.yml` will unpack the site and publish it. Open **Actions** and wait for **Deploy portfolio to GitHub Pages** to finish successfully.
5. The public site will use `https://liusiwul-blip.github.io/liu-siwu-portfolio/` once the first deployment succeeds.

The ZIP contains the site files and local image assets. Do not upload only the ZIP and expect GitHub Pages to show it directly; the included workflow unpacks it during deployment.
