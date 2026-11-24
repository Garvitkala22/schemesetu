# SchemeSetu — Entrepreneur & Citizen Scheme Discovery Platform

SchemeSetu is a zero-dependency, single-file front-end prototype built with plain HTML, CSS, and vanilla JavaScript. It helps Indian entrepreneurs, MSMEs, and citizens discover government schemes they qualify for using rule-based AI eligibility matching.

## Features

- **Entrepreneur-First Scheme Discovery:** Includes 5 central entrepreneur/startup schemes (PM Mudra Yojana, Startup India Seed Fund Scheme, PMEGP, Credit Guarantee Scheme for Startups, and Stand-Up India) alongside Students, Farmers, and Senior Citizens categories.
- **Light & Dark Mode Switcher:** Visual segmented Light/Dark toggle in both the login screen and dashboard navbar, persisted in `localStorage`.
- **Authentication Flow:** Login and Sign-up screens with `localStorage` session persistence, automatic redirect to Login when logged out, and a one-click Demo Founder Account.
- **AI Eligibility Matching Engine:** Computes a 0–100% match score, displays a badge (`Highly Eligible` 80%+, `Partially Eligible` 50–79%, `Not Eligible` <50%), and generates a plain-English explanation for each scheme.
- **Search, Filters, Bookmarks & Details Modal:** Live keyword search, category and match-level filters, `localStorage` saved bookmarks, and a modal with benefits, eligibility rules, required documents, and official portal links.
- **Floating AI Assistant:** Keyword-based chatbot that answers questions about top matches, entrepreneur funding, required documents, and application steps.

## Run Locally

Download or clone this repository and double-click `index.html` to open it in any web browser—no installation or build step required.

## Deploy on Vercel

1. Push this repository to GitHub (private or public).
2. Import the repository at https://vercel.com/new.
3. Choose **Framework Preset: Other** (no build command needed) and click **Deploy**.

## Editing Scheme Data

Open `index.html` and edit the `SCHEMES_DATA` array inside the `<script>` tag to add, remove, or update schemes, eligibility rules, documents, and official apply links.
