# Add "Enter Case Academy" CTA Button to Landing Page

## Context
I have a Case Academy landing page at `perrykramer.com/case-academy` that's hosted on WordPress but managed via GitHub and edited with Claude Code. The page is built with HTML/CSS/JS.

I've just launched the Case Academy platform (dashboard, courses, practice problems, community) as a separate Next.js app hosted on Vercel at:

**https://case-academy-app.vercel.app**

I need to add a prominent CTA button to my existing landing page that sends visitors to the Vercel app to sign in or create an account.

## What I Need

Add a prominent "Enter Case Academy" (or similar) button to the existing landing page. Requirements:

1. **Placement:** The button should be highly visible — ideally in the hero/header section and possibly repeated further down the page. Use your judgment based on the current page layout.

2. **Design:** Match the existing page's design language exactly. Use the brand colors:
   - Navy: `#1e3a5f`
   - Amber: `#f59e0b`
   - Font: Space Grotesk
   - The button should feel like a natural part of the page, not bolted on

3. **Link:** The button should link to `https://case-academy-app.vercel.app`

4. **Copy suggestions** (pick what fits the page best):
   - Primary CTA: "Enter Case Academy →" or "Sign In to Case Academy →" or "Get Started →"
   - Supporting text (optional): "Create your free account and try our first practice problem"

5. **Behavior:** Opens in the same tab (not a new tab) since we want users to transition to the app

## Instructions
- First, read through the existing landing page HTML to understand the current design, layout, and styling patterns
- Then add the CTA button in a way that feels native to the existing design
- Do NOT change any existing content or styling — only add the new button/CTA
- If there's already a CTA or button area, integrate near it
- Make the button responsive (works on mobile too)
