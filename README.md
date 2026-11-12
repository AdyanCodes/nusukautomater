# Nusuk code queue

A small web page that shows one Nusuk invite code at a time. Tap to copy it, open Nusuk, paste, tap Check the code, then mark the result here. It saves your place on your phone. Independent tool, not affiliated with Nusuk.

## Put it on GitHub (no coding needed)

1. Sign in at github.com and create a **New repository**. Name it e.g. `nusuk-queue`. Free accounts must make it **Public**.
2. Click **Add file > Upload files**, drag in everything from this folder (`index.html`, `codes.txt`, `manifest.webmanifest`, `sw.js`, both `icon` files), then **Commit changes**.
3. Go to **Settings > Pages**. Under Build and deployment choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. Wait a minute or two. Your page will be at `https://YOUR-USERNAME.github.io/nusuk-queue/`.

## Use it on your phone

1. Open that address in Chrome on your phone.
2. Chrome menu (three dots) > **Add to Home screen** or **Install app**. It then opens like an app and works offline.
3. Your progress is saved in that browser on that phone only. Clearing Chrome’s site data resets it.

## Adding or changing codes

- Easiest: use **Add your own codes** inside the page. Those stay on your phone only.
- To change the shared list: open `codes.txt` on GitHub, tap the pencil, add new codes at the **end**, commit. Don’t remove or reorder earlier lines, because your saved place counts lines from the top.
- After an update, reopen the page twice so the new file loads.

## Good to know

- A public repository means anyone can see `codes.txt`. The built-in codes came from public boards. If you add codes you want private, use the in-page box instead.
- The built-in codes were never verified and many are probably used already.
- Never share your Nusuk password or OTP with anyone.
