INDEPENDENTBILLER.COM WEBSITE PACKAGE
=====================================

FILES
- index.html: homepage
- services.html: services
- about.html: about page
- contact.html: contact page
- consultation.html: free consultation form
- privacy.html: basic privacy notice template
- assets/styles.css: responsive visual design
- assets/script.js: mobile menu and current year
- robots.txt and sitemap.xml: basic search-engine files
- CNAME: custom domain for GitHub Pages

BEFORE LAUNCH
1. Confirm that you control independentbiller.com and can access its DNS settings.
2. Review every service, price, and business statement for accuracy.
3. Add your real business phone number when you have one.
4. Review the privacy notice with qualified counsel and adjust it to your actual practices.
5. Do not collect patient names, dates of birth, insurance IDs, medical record numbers, diagnoses, claims or other PHI using these general website forms.
6. The forms currently use FormSubmit (a third-party form-to-email service) with chris@independentbiller.com as the destination. Before public launch, review FormSubmit's terms/privacy, submit a test inquiry, and complete the activation email if requested. If you do not want a third-party service, replace the form backend with a provider you approve. Do not use the form to send PHI.
7. The site states 3% of collections as a proposed service fee; a written contract should define covered services, calculation, exclusions, and payment terms.

LOCAL PREVIEW
Open index.html in a modern browser to preview the static pages. Internet is needed to load the optional Google Fonts; the site falls back to system fonts if unavailable.

FREE PUBLISHING OPTION: GITHUB PAGES
1. Create/sign in to a GitHub account.
2. Create a new PUBLIC repository named independentbiller-website (public repositories are supported by GitHub Free for Pages).
3. Upload the contents of this package to the repository root. Upload the files and the assets folder, not the ZIP file itself.
4. In repository Settings > Pages, set Build and deployment to deploy from a branch; choose main and / (root), then Save.
5. Wait for the default github.io website URL to appear and test it.
6. In Settings > Pages > Custom domain, enter independentbiller.com and save. Keep the included CNAME file in the repository root.
7. In GoDaddy Domain Portfolio > independentbiller.com > DNS, add/update the DNS records required by the current GitHub Pages documentation. For the root domain, GitHub currently documents A records:
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   For www, add a CNAME record pointing to YOUR-GITHUB-USERNAME.github.io (replace with your actual GitHub username).
   Remove conflicting website A/CNAME records for @ or www only after checking what they are used for.
   IMPORTANT: Do not delete MX/TXT records needed for your email. Do not change nameservers unless you know why.
8. Wait for DNS propagation; it can take up to 24 hours (sometimes longer). In GitHub Pages settings, enable Enforce HTTPS when available.
9. Test the root domain, www domain, mobile layout, all links, and the form.

OFFICIAL GUIDES
GitHub custom domains: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
GitHub Pages publishing: https://docs.github.com/en/pages/getting-started-with-github-pages
GoDaddy DNS records: https://www.godaddy.com/en-in/help/manage-dns-records-680

IMPORTANT
This is a static informational website package. GitHub Pages does not provide a server-side database or form handler. The included form uses an external form-to-email service. A production medical billing operation may require additional security, contractual, and HIPAA-related safeguards; do not use this public website to exchange PHI.
