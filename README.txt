ORTHOSHAHID.COM WEBSITE — DEPLOYMENT NOTES

Included:
- index.html: complete responsive website (HTML, CSS, JavaScript, SEO metadata)
- README.txt: setup and publishing checklist
- CNAME: intended custom domain (www.orthoshahid.com)

IMPORTANT BEFORE PUBLISHING
1. Confirm that you own/control orthoshahid.com and can edit its DNS.
2. Confirm the phone number, clinic address, clinic hours, credentials and current consultation location.
   The clinic is shown as Health First Clinic, Bengaluru. Add a full street address only after confirming the exact address to publish; the public EKA profile may show a different practice location.
3. Replace the generic stock clinical photos with Dr. Shahid's own approved professional portrait/clinic photos for authenticity.
4. Confirm exact fellowship designation and approved wording for credentials.
5. Test EKA Care appointment link, phone, WhatsApp and all navigation on mobile.
6. This is a static website. It does not collect patient data or include a backend appointment form.

QUICK LOCAL PREVIEW
- Extract the ZIP.
- Double-click index.html to open it in a browser.
- Internet is required for the stock photos and external EKA Care/WhatsApp links.

PUBLISHING OPTION: GITHUB PAGES
1. Create a GitHub repository and upload index.html and CNAME.
2. In repository Settings > Pages, enable publishing from the main branch/root.
3. Add www.orthoshahid.com as the custom domain in Pages settings.
4. At your DNS provider, configure the www CNAME record to the GitHub Pages hostname shown in your Pages settings. Do not guess the target hostname.
5. Configure the apex domain orthoshahid.com as a redirect to https://www.orthoshahid.com or configure the supported apex DNS records as directed by GitHub.
6. Enable HTTPS when available. DNS changes can take time to propagate.
7. Do not change nameservers or existing mail-related DNS records unless you understand their effect.

Official guide:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
