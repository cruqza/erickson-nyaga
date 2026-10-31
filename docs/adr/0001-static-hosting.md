# ADR 0001 — Static hosting with Astro + Vercel

- **Date:** 2026-10-31
- **Status:** Accepted
- **Context:** The portfolio needed to present six projects across three
  disciplines and be easy for a recruiter to scan, while staying cheap to host
  and maintain. A framework that scales to six projects and serves nothing but
  static HTML/CSS was the right shape for the goal.
- **Decision:** Use Astro as the static site generator, deployed to Vercel
  through the GitHub Git integration (every push to `main` auto-deploys).
  Shared CSS lives in `src/styles/global.css`; pages are Astro components.
- **Consequences:**
  - Recruiters get a fast, static first load and no runtime dependencies to
    break.
  - New projects can be dropped into the featured grid without touching the
    build tooling.
  - Vercel's automatic deploy loop keeps the live URL in sync with the repo.
