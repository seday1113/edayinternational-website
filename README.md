# Eday International LLC Website

Responsive static website for IT Consulting and IT Staffing/Recruitment.

## Preview locally
Open `index.html` in your browser, or run `python3 -m http.server 8000` and visit http://localhost:8000.

## Cloudflare Pages deployment
1. Create a GitHub repository named `edayinternational-website` and upload these files at repository root.
2. In Cloudflare dashboard go to Workers & Pages → Create → Pages → Import an existing Git repository.
3. Select the repository, use no build command, and set the output directory to `/` (repository root), then deploy. Alternatively use Cloudflare Pages Direct Upload for these static files.
4. In the Pages project open Custom domains, add `edayinternational.com` and `www.edayinternational.com`, and follow the DNS prompts.
5. Test HTTPS, mobile layout, navigation, and links.

## Before publishing
- `script.js` deliberately disables the contact form until you provide a verified business inbox and choose an email or form service. Never claim that submissions are delivered before configuring it.
- Add actual business contact details, privacy policy, and any legal disclosures appropriate to your business.
- Replace draft service descriptions with confirmed offerings.
- Check logo availability/trademark conflicts before commercial use.
