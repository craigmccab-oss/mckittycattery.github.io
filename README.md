# Mc Kitty Cattery – Static Website

Clean, responsive static version of [mckittycattery.co.za](https://www.mckittycattery.co.za) ready for **GitHub Pages**.

## Pages
- `index.html` – Home + customer testimonials
- `about.html` – About the facility + Vimeo video + booking process
- `rates.html` – Full rates table and booking confirmation steps
- `contact.html` – Address, phone, email, WhatsApp + Google Map
- `files/terms.pdf` – Terms & Conditions PDF
- `css/style.css` – All styling
- `images/` – Logo and facility/cat photos

## How to host on GitHub Pages

1. Create a new repository on GitHub (e.g. `mckittycattery` or `mckittycattery.github.io`).
2. Upload **all** the files and folders in this directory (keep the structure).
3. Go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**.
5. Select branch `main` (or `master`) and folder `/ (root)`.
6. Click Save. After a minute or two your site will be live at:
   - `https://YOUR-USERNAME.github.io/REPO-NAME/`  
     or  
   - `https://YOUR-USERNAME.github.io/` if the repo is named `YOUR-USERNAME.github.io`.

### Custom domain (optional)
If you want to keep using **www.mckittycattery.co.za**:
1. In the repo Settings → Pages → Custom domain, enter `www.mckittycattery.co.za`.
2. At your domain registrar, set a CNAME record for `www` pointing to `YOUR-USERNAME.github.io`.
3. (Optional) Add an A record for the apex domain using GitHub’s published IPs.

## Notes
- This is a clean rebuild (not a 1:1 scrape of the Zoho template) so it is fast, mobile-friendly, and easy to edit.
- Social links, rates, testimonials, address and the Vimeo facility video are included.
- Edit any `.html` file or `css/style.css` with a normal text editor. No build step required.
