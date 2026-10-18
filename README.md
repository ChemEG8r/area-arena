# Area Arena

Compound-shape area practice for VJ — the most sophisticated of the study
apps. Every quiz procedurally DRAWS 8 brand-new compound figures (SVG with
worksheet-style dimension arrows) across 8 shape families: rectangle +
semicircle stadiums, houses (rect + triangle), L-shapes with hidden widths,
ice-cream cones (triangle + semicircle), rectangle + parallelogram stacks
with hidden heights, right trapezoids, rectangles with semicircular
CUT-OUTS (subtraction!), and 3-piece rockets — plus two rule questions.

Answers are typed as decimals (pi = 3.14, round to 2 places). On a miss —
or on demand after a correct answer — the app shows a full step-by-step
breakdown where each step RE-DRAWS the figure with that piece highlighted:
split, find hidden dimensions, apply each formula with the real numbers,
then add (or subtract the hole). Every generated figure is independently
verified with the shoelace formula plus exact circular terms.

Cross-device history with exact misses via /api/scores (Cloudflare Pages
Function + Workers KV bound as SCORES).

Deploy: `npx wrangler pages deploy . --project-name area-arena --branch main`
