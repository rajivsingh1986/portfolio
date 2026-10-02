# Publishing This Site on WordPress.com (Free Plan)

This folder now also includes `wordpress-export.html` — the same portfolio
content formatted for a WordPress **Custom HTML block**, since WordPress.com's
free plan can't host raw `.html`/`.css` files directly the way Vercel does.

## Steps

1. Log in to your existing WordPress.com account.
2. From your site dashboard: **Pages → Add New Page**. Give it a title (e.g. "Home") — don't worry about the title showing publicly, you can hide it in the page settings later if you want.
3. In the block editor, add a **Custom HTML** block (type `/html` and select it, or use the `+` block inserter and search "Custom HTML").
4. Open `wordpress-export.html` in VS Code, select all, copy, and paste the entire contents into that one block.
5. Click **Preview** before publishing to check it rendered correctly.
6. If it looks right: **Publish**. Then, in **Settings → General**, you can set this new page as your site's homepage (**Settings → Reading → "A static page"**).

## If the styling looks broken or stripped out

WordPress.com applies a content filter (KSES) to free-tier sites that can strip
`<style>` blocks for non-admin content in some configurations. If Preview shows
unstyled plain text/black-and-white content instead of the dark themed design:

- Try adding the CSS via **Appearance → Customize → Additional CSS** instead
  (copy just the code between `<style>` and `</style>` from `wordpress-export.html`
  into that box) — this panel is available on most WordPress.com plans and is
  not subject to the same per-block content filtering.
- If `Additional CSS` isn't available on your plan, the remaining reliable
  options are: upgrade to a plan with custom CSS/plugin support, or keep using
  the already-live Vercel deployment (https://portfolio-mauve-psi-86.vercel.app)
  as your primary link, since it has zero such restrictions.

## Why not fully automate this step

Creating/configuring your WordPress.com site needs your own logged-in session
and account-specific choices (theme, domain, page structure), so this is
intentionally left as a short manual step rather than something done on your
behalf.
