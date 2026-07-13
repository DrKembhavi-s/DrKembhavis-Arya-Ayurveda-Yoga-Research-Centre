# Dr Kembhavi's Arya Ayurveda, Yoga & Research Centre — Website

Official website for **Arya Ayurveda, Yoga & Research Center**, Hubballi — a multi-specialty Ayurveda, Panchakarma, Yoga, Diet and Lifestyle Regulation & Wellness center.

**Live site:** [astangawellness.com](https://astangawellness.com) *(custom domain setup in progress)*

## About

This is a single-page static website providing information about the center's consultants, services, specialties, and patient resources, along with a direct booking pathway to our clinical platform.

## Features

- **Appointment booking** — links out to [MyVaidya.app](https://myvaidya.app) for scheduling, plus a direct WhatsApp contact option
- **Consultant profiles** — qualifications, specializations, and expandable CVs for Dr. Aakash S. Kembhavi and Dr. Anita Kadagad Kembhavi
- **About & philosophy** — center's approach to Ayurveda, healing process, and treatment principles
- **Understanding Ayurveda** — expandable educational content on Ayurvedic principles (doshas, dhatus, malas, purification therapies)
- **Services & specialties** — full listing of treatments offered
- **Diet & lifestyle tips**
- **Patient resources** — WhatsApp-based quick links for treatment tracking, diet plans, yoga guidance, medicine reminders, counseling, and health records
- **FAQ section**
- **Payment methods** overview
- **Live chat** via Tawk.to widget

## Tech Stack

- Single-file static site: HTML, CSS, and vanilla JavaScript (`index.html`)
- No backend or database — hosted as a static site
- Deployed via **GitHub Pages**

## Deployment

1. GitHub Pages is enabled on the `main` branch (root)
2. A `CNAME` file in the repo root points the custom domain `astangawellness.com` to this Pages deployment
3. DNS (A records + `www` CNAME) is configured at the domain registrar (BigRock) to route to GitHub Pages

## Contact

**Email:** drkembhavi@live.com
**Location:** #1st Floor-C, Om Annexe, Shirur Park Main Road, Prashant Colony, Vidyanagar, Hubballi 21, Karnataka, India

## Notes for Maintainers

- The site previously included an in-browser appointment booking form and a testimonials submission/display system. Both were removed (see commit history) in favor of directing bookings to MyVaidya.app; testimonials are pending a proper backend-supported solution before reintroduction, since static GitHub Pages sites cannot persist submitted data.
- Any future dynamic features (testimonials, appointment status, etc.) should be integrated through MyVaidya.app or another backend service rather than client-side-only JavaScript, since data submitted via plain JS on a static site is not saved or shared across visitors.

## License

© 2026 Arya Ayurveda, Yoga & Research Center. All rights reserved.
