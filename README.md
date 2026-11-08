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

## About this repository
This is a **showcase repository**. The production source is private. © Craig Chadley Johnson. All rights reserved. See [LICENSE](LICENSE).

Built by [Craig Chadley Johnson](https://github.com/craig-builds) — johnsoncraig.dev@gmail.com
