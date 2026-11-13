# Strada Studio — web design studio website

**Live:** https://stradastudio.co.za

The marketing site for my web design studio in Gqeberha, built to win small-business clients.

## The problem
Small businesses in South Africa often have no website, or a dated one that doesn't convert. As a studio, the best proof I can offer is my own site: it has to load fast, look distinctive, explain what I do in plain language, and make it easy to start a conversation.

## What I built
- A motion-driven site with interactive 3D elements, showcasing services and past work.
- A contact flow that emails enquiries to the studio and stores them in a database, with consent captured at the point of submission.
- Legal pages (Privacy, Terms) written around POPIA and the ECT Act: lawful basis, retention, user rights and Information Officer details.
- SEO and performance work: server-rendered pages, optimised images and proper metadata.

## Stack
Next.js (React, TypeScript), Tailwind CSS, Framer Motion, Spline 3D, Supabase, Resend for email. Deployed on Vercel from a private repository.

## Security and quality
- Secrets live only in environment variables; none are committed, and the full git history was scanned for leaked keys.
- Contact form input is validated server-side.
- Privacy-by-design: only the data needed to answer an enquiry is collected, with explicit consent.

## Issues encountered & how I solved them
- **3D and motion elements fighting page load speed** — a studio selling "fast, modern websites" can't itself be slow. I solved this by rendering pages server-side and lazy-loading the Spline 3D scenes and Framer Motion sequences so they only cost load time once they're actually in view.
- **Legal pages for a South African audience had no off-the-shelf template.** I wrote the Privacy and Terms pages around POPIA and the ECT Act directly — lawful basis, retention periods, user rights and a named Information Officer — rather than reusing a generic international template that wouldn't hold up locally.
- **Enquiry data needed to be captured without becoming a liability.** I limited the contact flow to only the fields needed to respond, added consent capture at the point of submission, and validated every input server-side rather than trusting the client.
- **Proving the studio's own claims** — the only credible proof that I can build fast, distinctive sites is my own site passing that bar, so SEO and performance work (metadata, image optimisation, server rendering) were treated as a deliverable, not an afterthought.

## Result
A live, production site at stradastudio.co.za, in active use to win client work, combining motion and 3D with server-rendered performance and SA-compliant legal pages.

## About this repository
This is a **showcase repository**. The production source is private. © Craig Chadley Johnson. All rights reserved. See [LICENSE](LICENSE).

Built by [Craig Chadley Johnson](https://github.com/craig-builds) — johnsoncraig.dev@gmail.com
