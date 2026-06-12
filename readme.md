<div align="center">

# Purrnanssh Sinha — Portfolio

### Data science, beyond dashboards.

A liquid-glass portfolio, hand-built in vanilla HTML, CSS and JavaScript.<br>
No frameworks. No build step. No dependencies. One file does all of it.

<br>

[**View Live**](https://purrnanssh.github.io/Portfolio/) · [Resume](./Purrnanssh_Gen_CV.pdf) · [LinkedIn](https://www.linkedin.com/in/purrnanssh/) · [Email](mailto:prrnnssh@gmail.com)

<br>

![HTML5](https://img.shields.io/badge/HTML5-1b1b1b?style=flat-square&logo=html5&logoColor=7AA2FF)
![CSS3](https://img.shields.io/badge/CSS3-1b1b1b?style=flat-square&logo=css3&logoColor=7AA2FF)
![JavaScript](https://img.shields.io/badge/JavaScript-1b1b1b?style=flat-square&logo=javascript&logoColor=7AA2FF)
![Vercel](https://img.shields.io/badge/Deployed_on_Vercel-1b1b1b?style=flat-square&logo=vercel&logoColor=ffffff)
![GitHub Pages](https://img.shields.io/badge/Mirror_on_Pages-1b1b1b?style=flat-square&logo=github&logoColor=ffffff)

</div>

<br>

## Overview

A single-page portfolio designed around Apple's Liquid Glass language — frosted surfaces, pointer-tracked specular highlights, layered depth, and motion that communicates quality instead of demanding attention. Every interaction is written by hand: no component library, no CSS framework, no bundler.

The page is recruiter-first. Availability status, proof metrics, and two end-to-end case studies sit above everything else; design serves the argument, not the other way around.

## Design System

| Token        | Dark                          | Light                  |
| ------------ | ----------------------------- | ---------------------- |
| Base surface | `rgb(27,27,27)`               | `#F4F4F6` porcelain    |
| Accent       | `#7AA2FF`                     | `#4A7AEE`              |
| Material     | Frosted glass, 4–7% white     | White glass, 45–70%    |
| Display type | SF Pro via system stack       | same                   |
| Utility type | SF Mono — metadata & labels   | same                   |

## Engineering Notes

- **Bottom dock navigation** with a sliding liquid-glass pill that tracks the active section — the visionOS pattern, not a pinned header
- **Pointer-tracked specular highlights** on every glass surface, so the whole page behaves like one material reacting to the cursor
- **Light / dark themes** crossfaded through the View Transitions API, preference persisted across visits
- **Motion choreography** — staggered scroll reveals, magnetic CTAs, animated metrics, dash-flow architecture diagrams — all on a single easing curve
- **`prefers-reduced-motion` respected end to end**, keyboard focus visible throughout
- **Zero network weight** beyond the page itself: system fonts, inline SVG diagrams, no trackers

## Featured Work

| Project | Summary | Links |
| ------- | ------- | ----- |
| **NHIP — National Highways Intelligence Platform** | Fuses WIM, ANPR and FASTag streams into a single vehicle record for automated overload detection across India's toll network | [Repository](https://github.com/Purrnanssh/NHIP) |
| **CodeMap** | Parses a GitHub repository and renders its architecture as interactive dependency graphs — onboarding before reading a single file | [Repository](https://github.com/Purrnanssh/codemap) · [Live demo](https://codemap-teal.vercel.app/) |

## Run Locally

```bash
git clone https://github.com/Purrnanssh/Portfolio.git
cd Portfolio
open index.html        # or serve it: python3 -m http.server
```

No install. No build. It's just a page.

## Structure

```
.
├── index.html              # markup, styles, and interactions — the whole site
├── assets/images/          # portrait and previews
├── Purrnanssh_Gen_CV.pdf   # resume
└── favicon.ico
```

<br>

<div align="center">

Designed and built from scratch · © 2026 Purrnanssh Sinha

<sub>If this repo was useful as a reference, a star is appreciated.</sub>

</div>