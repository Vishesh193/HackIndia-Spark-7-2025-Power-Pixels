# HackIndia-Spark-7-2025-Power-Pixels
# Next Kya - Campus Assistance Website

CaampusAssist is a comprehensive campus assistance website built with Next.js and Tailwind CSS. It provides students with easy access to campus resources, services, and information all in one place.

## Features

- **Homepage**: Welcoming landing page with hero section, features overview, quick links to essential services, and latest announcements
- **Resources**: Information about academic resources and student services available on campus
- **Campus Map**: Interactive campus map with building directory and navigation assistance
- **Dining**: Campus dining locations, meal plans, and dietary accommodations
- **Housing**: Residence halls, housing application process, and related resources
- **Health**: Health services, counseling, insurance information, and wellness resources
- **Transportation**: Campus shuttle services, parking information, and alternative transportation options
- **Announcements**: Latest news, events, and important updates from around campus

## Tech Stack

- [Next.js](https://nextjs.org) - React framework for building the web application
- [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework for styling
- [React](https://reactjs.org) - JavaScript library for building user interfaces

## Getting Started

First, install the dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the website.

## Project Structure

```
src/
├── app/                  # Next.js app directory
│   ├── announcements/    # Announcements page
│   ├── dining/           # Dining information page
│   ├── health/           # Health services page
│   ├── housing/          # Housing information page
│   ├── map/              # Campus map page
│   ├── resources/        # Campus resources page
│   ├── transportation/   # Transportation page
│   ├── layout.tsx        # Root layout component
│   └── page.tsx          # Homepage
├── components/           # Reusable UI components
│   ├── AnnouncementsSection.tsx
│   ├── FeaturesSection.tsx
│   ├── Footer.tsx
│   ├── HeroSection.tsx
│   ├── Navbar.tsx
│   └── QuickLinksSection.tsx
└── styles/               # Global styles
```

## Customization

You can customize the website by:

1. Modifying the content in each page component
2. Adding real data instead of the placeholder content
3. Connecting to a backend API or CMS for dynamic content
4. Adding or modifying the styling using Tailwind CSS classes

## Next Steps

To make this website fully functional for a real campus:

1. Add real images and icons in the `/public` directory
2. Connect to a database or API for dynamic content
3. Implement user authentication for personalized features
4. Add interactive features like a real-time shuttle tracker
5. Implement search functionality across the website

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - explore Tailwind CSS features
- [React Documentation](https://reactjs.org/docs) - learn about React

## Deployment

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
