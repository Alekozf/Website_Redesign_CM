# Canberra Modern Website: AI-Assisted Digital Workflow Case Study

A responsive eight-page website for Canberra Modern, a volunteer organisation focused on Canberra's modernist built heritage. Built with HTML, CSS, and JavaScript and deployed through GitHub Pages. This project is documented as a practical case study in using AI to support a real digital workflow, from planning and design through to implementation, testing, and deployment.

---

## Live Site



---

## Overview

This project covers the full digital stack: information architecture, UX design in Figma, front-end implementation, responsive testing, accessibility, and GitHub deployment. AI tools including Claude and ChatGPT were used to support parts of the workflow, but they were not used to complete the project independently. Final decisions, implementation, testing, and quality checks were completed by me.

The project demonstrates:

- Practical, responsible AI use integrated into a real digital workflow
- Front-end development using HTML, CSS, and JavaScript without a framework
- UX thinking and information architecture, with structure built around user goals
- Accessibility-conscious implementation across all eight pages
- Responsive design from desktop to mobile, tested in-browser
- Clear communication and technical documentation

---

## AI-Assisted Workflow

AI tools were used at defined stages of the project. For each one, I described the problem or task, reviewed what came back, tested it against the design or in the browser, and decided whether to use it, adapt it, or discard it.

| Stage | How AI was used |
|---|---|
| **Planning** | Helped structure page hierarchy, user journeys, and content grouping before design began |
| **Content review** | Reviewed copy for tone, plain language, and readability |
| **Debugging** | Helped troubleshoot HTML, CSS, and JavaScript issues, particularly responsive layout edge cases |
| **Accessibility** | Suggested improvements to ARIA usage, form labelling, focus management, and heading structure |
| **Usability review** | Flagged potential navigation gaps and interaction issues before live testing |
| **Documentation** | Supported drafting and refining this README |

Where suggestions were wrong or did not fit the design intent, they were discarded.

---

## Example AI Workflow

One practical example was responsive layout troubleshooting. I used AI to help identify why certain card layouts were breaking at smaller screen widths. I reviewed the suggestions, tested the CSS in-browser, and adapted the final solution using Grid, Flexbox, media queries, and `clamp()` sizing. This reflects the overall approach throughout the project: define the problem clearly, assess what AI returns, test it, and stay accountable for the final implementation.

---

## My Role

AI contributed at defined points. Everything else was my responsibility:

- Project direction and all scope decisions
- Visual design covering layout, typography, colour palette, and editorial tone
- Figma prototyping for both low-fi structure planning and high-fi visual design
- Front-end implementation in HTML, CSS, and JavaScript
- Translating fixed Figma layouts into flexible responsive systems
- Responsive testing across desktop, tablet, and mobile
- Accessibility decisions and implementation
- Content decisions across page structure, labelling, and copy
- Code review and quality checking
- GitHub version control and Pages deployment

---

## Key Features

- Eight-page site: Home, Events, Event Detail, Explore, Place Detail, Stories, Get Involved, About
- Responsive layout built with CSS Grid, Flexbox, media queries, and `clamp()` sizing
- Event listing with upcoming/past toggle and category filters
- Searchable place catalogue with category filtering
- Story and archive content section
- Get Involved pathway that consolidates all participation options in one place
- Mobile navigation menu
- Client-side form feedback with accessible error and success states
- Reusable card, button, tag, hero, and CTA component system across all pages

---

## Screenshots

![Homepage screenshot](assets/images/Homepage_Screenshot%20(2).png)

---

## Skills Demonstrated

| Skill area | Detail |
|---|---|
| **AI workflow** | Integrating AI into planning, debugging, accessibility review, and documentation, with human judgement applied at every step |
| **Front-end development** | HTML, CSS, JavaScript; responsive layout systems; mobile-first approach; progressive enhancement |
| **UX and IA** | Multi-page structure designed around user goals with distinct pages for distinct tasks |
| **Accessibility** | Semantic HTML, labelled forms, skip links, focus states, alt text, ARIA attributes |
| **Communication** | Clear documentation, plain language decisions, skimmable information design |
| **Problem solving** | Figma-to-browser translation, responsive edge cases, iterating from live testing |

---

## Workplace AI Relevance

The way AI was used in this project maps directly to how it adds value in everyday workplace tasks. It is not about replacing work but about improving specific parts of the workflow while keeping human judgement and quality control in place.

Some practical parallels:

- **Documentation**: using AI to draft, structure, and refine internal documents, then reviewing and editing for accuracy and tone
- **Troubleshooting**: describing a problem clearly, evaluating candidate solutions, testing them, and applying what actually works
- **Accessibility and compliance**: surfacing potential issues before a formal review, which reduces the gap between a first draft and something audit-ready
- **Content clarity**: checking internal copy or communications for plain language and readability before distribution
- **Onboarding and process guides**: applying the same approach to help non-technical colleagues understand digital tools or workflows

The skill being demonstrated here is not just that AI was used. It is knowing when to use it, how to frame the problem well, how to evaluate what it returns, and how to stay accountable for the final result.

---

## Tech Stack

- HTML
- CSS
- JavaScript (vanilla, no framework)
- GitHub Pages for deployment
- Figma for prototyping
- Claude and ChatGPT for workflow support

---

## Accessibility and Usability

Accessibility shaped decisions throughout the build:

- Semantic HTML landmarks: `header`, `nav`, `main`, `section`, `article`, `footer`
- One `h1` per page with a logical heading order
- Skip link on every page
- Labelled forms, including visually hidden labels for compact subscribe fields
- Visible focus states for keyboard navigation
- Alt text on content images with `aria-hidden` on decorative icons
- `aria-current` on active nav items
- `aria-expanded` and `aria-controls` on the mobile menu
- `aria-live="polite"` for form validation feedback

The site has not had a full formal WCAG audit. Colour contrast across all accent combinations, focus trap behaviour, and screen reader testing would need to be completed before making a compliance claim.

---

## What I Would Improve Next

- **AI-assisted content feature**: adding an AI-powered search or content helper that surfaces places, events, and stories based on natural language input, which would be a logical extension given the amount of catalogue content on the site
- **Image optimisation**: converting large PNGs to WebP with responsive sizing for mobile
- **Formal user testing**: observing unfamiliar users completing key tasks to validate the navigation and filter decisions
- **Full accessibility audit**: automated checks, keyboard-only testing, and screen reader review
- **Real form integration**: connecting the subscribe, contact, and booking forms to an actual backend
- **Content management**: moving to a templating system or static site generator to remove the repeated HTML across pages

---

## Responsible AI Use

Generative AI tools were used to support planning, debugging, code review, copy refinement, accessibility checks, and documentation throughout this project. All suggestions were reviewed, tested, and adapted before being used. Final design, implementation, project direction, and quality checks were completed by me.
