---
name: Dorna Pourang
description: One-page personal site for a senior clinical trial operations and strategy leader, laid out as a calm, scannable dossier.
colors:
  paper: "#f7f8f9"
  paper-deep: "#eef0f2"
  ink: "#15202b"
  ink-soft: "#46525f"
  ink-faint: "#59646f"
  rule: "#d9dde2"
  accent: "#1d5566"
  accent-deep: "#133e4b"
  on-ink: "#ffffff"
  on-ink-soft: "#d5dbe0"
  on-ink-faint: "#aeb7c0"
typography:
  display:
    fontFamily: "Source Serif 4, Georgia, Times New Roman, serif"
    fontSize: "clamp(2.5rem, 5vw, 4rem)"
    fontWeight: 500
    lineHeight: 1.04
    letterSpacing: "-0.025em"
    fontVariation: "\"opsz\" 60"
  headline:
    fontFamily: "Source Serif 4, Georgia, Times New Roman, serif"
    fontSize: "clamp(1.875rem, 3vw, 2.5rem)"
    fontWeight: 500
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  statement:
    fontFamily: "Source Serif 4, Georgia, Times New Roman, serif"
    fontSize: "clamp(1.375rem, 3.4vw, 2.5rem)"
    fontWeight: 500
    letterSpacing: "-0.015em"
  wordmark:
    fontFamily: "Source Serif 4, Georgia, Times New Roman, serif"
    fontSize: "1.25rem"
    fontWeight: 600
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Source Serif 4, Georgia, Times New Roman, serif"
    fontSize: "1.1875rem"
    fontWeight: 500
    lineHeight: 1.4
  title-sm:
    fontFamily: "Source Serif 4, Georgia, Times New Roman, serif"
    fontSize: "1.125rem"
    fontWeight: 500
  citation:
    fontFamily: "Source Serif 4, Georgia, Times New Roman, serif"
    fontSize: "0.9375rem"
    fontWeight: 400
  lead:
    fontFamily: "Hanken Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(1.0625rem, 1.5vw, 1.25rem)"
    fontWeight: 500
    lineHeight: 1.45
  body:
    fontFamily: "Hanken Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
    fontFeature: "\"kern\", \"liga\""
  body-sm:
    fontFamily: "Hanken Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.55
  nav:
    fontFamily: "Hanken Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 500
  label:
    fontFamily: "Hanken Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 600
    fontFeature: "\"tnum\", \"lnum\""
  button:
    fontFamily: "Hanken Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "1rem"
    fontWeight: 600
rounded:
  none: "0"
  focus: "2px"
  sm: "4px"
  pill: "999px"
spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "32px"
  xl: "48px"
  gutter: "clamp(20px, 5vw, 48px)"
  section: "clamp(64px, 10vw, 112px)"
  band: "clamp(72px, 10vw, 120px)"
  wrap: "1180px"
  header: "64px"
components:
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "48px"
  button-primary-hover:
    backgroundColor: "{colors.accent-deep}"
    textColor: "{colors.on-ink}"
  text-link:
    textColor: "{colors.accent}"
    typography: "{typography.button}"
  text-link-hover:
    textColor: "{colors.accent-deep}"
  nav-link:
    textColor: "{colors.ink-soft}"
    typography: "{typography.nav}"
    padding: "6px 0"
  nav-link-active:
    textColor: "{colors.ink}"
  nav-cta:
    textColor: "{colors.accent}"
    typography: "{typography.nav}"
    rounded: "{rounded.pill}"
    padding: "6px 16px"
  nav-cta-hover:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.on-ink}"
  header:
    backgroundColor: "{colors.paper}"
    height: "{spacing.header}"
  dossier-entry:
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    padding: "22px 0 24px"
  org-strip:
    backgroundColor: "{colors.paper-deep}"
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
    padding: "22px 0 24px"
  feature-image:
    backgroundColor: "{colors.paper-deep}"
    rounded: "{rounded.none}"
  contact-band:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-ink}"
    typography: "{typography.statement}"
    padding: "{spacing.band} 0"
  footer:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-ink-faint}"
    typography: "{typography.label}"
---

# Design System: Dorna Pourang

## Overview

**Creative North Star: "The Executive Dossier"**

The site reads like a well-kept dossier on a senior operator: a cool near-white sheet, deep navy-charcoal ink, and a single petrol accent that only ever means "act here" or "go there". The first viewport is the cover page (name, role, bio, portrait, one email action); everything below it is the record, filed as ruled lists with a narrow tabular column for year or outlet and a wide column for the title. Nothing is decorated for its own sake. Credibility comes from order, generous measure, and the weight of the record itself.

Two typefaces carry the whole system. Source Serif 4 names things: the person, the section titles, every publication, article, organization and feature title, and the email address at the close. Hanken Grotesk does everything else: describing, labelling, navigating. Density is calm and editorial rather than compact; sections breathe with 64 to 112px of space above them, and list rows are separated by hairlines rather than boxes.

The page refuses the biotech-corporate template (stock lab imagery, molecule graphics, metric tiles) and the psychedelic-wellness template (gradients, saturated or trippy color). It also does not echo the previous Squarespace look (all caps, condensed display type, stark black and white). The only inversion is the closing contact band and footer, set on solid ink.

**Key Characteristics:**
- Cool paper ground, navy-charcoal ink, one deep petrol accent.
- Serif for names and titles, grotesk for description and labels; no uppercase styling anywhere.
- Ruled dossier lists: heading column left, record column right, tabular meta column inside each row.
- Flat surfaces, hairline rules, square-cornered photography, pill-shaped actions.
- One dark band at the end of the page for the email address.
- Motion is quiet: a single hero entrance, a scroll-aware header, small hover lifts.

## Colors

A restrained cool-neutral palette with one deep, desaturated petrol accent; every neutral leans slightly blue so paper and ink feel like one family.

### Primary
- **Deep Petrol** (accent): links, the filled "Email me" button, the outlined Contact pill in the header, the role line under the name, the focus ring, and text selection. It is the only chromatic color on the page.
- **Midnight Petrol** (accent-deep): the hover and pressed state of petrol links and the primary button. Never used at rest.

### Neutral
- **Cool Paper** (paper): the page ground, the header backdrop once scrolled, and the browser theme color.
- **Shaded Paper** (paper-deep): the previous-organizations strip and the placeholder fill behind photographs while they load.
- **Navy Ink** (ink): headings, entry titles, primary body copy, the heavy top rule of every dossier list, and the full-bleed ground of the contact band and footer.
- **Slate** (ink-soft): secondary bio paragraphs, author lists, venue citations, and resting nav links.
- **Pewter** (ink-faint): the tabular meta column (years, outlets), feature source labels, and the "Previous organizations" strip label. Holds 5.3:1 or better on both paper grounds.
- **Hairline** (rule): the 1px dividers between list rows and around the organizations strip, and the scrolled header's bottom border.
- **On-Ink White** (on-ink): all text on the dark band, the primary button label, and the reversed focus ring and selection on ink.
- **Mist** (on-ink-soft): footer links at rest.
- **Fog** (on-ink-faint): footer body text.

### Named Rules
**The One Petrol Rule.** Petrol is reserved for things a visitor can act on (links, the button, the Contact pill, focus) plus the single role line under the name. No petrol backgrounds, panels, icons or decorative strokes. If it is petrol and it is not clickable, it had better be the role line.

**The Single Inversion Rule.** Ink becomes a ground exactly once, at the bottom of the page, for the contact band and footer. Everything above it sits on paper.

## Typography

**Display Font:** Source Serif 4 (with Georgia, Times New Roman, serif), self-hosted variable, weights 200 to 900, roman and italic.
**Body Font:** Hanken Grotesk (with system-ui, -apple-system, Segoe UI, sans-serif), self-hosted variable, weights 100 to 900.

**Character:** A literate, slightly warm text serif set at medium weight with tight negative tracking at size, paired with a clean contemporary grotesk that stays out of the way. The serif makes the record feel authored and published; the grotesk keeps the page current and readable.

### Hierarchy
- **Display** (500, clamp(2.5rem, 5vw, 4rem), 1.04, optical size 60, balanced wrapping): the greeting and name in the hero. Used once.
- **Headline** (500, clamp(1.875rem, 3vw, 2.5rem), 1.1): section titles (Publications, Features, Writing, Press, Education, Contact me).
- **Statement** (500, clamp(1.375rem, 3.4vw, 2.5rem)): the email address in the contact band, underlined with a 35% white line that turns solid on hover.
- **Wordmark** (600, 1.25rem): the name in the header.
- **Title** (500, 1.1875rem, 1.4, max 62ch): publication titles, article and press link titles, feature captions (max 48ch), education entries.
- **Title Small** (500, 1.125rem; 1.0625rem on phones): organization names in the strip.
- **Citation** (serif italic, 0.9375rem): the venue line under each publication.
- **Lead** (grotesk 500, clamp(1.0625rem, 1.5vw, 1.25rem), 1.45, petrol): the two-part role line under the name, one phrase per line.
- **Body** (grotesk 400, 1.0625rem, 1.6; 1rem under 720px): bio copy, max 66ch. The first bio paragraph is set slightly larger (1.09375rem, 1.58) in full ink; the second drops to Slate.
- **Body Small** (grotesk 400, 0.9375rem, 1.55, max 72ch): author lists, with Dorna's own name in ink at weight 650.
- **Nav** (grotesk 500, 0.9375rem): header links.
- **Label** (grotesk 600, 0.875rem, tabular lining numerals): the meta column, feature sources, footer.

### Named Rules
**The Two Voices Rule.** Serif names things; grotesk describes and labels them. A title, a name, an organization or an address is serif. Dates, outlets, authors, navigation and buttons are grotesk.

**The Sentence Case Rule.** No uppercase transforms, no letterspaced caps, no condensed display type. Labels are distinguished by weight and color, not case.

## Layout

A single centered column with a 1180px maximum width and a fluid side gutter of clamp(20px, 5vw, 48px). Sections are separated by large vertical space, clamp(64px, 10vw, 112px), rather than by backgrounds or borders.

- **Header:** sticky, 64px tall (56px under 720px). Wordmark left, section links right, with a pill-outlined Contact link last.
- **Hero:** a two-column grid at 1.8fr to 1fr with a gap of clamp(32px, 6vw, 88px). Copy on the left (max 46rem), a 4:5 portrait on the right, top-aligned. Under 960px the portrait column narrows to 0.8fr; under 720px the grid stacks and the portrait moves above the name, capped at 180px wide.
- **Organizations strip:** a full-bleed band on Shaded Paper with hairlines top and bottom, a small label above a wrapping row of serif names (gap 8px by 26px).
- **Dossier sections:** a two-column grid at 1fr to 2.6fr. The section title sits in the left column and stays sticky 24px below the header while its list scrolls. Each list row is its own grid: an 11.5rem meta column and a flexible title column, 32px apart. Under 960px the title moves above the list; under 720px each row collapses to a single column with the meta line above the title.
- **Features:** a two-up grid of 3:2 photographs with a 48px row gap and clamp(24px, 3.5vw, 48px) column gap; one column under 720px.
- **Contact band:** full-bleed ink with clamp(72px, 10vw, 120px) of vertical padding; the title and the email address share a baseline, pushed to opposite ends, and stack under 720px.

**Responsive navigation:** under 960px the header wraps. The wordmark keeps the first line with the Contact pill pinned to its right; the remaining links drop to a full-bleed second row that scrolls horizontally with no visible scrollbar.

**Spacing rhythm:** 8, 16, 24, 32 and 48px steps cover nearly every gap; list rows use 22px over 24px of padding.

### Named Rules
**The Dossier Rule.** Records are filed, not carded. Every list opens with a 1px ink rule, separates rows with 1px Hairline rules, and keeps a narrow left meta column in Label type. A new record type (talks, roles, patents) gets the same treatment.

## Elevation & Depth

The system is flat. Depth comes from tonal shifts between Cool Paper, Shaded Paper and Navy Ink, and from hairline rules. Shadows exist in exactly two places, both tied to action: the primary button carries a soft petrol-tinted shadow at rest that deepens on hover, and feature photographs gain a long, low shadow only while hovered. The header gets a translucent paper backdrop with a 10px blur and a hairline only after the page scrolls past 8px.

### Shadow Vocabulary
- **Action rest** (`box-shadow: 0 1px 2px rgba(19, 62, 75, 0.18), 0 6px 18px -6px rgba(19, 62, 75, 0.35)`): the primary button at rest.
- **Action lift** (`box-shadow: 0 2px 4px rgba(19, 62, 75, 0.2), 0 10px 24px -8px rgba(19, 62, 75, 0.45)`): the primary button on hover, paired with a 1px rise.
- **Photo lift** (`box-shadow: 0 18px 40px -22px rgba(21, 32, 43, 0.45)`): a feature photograph on hover, paired with a 3px rise.

### Named Rules
**The Flat Paper Rule.** Nothing on paper casts a shadow at rest except the one filled button. Lists, strips, photographs and headings stay flat; lift is a response to the pointer, never a resting state.

## Shapes

Two shapes, used for two different jobs. Photography is cut square: the portrait and the feature images have no radius at all, which keeps them reading as documents in a file. Actions are fully round: the primary button and the header Contact pill use a 999px radius. Rules are 1px straight lines. The only other radii are functional: 2px on the focus ring and 4px on the skip link. The external-link mark is a thin stroked arrow (1.6 stroke, round caps) drawn at 0.8em.

### Named Rules
**The Square Image, Round Action Rule.** Pictures are square-cornered; things you press are pills. Do not round a photograph and do not square a button.

## Components

### Buttons
Confident but quiet: one filled pill per page.
- **Shape:** fully rounded pill (999px), 48px tall, 26px side padding.
- **Primary:** Deep Petrol fill, On-Ink White label in grotesk 600 at 1rem, with the Action rest shadow.
- **Hover / Focus:** fill shifts to Midnight Petrol, rises 1px, shadow deepens to Action lift over 0.2s on the house ease; pressing returns it to rest. Focus shows the 2px petrol ring at 3px offset.
- **Text link companion:** sits beside the button with a 28px gap: grotesk 600, petrol, underlined with a 1px line at 0.22em offset.

### Navigation
- **Style:** grotesk 500 at 0.9375rem in Slate, no underline, 6px vertical padding, links clamp(16px, 2.4vw, 32px) apart.
- **Hover / Active:** text darkens to Navy Ink. The link for the section in view (tracked by an intersection observer) gets a 1px underline drawn in its current color.
- **Contact pill:** the last link is outlined in petrol (1px, 999px radius, 6px by 16px padding); on hover it fills petrol with white text. It never gets the active underline.
- **Scroll state:** transparent at the top of the page; after 8px of scroll it gains a 92% paper backdrop, 140% saturation and 10px blur, and a Hairline bottom border, transitioning over 0.3s.
- **Mobile:** see Layout; the second row scrolls sideways and the Contact pill stays pinned top right.

### Dossier Entry (signature)
The core of the page. Used for publications, writing, press and education.
- **Structure:** two-column row, 11.5rem meta column in Label type and Pewter, title column in Title serif and Navy Ink.
- **Publication variant:** title, then author list in Body Small and Slate with her name in ink at 650, then the venue in serif italic.
- **Link variant (writing, press):** the whole title is the link, in ink with no underline at rest, followed by a faded external-link arrow. On hover the title turns petrol with a 45% petrol underline and the arrow nudges 2px up and right while reaching full opacity.
- **Rules:** list top is a 1px ink rule; each row closes with a 1px Hairline.

### Organizations Strip
- **Style:** full-bleed Shaded Paper band with Hairline borders top and bottom, 22px over 24px padding.
- **Content:** a small grotesk 600 label in Pewter above a wrapping row of serif organization names in ink. Names never wrap internally.

### Feature Card
The only image tiles on the page.
- **Corner Style:** square (0).
- **Background:** Shaded Paper placeholder behind a 3:2 cover-cropped photograph.
- **Shadow Strategy:** flat at rest; Photo lift and a 3px rise on hover over 0.6s.
- **Caption:** Title serif below the image with an 18px gap, max 48ch, turning petrol on hover; source label in Label type and Pewter beneath.
- **Border:** none.

### Contact Band and Footer
- **Contact band:** full-bleed Navy Ink, Headline title in white on the left, the email address in Statement serif on the right with a translucent white underline that turns solid on hover. Focus ring and selection invert to white.
- **Footer:** continues the ink ground below a 12% white hairline; Label-size text in Fog, links in Mist that turn white and underline on hover.

### Motion
One easing curve, `cubic-bezier(0.16, 1, 0.3, 1)`, an exponential ease-out, drives every transition. Link and button state changes run 0.2s; the header backdrop runs 0.3s; photo lifts run 0.6s. On load, and only when the visitor has not asked for reduced motion, the hero copy rises 14px into place over 0.9s in a 60ms stagger while the portrait settles from 102% scale over 1.1s. Content is visible from the first frame; the entrance only moves it.

## Do's and Don'ts

### Do:
- **Do** keep petrol (`accent`) for links, the single filled button, the Contact pill, focus and the role line only.
- **Do** set every name, title, organization and the email address in Source Serif 4 at weight 500, and every label, date, outlet, author list and control in Hanken Grotesk.
- **Do** file any new list of records as a Dossier Entry: 1px ink rule on top, 1px Hairline (`rule`) between rows, 11.5rem tabular meta column.
- **Do** keep photographs square-cornered with a Shaded Paper (`paper-deep`) placeholder fill and an explicit aspect ratio (4:5 portrait, 3:2 features).
- **Do** use the house ease `cubic-bezier(0.16, 1, 0.3, 1)` for every transition and wrap any entrance animation in `prefers-reduced-motion: no-preference`.
- **Do** self-host fonts and images; the page should depend on nothing a vendor can switch off.

### Don't:
- **Don't** put list entries, bio text or sections inside bordered or shadowed cards; the four feature photographs are the only tiles.
- **Don't** introduce a second accent hue, gradients, or saturated wellness colors.
- **Don't** use stock lab imagery, molecule graphics, or metric tiles.
- **Don't** use uppercase transforms, letterspaced caps, or condensed display type for labels or headings.
- **Don't** add small labels or eyebrows above section titles; the serif headline stands alone.
- **Don't** round photographs or square off the pill actions.
- **Don't** add resting shadows to anything other than the primary button.
- **Don't** use ink as a ground anywhere above the contact band.
