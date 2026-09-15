# Project 5: Naija Beats web player

**Level:** Advanced (capstone)  
**Focus:** Flexbox, Grid and positioning together

A music streaming web player on an artist page. Use everything from the first four projects.

## What you will practise

- A 2-column page grid with a sticky sidebar
- A banner with a background image, gradient overlay and text layered with `absolute`
- A play button that overlaps the banner edge (negative `bottom`)
- A two-column grid with a sticky side card
- Track rows built with `grid-template-columns` (6 columns)
- An album grid using `repeat(auto-fill, minmax(160px, 1fr))`
- A hover-reveal play button on album covers
- A `fixed` player bar laid out as a 3-column grid, with a progress bar and knob made from positioned `div`s
- Turning the sidebar into a fixed bottom tab bar on mobile

## What's in this folder

| Path | What it is |
|---|---|
| `design/desktop-full-page.png` | Whole page at 1440px (player bar hidden) |
| `design/desktop-first-screen.png` | What you see on load, with the player bar |
| `design/mobile-full-page.png` | Whole page at 390px (bars hidden) |
| `design/mobile-first-screen.png` | First screen on mobile, with tab bar and player |
| `assets/images/` | artist-banner.jpg, cover-danfo-drive.jpg, cover-garden-city-soul.jpg, cover-lagoon-nights.jpg, cover-owambe-season.jpg, cover-palm-wine-tapes.jpg, cover-slow-harmattan.jpg, cover-sunrise-riddims.jpg, cover-third-mainland.jpg |
| `assets/icons/` | heart.svg, home.svg, library.svg, next.svg, pause.svg, play.svg, prev.svg, search.svg, shuffle.svg, volume.svg (SVG) |
| `assets/logo.svg` | Logo |
| `starter/index.html` | Finished HTML with all content. You shouldn't need to change it much. |
| `starter/style.css` | Colours, fonts and a reset. Write your layout here. |

## Your tasks

Work through these in order.

1. Build the page grid: 260px sidebar and main area, 8px gap and padding.
2. Make the sidebar sticky and tall enough to stop just above the player bar.
3. Build the banner: image, gradient fading into the indigo, text bottom-left, play and follow buttons overlapping the bottom edge.
4. Build the Popular list and the sticky Now playing card beside it.
5. Build the New releases album grid. The first album shows its play button; the rest show it on hover.
6. Build the fixed player bar. Add bottom padding to the body so it never covers content.
7. Below 1000px hide the Now playing card.
8. Below 700px: the sidebar becomes a bottom tab bar, the player sits just above it and shows only the track and pause button, track rows show cover, title and duration only, and albums go 2 per row.

## Design specs

**Colours**

| Name | Hex | Used for |
|---|---|---|
| Indigo | `#1B1464` | Panels |
| Deep indigo | `#120D45` | Page background, player bar |
| Soft indigo | `#2A2380` | Now playing card |
| Mango | `#FF9F1C` | Play buttons, active track, progress |
| Lime | `#C4E538` | Verified and now-playing tags |
| Text | `#F4F2FF` | Main text |
| Muted | `#A9A4D6` | Secondary text |

**Font:** Sora (400, 500, 600, 700, 800). Get it from https://fonts.google.com/specimen/Sora (already linked in the starter HTML).

**Measurements**

- Panel radius: 14px
- Banner height: 340px (280px on mobile); name: `clamp(3rem, 7vw, 5.5rem)`, weight 800, letter-spacing −0.04em
- Big play button: 60px circle
- Player bar height: 88px desktop, 72px mobile; tab bar: 60px
- Progress bar: 4px tall; knob: 12px circle at 37%

**Breakpoints:** check your page at 1440px, 1024px, 768px and 390px wide. Your page should never scroll sideways.

## Stretch goals

- Make the play/pause button toggle its icon.
- Let the progress knob be dragged.
- Add a mobile full-screen now playing view that slides up from the player.

## Tips

- Open the design image next to your browser and compare often.
- Use your browser's DevTools: the Grid and Flexbox overlays show you exactly what is happening.
- Pixel-perfect is not the goal. Matching the layout and the way it responds is.
