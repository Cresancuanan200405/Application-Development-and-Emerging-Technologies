# Developer Portfolio

This is a personal developer portfolio built with Next.js (App Router), TypeScript, and Tailwind CSS, optimized for deployment on Vercel.

## Sections

- **About Me** – who you are as a developer.
- **Key Projects** – three projects that showcase your skills, learning progress, and career direction.
- **Currently Learning** – topics you are actively studying to grow as a developer.
- **Contact** – ways to reach you.

## Prerequisites

- **Git**: https://git-scm.com/downloads
- **Node.js**: v18.17 or newer (LTS recommended) – https://nodejs.org
- Optional: **VS Code** for best DX – https://code.visualstudio.com/

## Clone & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Cresancuanan200405/Cuanan-Portfolio-IT-31.git
   cd Cuanan-Portfolio-IT-31
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
   - The app runs on http://localhost:3000 by default. If 3000 is in use, Next.js will use another port (e.g., 3001).

## Production Build

```bash
npm run build
npm run start
```

## Contact Form & Inquiries

- The contact form lives on the **Contact** section of the homepage (route `/#contact`).
- Submissions are sent via **Web3Forms** and can be viewed in your dashboard:
  - https://app.web3forms.com/
- The access key is defined in the client form as a hidden input in [app/page.tsx](app/page.tsx). If you fork this project, replace the `access_key` value with your own Web3Forms key from the dashboard.

## Configuration to Update

- Personal details and social links (GitHub, Facebook) in [app/page.tsx](app/page.tsx).
- Favicon/icon configured in [app/layout.tsx](app/layout.tsx) referencing `public/portfolio.png`.

## Deployment

- This project is optimized for **Vercel**.
- Do not commit or upload the `.next` directory – it is a build output and will be created during `vercel build` or `npm run build`.

## Notes

- Tailwind CSS is already configured in [app/globals.css](app/globals.css) and [tailwind.config.ts](tailwind.config.ts).
- If you see a port warning or styling not updating, try a hard refresh (Ctrl+Shift+R) and ensure your Node.js version meets the requirement.

Before sharing this portfolio, update your name, email, GitHub, and Facebook links in `app/page.tsx`.
