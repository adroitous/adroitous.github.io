# Portfolio Futuristic Redesign Spec

## Goal

Redesign `adroitous.github.io` into a one-page, cinematic portfolio for mostly nontechnical visitors: funders, publishers, collaborators, education buyers, and parents.

The current page proves range, but it reads too busy and technical. The redesign should feel premium, futuristic, focused, and emotionally legible: closer to SpaceX, Runway, and Apple than a developer dashboard.

Primary message:

> I build playable worlds, AI learning products, and operating systems that make ambitious work possible.

## Audience And Positioning

The page should not lead with framework fluency. It should lead with what the work enables:

- Playable worlds with a clear audience and visual identity.
- AI learning products that make students and buyers feel supported, not overwhelmed.
- Behind-the-scenes systems that make complex creative work repeatable.
- A public proof trail for people who want to inspect the work more deeply.

Avoid copy that sounds like "I know many frameworks." Prefer copy that sounds like "I can take a large idea from concept to playable, usable, visible proof."

## One-Page Information Architecture

Use a single scrolling page with fewer, larger sections:

1. **Cinematic Hero**
   - Purpose: make the portfolio feel immediately premium and understandable.
   - Primary CTA: `Play Jianghu Ascendant`.
   - Secondary CTA: `View Work`.
   - Tertiary link: `GitHub`.

2. **Jianghu Ascendant**
   - Purpose: the flagship live proof.
   - Weight: largest project section on the page.
   - CTA: live game link, `https://jianghu-ascendant.pages.dev`.

3. **Project Sanctuary / cardlyB**
   - Purpose: second major visual game proof.
   - Weight: large cinematic section, but slightly smaller than Jianghu.
   - CTA: source or project link.

4. **AcePrepLabs**
   - Purpose: accessible AI learning product proof.
   - Weight: major product section, warm and human, not a technical stack dump.
   - CTA: product/site link if present in the current page.

5. **Harness Ecosystem**
   - Purpose: explain the behind-the-scenes operating system for AI-assisted building.
   - Weight: conceptual section with restrained visuals, not a dashboard.
   - CTA: GitHub/source link.

6. **Archive Proof Strip**
   - Purpose: compress older projects into credibility without creating clutter.
   - Weight: small horizontal strip or compact grid.

7. **Final CTA**
   - Purpose: route the visitor to the most useful next action.
   - CTAs: `Play Jianghu`, `Explore GitHub`, and optional contact/collaboration language if a contact link exists.

Header navigation should be minimal:

- `Games`
- `Learning`
- `Systems`
- `Archive`
- CTA button: `Play Jianghu`

## Exact Sections And Copy Direction

### 1. Cinematic Hero

Visual direction:

- Full-bleed cinematic image background using Jianghu art.
- Prefer `stone-courtyard.webp` or `jianghu-road-backdrop.webp`.
- Dark premium overlay, deep blacks, pale gold, warm white, sharp red accent.
- Keep the hero text large, sparse, and calm.
- Leave a visible hint of the Jianghu section below the fold.

Copy:

- Eyebrow: `Playable worlds / AI learning / production systems`
- H1: `Playable worlds. AI learning products. Operating systems for ambitious builds.`
- Body: `Vincent Lin builds cinematic game prototypes, accessible AI education tools, and the behind-the-scenes systems that make complex creative work repeatable.`
- Primary CTA: `Play Jianghu Ascendant`
- Secondary CTA: `View Work`
- Tertiary link: `GitHub`

Suppress:

- Do not show technical stats in the hero.
- Do not mention Vite, Three.js, FastAPI, Supabase, LangChain, C#, Python, or PowerShell in the hero.
- Do not make GitHub the primary CTA.

### 2. Jianghu Ascendant

Priority:

- This is the main project on the page.
- It should feel like a live cinematic game launch section, not a repo card.

Visual direction:

- Use real Jianghu image assets, not the current CSS-only fake battlefield.
- Create a large editorial layout with one dominant image and supporting stills.
- Recommended composition:
  - Main wide image: `jianghu-route-atlas.webp` or `jianghu-road-backdrop.webp`.
  - Atmospheric square/portrait layer: `stone-courtyard.webp`.
  - Enemy character fan: `white-serpent-witch.webp`, `black-eagle-captain.webp`, `snow-daoist.webp`, `crimson-lute-assassin.webp`.
  - Small level still strip: `river-gate.webp`, `old-shrine.webp`, `iron-pagoda.webp`, `rain-teahouse.webp`, `mirror-terrace.webp`, `bell-approach.webp`.
  - Small `qi.png` icon may be used as a restrained motif, not a repeated decoration.

Copy:

- Eyebrow: `Live cinematic browser game`
- Heading: `Jianghu Ascendant`
- Subheading: `A martial-arts deckbuilder you can play now.`
- Body: `Choose a route through a mythic wuxia world, build a martial style, and survive duels against rivals, assassins, captains, and spirits. Jianghu Ascendant is the clearest live proof of the portfolio: a playable world with atmosphere, progression, combat, and a public build.`
- Proof points:
  - `Playable live build`
  - `Route-based roguelike structure`
  - `Martial-arts deckbuilding combat`
  - `Cinematic enemy and level art`
- CTA: `Play the live build`
- Secondary link: `View source`

Implementation notes:

- Link the CTA to `https://jianghu-ascendant.pages.dev`.
- The section should be large enough that it reads as the flagship, not one item in a list.
- Technical tags may be moved into visually quiet metadata or removed entirely. If retained, limit to one line: `Browser game / deckbuilder / wuxia roguelike`.

### 3. Project Sanctuary / cardlyB

Priority:

- This is the second major game section.
- It should feel like a polished concept/prototype pitch with strong visual art.

Visual direction:

- Use existing files already in this repo:
  - `assets/portfolio/sanctuary-combat.png`
  - `assets/portfolio/sanctuary-character.png`
  - `assets/portfolio/sanctuary-card.png`
  - `assets/portfolio/sanctuary-title.png`
- Use `sanctuary-combat.png` as the primary background.
- Overlay `sanctuary-character.png` and `sanctuary-card.png` with depth, but keep them readable.
- Use `sanctuary-title.png` only as a small title mark or supporting emblem, not as the hero background.

Copy:

- Eyebrow: `Narrative card battler`
- Heading: `Project Sanctuary / cardlyB`
- Subheading: `A character-driven card battler about survival, style, and hard choices.`
- Body: `Project Sanctuary pairs roguelike card combat with an anime-styled party world. It shows a second path through the same portfolio promise: visual direction, systems design, playable mechanics, and production planning moving together.`
- Proof points:
  - `Party roguelike card combat`
  - `Character-first visual identity`
  - `Playable prototype direction`
  - `Design, art, audio, and QA planning`
- CTA: `View project`

Suppress:

- Do not foreground `Godot 4 .NET`, `C#`, or QA harness wording in the visible headline area.
- If technology is included, put it in a small muted line at the bottom.

### 4. AcePrepLabs

Priority:

- This is the accessible AI learning product section.
- It should speak to parents, schools, and education buyers.

Visual direction:

- Use warm, human visuals instead of app-dashboard density.
- Recommended composition:
  - `high school girl.jpg` as the human anchor.
  - `owl-mascot.png` as a friendly brand accent.
  - `search_results.png` and `before_search_click.png` as small proof screenshots, framed like product evidence.
- Keep screenshots secondary. The emotional center should be learning support and trust.

Copy:

- Eyebrow: `AI learning product`
- Heading: `AcePrepLabs`
- Subheading: `AI practice that feels clear, supportive, and student-centered.`
- Body: `AcePrepLabs turns practice, feedback, and question workflows into a more approachable learning experience. The product direction is not "AI for its own sake"; it is AI that helps students know what to practice next and gives educators a clearer path to support them.`
- Proof points:
  - `Student-friendly practice flow`
  - `AI-supported tutoring and feedback`
  - `Question-bank workflow proof`
  - `Built for families, educators, and training buyers`
- CTA: `Visit AcePrepLabs`

Suppress:

- Do not list `Next.js 15`, `FastAPI`, `Supabase`, `LangChain`, `React Native`, or `Selenium` in the main section copy.
- Do not describe the scraper as the product. Treat screenshots as evidence of content workflow support.

### 5. Harness Ecosystem

Priority:

- This section explains the operating system behind the work without becoming a technical dashboard.

Visual direction:

- Abstract, premium, sparse.
- Use a clean diagram-like layout: three connected pillars or a quiet orbital system.
- Avoid terminal screenshots, dense tables, code blocks, and repo badges.

Copy:

- Eyebrow: `Behind the scenes`
- Heading: `A production operating system for AI-assisted building.`
- Body: `The harness work turns ambitious projects into repeatable production loops: agents can explore, build, test, critique, and preserve context while the project keeps moving. It is the invisible layer behind faster game production, stronger prototypes, and clearer handoffs.`
- Pillars:
  - `Coordinate` - `Break large work into clear roles, files, and responsibilities.`
  - `Verify` - `Use tests, browser checks, playtest loops, and review passes before claiming work is done.`
  - `Remember` - `Preserve decisions, evidence, and handoff context so complex projects do not reset every session.`
- CTA: `Explore the systems`

Suppress:

- Do not describe this as `FastAPI`, `SQLite`, `REST API`, `Dolt`, `Bash`, or `Claude Code` in the main copy.
- Do not use the current dashboard-like project panels.
- Do not lead with "11 autonomous departments"; if retained, phrase it as a small proof note: `Multi-role agent workflow experiments`.

### 6. Archive Proof Strip

Purpose:

- Keep older work visible without letting it dominate the page.
- This section should support credibility, not compete with the major priorities.

Recommended entries:

- `Physics Equation Playground` - `Interactive physics prototyping.`
- `LocalTelemetry` - `Observability for AI coding sessions.`
- `Claude PowerShell Hooks` - `Local workflow notifications.`
- `Resume JSON Generator` - `Structured AI resume workflows.`
- `YouTube Comments Classifier` - `NLP experiments and ranking.`
- `K-Means Experiments` - `Clustering and benchmark analysis.`
- `Buffer Overflow Exercises` - `Systems fundamentals.`

Layout:

- One compact strip or two-row grid.
- Each item gets a name and one short phrase only.
- No tags, badges, long descriptions, language labels, or screenshots.

### 7. Final CTA

Copy:

- Heading: `Start with the playable work. Then inspect the proof.`
- Body: `The fastest way to understand the portfolio is to play Jianghu Ascendant, then follow the public project trail behind the games, learning products, and production systems.`
- CTAs:
  - `Play Jianghu`
  - `Explore GitHub`

## Asset Mapping And Files To Copy

Create this destination structure:

```text
assets/portfolio/jianghu/
assets/portfolio/aceprep/
```

Existing assets already in the repo:

| Current file | Use |
| --- | --- |
| `assets/portfolio/sanctuary-title.png` | Sanctuary emblem/supporting mark |
| `assets/portfolio/sanctuary-combat.png` | Sanctuary primary background |
| `assets/portfolio/sanctuary-character.png` | Sanctuary foreground character |
| `assets/portfolio/sanctuary-card.png` | Sanctuary foreground card |

Copy Jianghu assets:

| Source | Destination | Use |
| --- | --- | --- |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/arena/stone-courtyard.webp` | `assets/portfolio/jianghu/stone-courtyard.webp` | Hero or Jianghu atmosphere |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/map/jianghu-route-atlas.webp` | `assets/portfolio/jianghu/jianghu-route-atlas.webp` | Jianghu main visual |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/map/jianghu-road-backdrop.webp` | `assets/portfolio/jianghu/jianghu-road-backdrop.webp` | Hero/Jianghu background |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/map/jianghu-handscroll-route.webp` | `assets/portfolio/jianghu/jianghu-handscroll-route.webp` | Route detail strip |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/river-gate.webp` | `assets/portfolio/jianghu/river-gate.webp` | Level still |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/old-shrine.webp` | `assets/portfolio/jianghu/old-shrine.webp` | Level still |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/iron-pagoda.webp` | `assets/portfolio/jianghu/iron-pagoda.webp` | Level still |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/rain-teahouse.webp` | `assets/portfolio/jianghu/rain-teahouse.webp` | Level still |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/mirror-terrace.webp` | `assets/portfolio/jianghu/mirror-terrace.webp` | Level still |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/bell-approach.webp` | `assets/portfolio/jianghu/bell-approach.webp` | Level still |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/enemies-webp/white-serpent-witch.webp` | `assets/portfolio/jianghu/white-serpent-witch.webp` | Enemy portrait |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/enemies-webp/black-eagle-captain.webp` | `assets/portfolio/jianghu/black-eagle-captain.webp` | Enemy portrait |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/enemies-webp/snow-daoist.webp` | `assets/portfolio/jianghu/snow-daoist.webp` | Enemy portrait |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/enemies-webp/crimson-lute-assassin.webp` | `assets/portfolio/jianghu/crimson-lute-assassin.webp` | Enemy portrait |
| `/home/vincent/GitRepo/jianghu-ascendant/public/images/ui/resources/qi.png` | `assets/portfolio/jianghu/qi.png` | Small motif/icon |

Copy AcePrep assets:

| Source | Destination | Use |
| --- | --- | --- |
| `/home/vincent/GitRepo/acepreplabs/AcePrepLabsLandingPage/public/owl-mascot.png` | `assets/portfolio/aceprep/owl-mascot.png` | Friendly product accent |
| `/home/vincent/GitRepo/acepreplabs/AcePrepLabsLandingPage/public/high school girl.jpg` | `assets/portfolio/aceprep/high-school-girl.jpg` | Human learning image |
| `/home/vincent/GitRepo/acepreplabs/AcePrepLabSATOfficialScrapper/search_results.png` | `assets/portfolio/aceprep/search-results.png` | Workflow proof screenshot |
| `/home/vincent/GitRepo/acepreplabs/AcePrepLabSATOfficialScrapper/before_search_click.png` | `assets/portfolio/aceprep/before-search-click.png` | Workflow proof screenshot |

Gemini may use these commands to copy the assets:

```bash
mkdir -p assets/portfolio/jianghu assets/portfolio/aceprep
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/arena/stone-courtyard.webp assets/portfolio/jianghu/stone-courtyard.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/map/jianghu-route-atlas.webp assets/portfolio/jianghu/jianghu-route-atlas.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/map/jianghu-road-backdrop.webp assets/portfolio/jianghu/jianghu-road-backdrop.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/map/jianghu-handscroll-route.webp assets/portfolio/jianghu/jianghu-handscroll-route.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/river-gate.webp assets/portfolio/jianghu/river-gate.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/old-shrine.webp assets/portfolio/jianghu/old-shrine.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/iron-pagoda.webp assets/portfolio/jianghu/iron-pagoda.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/rain-teahouse.webp assets/portfolio/jianghu/rain-teahouse.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/mirror-terrace.webp assets/portfolio/jianghu/mirror-terrace.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/levels-webp/bell-approach.webp assets/portfolio/jianghu/bell-approach.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/enemies-webp/white-serpent-witch.webp assets/portfolio/jianghu/white-serpent-witch.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/enemies-webp/black-eagle-captain.webp assets/portfolio/jianghu/black-eagle-captain.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/enemies-webp/snow-daoist.webp assets/portfolio/jianghu/snow-daoist.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/enemies-webp/crimson-lute-assassin.webp assets/portfolio/jianghu/crimson-lute-assassin.webp
cp /home/vincent/GitRepo/jianghu-ascendant/public/images/ui/resources/qi.png assets/portfolio/jianghu/qi.png
cp /home/vincent/GitRepo/acepreplabs/AcePrepLabsLandingPage/public/owl-mascot.png assets/portfolio/aceprep/owl-mascot.png
cp "/home/vincent/GitRepo/acepreplabs/AcePrepLabsLandingPage/public/high school girl.jpg" assets/portfolio/aceprep/high-school-girl.jpg
cp /home/vincent/GitRepo/acepreplabs/AcePrepLabSATOfficialScrapper/search_results.png assets/portfolio/aceprep/search-results.png
cp /home/vincent/GitRepo/acepreplabs/AcePrepLabSATOfficialScrapper/before_search_click.png assets/portfolio/aceprep/before-search-click.png
```

## What To Remove Or Suppress From The Current Page

Remove or heavily suppress:

- The current GitHub-first positioning in the hero.
- The hero stat cards: `2 game worlds`, `AI products`, `11 departments`.
- Framework and language tag clouds in major sections.
- The CSS-only fake Jianghu battlefield, combatant circles, grid, and status panel.
- The dense intro grid that explains range before showing the work.
- Repeated project cards competing with the flagship sections.
- Language labels such as `JavaScript`, `PowerShell`, `HTML/Python`, `Python`, and `C` in the main visual flow.
- Long technical descriptions of AcePrepLabs internals.
- Dashboard-like panels for LocalTelemetry and Game Studio Harness.
- The separate `Build pattern` section if it repeats the Harness message.
- Any copy that makes the site feel like a repo directory instead of a curated portfolio.

Keep but reframe:

- GitHub links as proof and inspection paths, not the main pitch.
- Older projects as a compact archive strip.
- Technical details only where they serve credibility after the emotional product story is clear.
- Private-repo links should not be exposed as primary CTAs for external visitors; route those to the public GitHub profile or an on-page section instead of letting nontechnical visitors hit 404s.

## Implementation Instructions For Gemini CLI

Gemini should modify only these implementation files and copied assets:

- `index.html`
- `style.css`
- `assets/portfolio/jianghu/*`
- `assets/portfolio/aceprep/*`

Required steps:

1. Copy the assets listed in the asset mapping section.
2. Replace the current page structure in `index.html` with the one-page IA above.
3. Keep the site static: no build system, no dependency install, no JavaScript requirement unless absolutely necessary.
4. Update the page metadata:
   - Title direction: `Vincent Lin | Playable Worlds, AI Learning, Production Systems`
   - Description direction: `Vincent Lin builds cinematic game prototypes, accessible AI learning products, and operating systems for AI-assisted production.`
5. Rebuild the header with minimal navigation and a single strong CTA to Jianghu.
6. Replace the current hero with a full-bleed cinematic visual using copied Jianghu assets.
7. Replace the current Jianghu CSS illustration with real images from `assets/portfolio/jianghu/`.
8. Rebuild Sanctuary as a cinematic image-led section using existing Sanctuary images.
9. Rebuild AcePrepLabs as a warm learning-product section using copied AcePrep assets.
10. Rebuild Harness as a premium conceptual section with three simple pillars: `Coordinate`, `Verify`, `Remember`.
11. Compress older projects into the archive proof strip.
12. Keep all copy understandable to a nontechnical visitor.
13. Preserve working external links currently present when they remain relevant:
    - `https://jianghu-ascendant.pages.dev`
    - `https://github.com/adroitous`
    - current source links that are still used in final CTAs or archive items.
14. Make the CSS responsive for desktop, tablet, and mobile.
15. Avoid a one-note palette. Use black/deep charcoal as the base, warm white text, pale gold accents, restrained red, and one cool atmospheric accent.
16. Avoid generic dashboard cards. Use cinematic bands, editorial image compositions, full-width sections, and restrained proof chips.
17. Do not add visible instructional text explaining the site's design, features, or layout.
18. After editing, verify by opening the static `index.html` in a browser or serving the folder with a simple local static server.

Recommended CSS direction:

- Use CSS custom properties for color, spacing, and typography.
- Use a premium dark base: near-black, warm off-white, muted gold, lacquer red, and one cool steel/cyan accent.
- Prefer large full-width sections over many small cards.
- Use image overlays, subtle grain, thin rules, and precise spacing.
- Keep cards at `8px` radius or less.
- Ensure mobile text never overlaps images or buttons.
- Respect `prefers-reduced-motion`.

## Acceptance Criteria

Content acceptance:

- The page can be understood by a nontechnical visitor in under 30 seconds.
- The primary message is visibly aligned with: playable worlds, AI learning products, and operating systems for ambitious work.
- Jianghu Ascendant is the dominant project and includes a working `Play` CTA to `https://jianghu-ascendant.pages.dev`.
- Project Sanctuary/cardlyB is the second major game section and uses the existing Sanctuary images.
- AcePrepLabs reads as an accessible learning product, not a stack dump.
- Harness Ecosystem reads as a behind-the-scenes production operating system, not a technical dashboard.
- Older projects are compressed into a small archive/proof strip.
- GitHub is available as proof, but it is not the main hero message.

Visual acceptance:

- The page feels cinematic, premium, futuristic, and clear.
- Real project images are used for Jianghu, Sanctuary, and AcePrep.
- The layout has fewer, larger moments instead of many equal-weight panels.
- The Jianghu section no longer uses CSS-only fake game art.
- No section is dominated by framework tags or language badges.
- The design is responsive across desktop and mobile.
- Text remains readable over images with sufficient contrast.
- Buttons and links have visible focus states.

Technical acceptance:

- `index.html` and `style.css` remain static and dependency-free.
- All new image paths resolve locally under `assets/portfolio/`.
- No missing images appear in the browser console or network panel.
- No horizontal scrolling occurs on mobile widths.
- The page passes a basic manual link check for the main CTAs.
- The final implementation does not introduce build artifacts, package files, or unrelated repo changes.

