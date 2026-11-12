# Beth Shalom homepage refresh notes

## Before and after

- **Header:** The official seal now appears in a medium 48px mark at the far right of the public header. The wordmark remains on the left; both link home.
- **Hero:** Replaced the single static hero treatment with a full-width HD video carousel, subtle ivory gradient, and translucent glass content/history panels. Removed the “Registered Society Est.” badge, added a Virtual Tour action, and changed the legacy metric to 60+.
- **Family admissions:** Replaced the compact dormitory banner with a calm admissions portal for families of children with autism and their parents. It keeps dormitory capacity and fee transparency statements, adds the four-step admissions pathway, family eligibility guidance, preparation notes, and a clear application link.
- **Global theme:** Updated the public, donation, facility, admission, and admin pages to the same warm-white, soft-gray, sage, and mint tokens. Components that use semantic surface/action tokens inherit the updated colors.

## Prototype flow

1. The hero starts on the campus slide with the existing campus image as the fallback poster.
2. Previous/next, slide dots, or autoplay move between campus, care, and community clips; each clip updates its attribution.
3. Pause/play, hover/focus pause, and reduced-motion behavior remain available; no central play button is shown.
4. **Virtual Tour** opens `/living-spaces/visualizer/`; admission actions open `/admission/`.
5. The family portal presents the four admission steps and expandable family eligibility/document details.
6. Existing living-space cards and the Society & Donations route remain available below the updated sections.

## Content and media notes

The timeline uses milestones already described by the site: society establishment in 1965, registration in 1967, and current care. The independent men’s and women’s dormitories are still described separately from integrated family living options. Hero footage is illustrative third-party stock, not footage of Beth Shalom; its source is labeled in the UI and documented in `STYLE-GUIDE.md`.

## Responsive behavior

The existing responsive grid/type architecture is preserved. On mobile, hero identity/history stacks above the copy; metrics wrap to two columns, CTAs and controls wrap, and the admissions portal becomes a single column. Tablet layouts flow into intermediate grid sizes; desktop uses a 4/8 hero split and a 5/7 admissions split.
