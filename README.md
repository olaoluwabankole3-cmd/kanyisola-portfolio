# Audu Kanyinsola — Portfolio

A responsive, single-page portfolio for an Executive Assistant and Administrative Professional. Built with plain HTML, CSS, and JavaScript so it can be hosted on Cloudflare Pages without a framework or dependency installation.

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

1. Open the [Cloudflare dashboard](https://dash.cloudflare.com/) and select your account.
2. Go to **Workers & Pages** → **Create application** → **Pages** → **Connect to Git**.
3. Connect GitHub and select `olaoluwabankole3-cmd/kanyisola-portfolio`.
4. Set the production branch to `main`.
5. Choose **None** or **No framework** as the framework preset.
6. Set the **Build command** to `exit 0` and the **Build output directory** to `.` (the repository root, where `index.html` lives). Leave the root directory at its default.
7. Start the deployment. No environment variables are required.
8. When the deployment succeeds, open the generated `*.pages.dev` URL and test the page on desktop and mobile, including the contact links and sample previews.

Cloudflare Pages can automatically rebuild and deploy new commits pushed to the connected production branch. See the [official static HTML deployment guide](https://developers.cloudflare.com/pages/framework-guides/deploy-anything/) for current dashboard details.

## Editing the portfolio

Most visible wording is in `index.html`. Review the name, contact details, job titles, dates, education, and training before sharing publicly. The work-sample modals are conceptual examples, not records of completed client assignments.

## Technical notes

- No Node.js dependencies or framework build step.
- Responsive layouts for desktop and mobile.
- Mobile navigation and keyboard-dismissable sample dialogs.
- Basic security headers are configured in `_headers`.
