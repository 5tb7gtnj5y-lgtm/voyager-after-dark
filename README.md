# Voyager After Dark

An offline-first nautical pub-crawl mission for the bars and clubs aboard Marella Voyager.

## GitHub upload

1. Create a new GitHub repository called `voyager-after-dark`.
2. In the empty repository, choose **Add file → Upload files**.
3. Upload `README.md` and the complete `dist` folder from this package.
4. Commit the files to the `main` branch.

## Cloudflare Pages settings

Connect the GitHub repository from **Workers & Pages → Create → Pages → Connect to Git**.

Use these settings:

- Framework preset: **None**
- Production branch: `main`
- Build command: `exit 0`
- Build output directory: `dist`
- Root directory: leave blank

After deployment, Cloudflare supplies a `pages.dev` address. Every later commit to `main` will publish automatically.

## Offline use

Open the deployed address once while online. On iPhone, use **Safari → Share → Add to Home Screen**. The service worker stores the game and artwork for offline play.

