# Rahul Gupta Portfolio Website

A modern, responsive, recruiter-focused personal portfolio for **Rahul Gupta** targeting Data Analyst / IT Support / Technical roles.

## Local Development

This is a static site.

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Customize Personal Links

Update these placeholders in `index.html`:

- Email: `rahul@example.com`
- LinkedIn: `https://linkedin.com/in/rahulgupta`
- GitHub: `https://github.com/rahulgupta`
- Formspree endpoint: `https://formspree.io/f/your-id`

## Resume Button

The resume button downloads `Rahul_Gupta_Resume.pdf` from the project root.
Replace the placeholder file with your latest resume PDF.

## Deployment

### Option 1: Vercel
1. Push this repo to GitHub.
2. In Vercel, click **New Project** and import the repo.
3. Keep default settings (Framework Preset: Other / static).
4. Deploy.

### Option 2: Netlify
1. Push this repo to GitHub.
2. In Netlify, click **Add new site** → **Import an existing project**.
3. Build command: _(leave empty)_
4. Publish directory: `.`
5. Deploy.

## Connect a Custom Domain (`rahulgupta.dev`)

### On Vercel
1. Go to **Project Settings** → **Domains**.
2. Add `rahulgupta.dev` and `www.rahulgupta.dev`.
3. At your domain registrar, set:
   - `A` record for root (`@`) to `76.76.21.21`.
   - `CNAME` for `www` to `cname.vercel-dns.com`.
4. Wait for DNS propagation and verify in Vercel.

### On Netlify
1. Go to **Domain settings** → **Add custom domain**.
2. Add `rahulgupta.dev`.
3. Configure DNS using Netlify DNS instructions (recommended) or external DNS records shown in Netlify.
4. Verify HTTPS is issued.

## SEO and Recruiter Optimization Included

- Metadata title and description
- Open Graph + Twitter tags for LinkedIn/social preview
- Keywords for: Data Analyst, Python, SQL, Tableau, IT Support
- Fast-loading single-page static site
