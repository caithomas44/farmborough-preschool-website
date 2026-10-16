# Farmborough Preschool website

The website for Farmborough Preschool, https://www.farmboroughpreschool.com/. A single static page
(`index.html`, `style.css`, `images/`), built on claude.ai and hosted on GitHub Pages from the
`main` branch of this repo. It replaced the old Wix site in October 2026.

## Changing the site

Edit the files and push to `main`. GitHub Pages republishes within a minute or two.

## Hosting and DNS

- GitHub Pages, custom domain `www.farmboroughpreschool.com` (the `CNAME` file), HTTPS enforced.
  `farmboroughpreschool.com` redirects to `www`.
- The domain is registered through Wix, and its DNS is edited in the Wix dashboard (Domains →
  farmboroughpreschool.com → ⋯ → Manage DNS records).

| Host | Type  | Value |
|------|-------|-------|
| @    | A     | 185.199.108.153 |
| @    | A     | 185.199.109.153 |
| @    | A     | 185.199.110.153 |
| @    | A     | 185.199.111.153 |
| www  | CNAME | caithomas44.github.io |

## Old Wix addresses

The Wix site had a page per section. Each old address (`/about`, `/information-for-parents`,
`/admission-information`, `/meet-our-staff`, `/fundraising`, `/our-committee`, `/testimonials`,
`/location`, `/daily-routine`) has a small page in its own folder that forwards to the matching
section of the new page. Anything else shows `404.html`.
