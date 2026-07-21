# A Clear Path — Development Guide

## Visual Verification

After every frontend change:
1. Take a screenshot of each page (Mentorship, About, Testimonials, Apply, Contact)
2. Verify the change matches the request before committing
3. If it doesn't look right, ask me what's wrong before pushing

## Frontend Priorities

- Always load the frontend-design skill before CSS changes
- Use modern, professional fonts (not Georgia/Arial)
- Ensure spacing, hierarchy, and visual balance feel intentional
- Test on mobile (380px) and desktop views
- Use the existing colour palette: #1E5A48 (deep green), #C79A3B (gold), #F7F4EC (cream)

## Content Voice

- Use conversational, human language
- No em dashes
- No templated phrasing
- Match Hakeem's tone throughout

## Deployment

- Cloudflare's production deployment tracks `main`, not the feature branch
- After a change is reviewed and approved, push to the feature branch AND
  merge it into `main` (open a PR and merge it) so the live Cloudflare URL
  actually updates. Pushing to the feature branch alone is not enough.
