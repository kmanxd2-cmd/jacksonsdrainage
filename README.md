# Jacksons Drainage Northwest website

A lightweight static website. It needs no build command or package installation.

## Run locally

Open `index.html` in a browser. Select Widnes, Runcorn or Warrington from the Service Areas menu to show that area's detail section in the same page.

## Files

- `index.html` contains the home page and the reusable area detail section. The selected area is read from the URL query, for example `index.html?area=Widnes#area-details`.
- `styles.css` contains the styling and responsive layout.
- `_headers` configures basic security headers for Netlify.
- `assets/` contains the images you supplied and six service illustrations cropped directly from the reference image you supplied in `assets/icons/`; the service cards use these supplied images.

Update the phone number in `index.html` if it changes. The supported area list is in the `serviceAreas` array in the page script and should match the navigation links. The Customer Reviews area links to Instagram while genuine customer reviews are not yet supplied. Add only reviews approved by the customers who wrote them. Instagram contact links to `https://www.instagram.com/jacksonsdrainagenorthwest`.

## Publish to Netlify

Drag this folder to Netlify Drop with `index.html`, `styles.css` and `assets/` together at the root. Preserve the folder structure because the page uses relative asset paths. Netlify reads `_headers` from the published folder root. The headers omit `X-Frame-Options` so the site can be embedded in Google Sites.






