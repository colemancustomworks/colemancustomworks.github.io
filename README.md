# Coleman Customworks LLC website

Repair, renovation and custom builds in Twin City, Georgia. Owner, Quin Coleman.

Plain HTML site, ready for free hosting on GitHub Pages.

## Pages
- `index.html` - homepage
- `our-work.html` - photo gallery and video
- `join-the-team.html` - job application

## Before going live
1. Join the Team form: replace `FORM_ENDPOINT_HERE` in `join-the-team.html` with a free form service address (for example Formspree) that emails colemancustomst1@gmail.com.
2. GitHub Pages: repo Settings > Pages > Deploy from branch `main`, folder `/ (root)`.
3. Domain: once colemancustomworks.com moves off Squarespace, add a `CNAME` file containing `www.colemancustomworks.com` and point the domain's DNS at GitHub Pages.

## Adding work photos
Drop photos into `images/` and add a `<figure>` block in `our-work.html`.
