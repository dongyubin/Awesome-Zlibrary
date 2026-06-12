# Ambrook — Style Reference
> harvest ledger on butcher paper

**Theme:** light

Ambrook speaks in the visual dialect of American heartland: warm parchment canvas, ink-dark type, and a single harvest-amber accent that warms every primary action. The palette is deliberately desaturated — olive greens, wheat tans, bark browns — as if the interface itself were printed on recycled butcher paper and stamped with soy ink. Headlines use a custom display face with quiet authority (weight 500, not the expected 700), and every section opens with a small uppercase eyebrow that breathes across the page on wide tracking. Photography is documentary, not aspirational — welders, ranchers, truckers, unposed and full-sun. The result is an interface that feels rooted, not glossy: trustworthy through warmth rather than through chrome.

## Colors

| Name | Value | Role |
|------|-------|------|
| Parchment | `#fcfaf1` | Page canvas and card surfaces — warm off-white replaces pure #ffffff to keep the system grounded in an agricultural, paper-like register |
| Bone | `#efe9e0` | Secondary surface for footer, soft sections, and hairline borders that need separation from the parchment canvas without harsh contrast |
| Pure White | `#ffffff` | Elevated card and product-mockup surface — used sparingly to lift specific panels (like the Ledger screenshot) above the parchment base |
| Loam | `#c7bcaf` | Subtle dividers, card edges, and low-emphasis borders between the canvas and content blocks |
| Bark | `#96897b` | Muted helper text, metadata, and supporting labels where a softer voice is needed than primary body copy |
| Saddle | `#50463c` | Secondary body text and subdued icon fills — a warm brown-gray that recedes without disappearing |
| Ink | `#211b15` | Primary text, heading strokes, and the dominant border color across the system. Warm near-black with a hint of umber keeps the interface from feeling clinical |
| Charcoal Olive | `#252a23` | Dark mode–style panels, product UI containers, and high-emphasis icon fills — used when a section needs to invert the warm page into something product-focused |
| Deep Olive | `#434f40` | Navigation borders, icon strokes, and the most-used neutral divider in the system — a moss-toned dark that reads as organic rather than industrial |
| Sage | `#7a9779` | Green accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Honey Amber | `#e8b672` | Primary action button fill — the system's singular chromatic accent for CTAs, earning attention through warmth rather than saturation |
| Wheat | `#f0c891` | Lighter amber used for heading borders, icon accents, and subtle decorative strokes where honey would be too heavy |

## Typography

### Lateral — Workhorse sans for body, nav, buttons, inputs, and secondary headings. Weight 400 for running text, 500 for buttons and emphasis. Custom letterforms give it subtle warmth a generic sans would miss — slightly humanist proportions rather than mechanical geometric.
- **Substitute:** Inter or Söhne
- **Weights:** 400, 500
- **Sizes:** 11px, 13px, 15px, 17px, 19px, 30px, 68px
- **Line height:** 1.20–1.71
- **Letter spacing:** -0.0110em for 19px and 30px; 0.0580em and 0.1070em for uppercase labels at 11px and 13px

### Lateral Narrow — Condensed variant for tighter column headings and subhead text where horizontal space is constrained but body voice is still wanted.
- **Substitute:** Inter (condensed) or Söhne Buch
- **Weights:** 400, 500
- **Sizes:** 19px, 30px, 34px
- **Line height:** 1.40, 1.50
- **Letter spacing:** -0.0090em to -0.0100em

### Lateral Display — Hero and section display face. Used at weight 500 (not the default 700) for major headlines — this restraint is signature: the type whispers authority instead of shouting. Slight serif character in the terminals gives it an editorial, almost newspaper-headline feel that matches the agricultural brand voice.
- **Substitute:** Tiempos Text or Source Serif Pro
- **Weights:** 400, 500, 700
- **Sizes:** 38px, 53px, 68px
- **Line height:** 1.00, 1.10, 1.14
- **Letter spacing:** -0.0110em at all sizes
- **OpenType features:** `"ss01" on`

### Type Scale

| Role | Size | Line Height | Letter Spacing |
|------|------|-------------|----------------|
| caption | 11px | 1.5 | 0.107px |
| eyebrow | 13px | 1.6 | 0.058px |
| body | 15px | 1.71 | — |
| body-lg | 17px | 1.6 | — |
| subheading | 19px | 1.43 | -0.21px |
| heading-sm | 30px | 1.33 | -0.33px |
| heading | 38px | 1.14 | -0.42px |
| heading-lg | 53px | 1.1 | -0.58px |
| display | 68px | 1 | -0.75px |

## Spacing & Layout

**Base unit:** 4px

**Density:** comfortable

- **Page max-width:** 1200px
- **Section gap:** 60-90px
- **Card padding:** 30-45px
- **Element gap:** 8-15px

### Border Radius

- **cards:** 7.5px
- **pills:** 9999px
- **inputs:** 3.75px
- **buttons:** 3.75px

## Components

### Primary Action Button
**Role:** Filled amber CTA for email signup, trial start, and get-started flows.

Background #e8b672, text #211b15, border-radius 3.75px, padding 15px 30px, Lateral weight 500 at 15px. No shadow. On hover, darkens to a deeper amber. Arrow character (→) after label is a signature detail — the button always points forward.

### Ghost Outline Button
**Role:** Secondary action (Sign Up, Log In) where the primary amber is too loud.

Transparent background, 1px border in #211b15, text #211b15, border-radius 3.75px, padding 9px 15px. The thin, slightly rounded rectangle is the system's quiet counterpoint to the honey-amber CTA.

### Email Capture Input
**Role:** Hero-level signup field with embedded submit button.

Container is a 1px #211b15 border with 3.75px radius. Left side: Lateral 15px placeholder "Enter your email" in #96897b. Right side: amber Primary Action Button embedded flush against the input edge. No focus ring color shift — border remains ink-dark on focus.

### Section Eyebrow Label
**Role:** Small uppercase tag above every section heading (e.g. "ACCOUNTING SOFTWARE", "WHO WE SERVE").

Lateral weight 400 at 13px, letter-spacing 0.058em, color #211b15, uppercase. Centered above the heading. Wide tracking gives it the cadence of a newspaper dateline — a quiet rhythm device across the page.

### Section Heading
**Role:** Two-line editorial headline for each content section.

Lateral Display weight 500 at 38px or 53px, line-height 1.14, letter-spacing -0.42px to -0.58px, color #211b15, centered. Weight 500 (not 700) is the signature restraint — authority through quiet, not volume.

### Trust Signal Row
**Role:** Horizontal bar of icon + label assurances below the hero CTA.

Flex row with 8px gap, Lateral 13px, color #211b15. Each item is a 14px outlined icon followed by label text ("30-day free trial", "Live onboarding", "US-based support", "4.7 Trustpilot"). Icons are thin-stroke, monochrome ink.

### Brand Logo Strip
**Role:** Horizontal scroller of customer brand marks to build social proof.

Grayscale logos in oval/rounded containers on parchment background, centered around a headline "Over 7,000 businesses rely on Ambrook". Logos render in #50463c or #211b15 on parchment. No card backgrounds, no shadows — the logos sit directly on the page.

### Industry Illustration Card
**Role:** 3-column grid of industry categories (Farming, Ranching, Construction, Trucking, Property Management, Services).

Each card is a 1px #efe9e0 divider grid cell, no card background, padding 45px 30px. Center: monochrome line-art illustration of the trade (tractor, cow, crane, truck, keys, newspaper) rendered in #211b15 stroke at ~1.5px weight. Below: industry name in Lateral weight 500 at 15px with a → arrow. Illustration style is hand-drawn line art, not filled or colorful.

### Product Showcase Panel
**Role:** Dark inverted panel previewing the actual product UI (Ledger view).

Background #252a23 (charcoal olive), border-radius 7.5px, padding 45px. Left column: section heading "Bookkeeping that makes sense." in #fcfaf1 (inverted text). Right column: product screenshot (Ledger table) with light table UI on white, slightly overlapping or flush to the right edge of the dark panel.

### Documentary Photo Collage
**Role:** Hero bottom strip — overlapping, slightly rotated documentary photographs of real workers.

Five to six photographs arranged in an overlapping row at the page break below the hero. Each photo has a thin 2-4px white or parchment border (polaroid-like), slight random rotation (-3° to +3°), no border-radius. Subjects are candid, full-sun, unposed — welding sparks, a rancher in a cowboy hat, a trucker, a mechanic. Photography is the emotional anchor of the brand.

### Footer Link
**Role:** Underlined link in the footer area.

Lateral 13px, color #50463c, 1px underline in #efe9e0, 15px row gap between links. Underline is subtle — a warm bone-colored line, not ink — keeping the footer soft and scannable.

## Do's and Don'ts

### Do
- Use #fcfaf1 parchment as the page canvas for every section — never switch to pure #ffffff for a full page.
- Set primary action buttons to #e8b672 honey amber with #211b15 text and 3.75px radius.
- Open every section with an uppercase eyebrow label at 13px Lateral with 0.058em letter-spacing before the heading.
- Use Lateral Display at weight 500 (not 700) for headlines at 38px, 53px, and 68px.
- Render industry illustrations as monochrome line art in #211b15 stroke — no fills, no color.
- Apply 3.75px border-radius to buttons, inputs, and small surfaces; 7.5px to larger cards and panels.

### Don't
- Don't use pure #ffffff as a page background — parchment #fcfaf1 is the canvas signature.
- Don't set headlines at weight 700 — the system's authority comes from 500 and restraint.
- Don't introduce blue, red, or other saturated primaries — the only chromatic accent is honey amber #e8b672.
- Don't use pill-shaped (9999px) buttons — the system is defined by subtle 3.75px rounding.
- Don't fill illustrations with color — they must remain monochrome line art in #211b15.
- Don't use stock-polished or studio photography — documentary, full-sun, candid subjects only.
- Don't add drop shadows to cards or panels — the system relies on border color and surface warmth for separation.

## Elevation

The system intentionally avoids drop shadows. Visual hierarchy is built through warm surface contrast (parchment → bone → white → charcoal olive) and hairline borders in #efe9e0 and #211b15. Elevation is communicated by color temperature shifts, not by shadow depth — a flat, paper-printed aesthetic that matches the agricultural brand voice.

## Surfaces

- **Parchment Canvas** (`#fcfaf1`) — Base page background — warm off-white as the default surface.
- **Pure White Panel** (`#ffffff`) — Elevated cards and product-mockup containers that need to lift above the canvas.
- **Bone Footer** (`#efe9e0`) — Section dividers and footer band — a step warmer than the canvas to signal section boundaries.
- **Charcoal Olive Panel** (`#252a23`) — Inverted product UI panels that flip the warm page into a dark, focused work surface.

## Imagery

Photography is documentary and full-sun: real welders with sparks flying, ranchers in cowboy hats, truckers, farmers, mechanics — candid, unposed, golden-hour warm. Images are arranged in overlapping collage strips with slight rotation, giving a polaroid-scrapbook feel. Industry illustrations are hand-drawn monochrome line art — tractors, cattle, cranes, trucks, keys, newspapers — rendered in thin #211b15 stroke with no fills. No 3D renders, no abstract gradient art, no stock-polished lifestyle photography. The visual language is rooted in real American work, not aspirational gloss.

## Layout

Centered, max-width 1200px contained layout with generous vertical breathing room. The page opens with a full-bleed parchment canvas — a centered headline stack (eyebrow → display headline → subtext → email input → trust signals) with no side navigation. Below the hero, a documentary photo collage breaks the grid with overlapping, slightly rotated images. Sections alternate between centered text-only blocks and 3-column industry cards separated by hairline dividers. A dark inverted product showcase panel interrupts the warm cream rhythm to introduce the actual product UI. Navigation is a minimal top bar with the wordmark left, center links, and Log In / Sign Up right. The overall rhythm is: quiet centered text → warm collage → centered text → grid cards → centered text → dark product panel — a paced, editorial cadence rather than a dense feature grid.

## Similar Brands

- **Farmers Business Network** — Same agricultural audience and warm earthy palette, though Ambrook leans more editorial and less data-dense.
- **Indigo Agriculture** — Shared documentary-photography approach and warm, grounded brand voice targeting American growers.
- **Patagonia** — Same documentary portraiture of real working people, unposed and full-sun, paired with restrained editorial typography.
- **Mailchimp** — Same warm cream canvas, illustrative line-art category icons, and editorial headline restraint (weight 500, not 700).
- **Square (Block)** — Similar accounting-fintech positioning with a warm, approachable palette instead of the typical blue corporate register.
