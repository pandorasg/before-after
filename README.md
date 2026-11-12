# Before/after slider

- **index.html** is the slider itself. It reads its two images from the address.
- **make.html** is a helper page. Paste two image links into it and it gives you the code for Carbonmade.

## One-time setup (GitHub Pages)
1. Go to github.com and click **New repository**.
2. Name it **before-after**, set it to **Public**, and click **Create repository**.
3. On the next page, click **uploading an existing file**. Drag in `index.html` and `make.html`, then click **Commit changes**.
4. Open **Settings → Pages**. Under **Branch**, choose **main** and **/ (root)**, then click **Save**.
5. Wait about a minute. Your pages will be at:
   - https://pandorasg.github.io/before-after/make.html (the helper)
   - https://pandorasg.github.io/before-after/index.html (the slider)

## Each new slider
1. Get a link for each image. Either upload them to the same repository (**Add file → Upload files**), or right-click an image already on your site and choose **Copy image address**.
2. Open **make.html**, paste the two links, add a short description of each image, and click **Copy code**.
3. On Carbonmade, drag a **Title** block where you want the slider. Delete its text, then paste the code.
4. Publish.

## Options in the address
| Option | What it does |
|---|---|
| `before`, `after` | Image links |
| `balt`, `aalt` | What screen readers say about each image |
| `bl`, `al` | The two labels (default Before / After) |
| `start` | Where the divider starts, 0 to 100 (default 50) |
| `anim=1` | Sweeps once when the slider scrolls into view. Skipped for people who turn on Reduce Motion. |

## Accessibility
- The divider moves with the arrow keys and announces its position.
- The handle is 44 pt.
- Labels pass AAA contrast on the grey frame.
