# Audu Kanyinsola — Portfolio

A responsive, single-page portfolio for an Executive Assistant and Administrative Professional. Built with plain HTML, CSS, and JavaScript so it can be hosted on Cloudflare Pages without a framework or build process.

## Sections

- Introduction and professional positioning
- About and working principles
- Executive support, administrative operations, and client/project coordination
- Professional experience
- Tools and skills
- Clearly labelled illustrative work-sample previews
- Education and professional development
- Email, telephone, and WhatsApp contact links

## Deploy to Cloudflare Pages

1. Sign in to the Cloudflare dashboard.
2. Open **Workers & Pages** and choose **Create application** → **Pages** → **Connect to Git** (the exact labels may vary slightly).
3. Connect GitHub and select `olaoluwabankole3-cmd/kanyisola-portfolio`.
4. Set the production branch to `main`.
5. Select **None** or **No framework** as the framework preset.
6. Leave the build command blank and set the build output directory to `/` or `.` if the dashboard accepts the repository root as the output directory. Cloudflare Pages commonly uses `.` for a plain static site.
7. Start the deployment. The site entry point is `index.html`; no environment variables are required.
8. After deployment succeeds, open the generated `*.pages.dev` URL and check the contact links and mobile menu.

Cloudflare Pages will build a new deployment when changes are pushed to the connected production branch.

## Editing the portfolio

Most visible wording is in `index.html`. Review the name, contact details, job titles, dates, education, and training before sharing publicly. The work-sample modals are conceptual examples, not records of completed client assignments.

## Technical notes

- No Node.js dependencies or build step.
- Responsive layouts for desktop and mobile.
- Keyboard-accessible sample dialogs and navigation controls.
- Basic security headers are configured in `_headers`.
