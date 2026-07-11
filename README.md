# 97 112 99

The product consultancy of Andrew Cunningham.

## Files

- `index.html` — main site
- `404.html` — custom 404 page
- `favicon.svg` — browser tab icon (green up-right arrow)
- `linkedin-profile.svg` / `linkedin-profile.png` — LinkedIn profile picture (green arrow, 1000×1000)
- `linkedin-banner.png` — LinkedIn cover banner (red→green divider squares, 1584×396)

## Deployment

1. Push these files to the `main` branch of your GitHub repo (root level)
2. Go to **Settings → Pages**
3. Set **Source** to `Deploy from a branch`
4. Select `main` branch, `/` (root) folder
5. Save

Site will be live at `https://<username>.github.io/<repo>/` in about a minute.

## Custom domain (9711299.com)

1. In **Settings → Pages → Custom domain**, enter `9711299.com`
2. At your DNS registrar, add these A records for the apex:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. Add a CNAME record for `www` → `<username>.github.io`
4. Wait for DNS propagation (10 min–few hours)
5. Enable **Enforce HTTPS** in Pages settings

## Contact form

The form is powered by [Web3Forms](https://web3forms.com) and submissions go to andcunning@gmail.com. Access key is public and safe to include in client-side code.

## LinkedIn profile picture

`linkedin-profile.png` is a 1000×1000 green up-right arrow on white — matches the site favicon. Upload it as your profile photo. (`linkedin-profile.svg` is the vector source.)

## LinkedIn banner

`linkedin-banner.png` is a 1584×396 cover image: five squares sweeping red→green (the site's footer-divider motif). Upload it as your LinkedIn cover photo. Content sits in the right two-thirds so your profile photo doesn't overlap it.
