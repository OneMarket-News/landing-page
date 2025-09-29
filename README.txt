# OneMarket — Static Landing (No Build Step)

This is a single-file static site you can deploy in minutes.

## Deploy on Netlify (drag & drop)
1) Download this folder and unzip.
2) Go to https://app.netlify.com/drop
3) Drag **index.html** to upload.
4) You’ll get a live URL instantly.

## Connect your own domain
- In Netlify → your site → **Domains** → Add custom domain → follow the DNS instructions.
- Add the A/CNAME records at your domain registrar (GoDaddy/Namecheap/etc.).
- Wait a bit for DNS to propagate, then your domain points to this site.

## Enable the forms
- Create a free endpoint at **Formspree** (https://formspree.io). You’ll get a URL like `https://formspree.io/f/abcyz123`.
- Open **index.html**, find `FORMSPREE_ENDPOINT` near the bottom, and replace the placeholder with your URL.
- Test by submitting your email—check Formspree dashboard or email.

## Editing later
- Open index.html in any text editor. Update copy, colors, or sections.
- For images, create an `images/` folder next to this file and reference them with `<img src="images/yourlogo.png" />`.
