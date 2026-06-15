# AGENTS.md

## Project Overview

This repository contains a personal portfolio website for Carole Schäfer, presented in the role of a Product Marketing Manager. The site is intended for recruiters, hiring managers, and companies evaluating Carole for job opportunities.

The website should communicate professional capability, strategic thinking, cross-functional collaboration, and clear business impact. It should feel modern, polished, credible, and personable without sounding exaggerated or generic.

## Audience

Primary audience:

- Recruiters screening for fit and experience.
- Hiring managers evaluating product marketing skills.
- Companies looking for a capable, thoughtful, and collaborative colleague.

Write and design for people who need to quickly understand:

- What Carole does well.
- What kind of value she brings to a team.
- How she thinks about product marketing, positioning, go-to-market work, storytelling, and collaboration.
- How to contact her or continue the conversation.

## Content Direction

Use confident, specific, and warm professional language. Present Carole as capable, skilled, thoughtful, and easy to work with.

Prefer:

- Clear value statements over buzzwords.
- Concrete examples, outcomes, and strengths over vague claims.
- A human, collegial tone over corporate boilerplate.
- Concise sections that are easy to scan.

Avoid:

- Overstated or inflated language.
- Generic portfolio filler.
- Excessive jargon.
- Long paragraphs that slow down recruiter review.
- Claiming specific achievements, metrics, employers, or credentials unless provided by Carole or already present in source material.

Good positioning themes:

- Product positioning and messaging.
- Go-to-market strategy.
- Customer and market understanding.
- Cross-functional collaboration with product, sales, leadership, and customer-facing teams.
- Storytelling that connects product value to customer needs.
- Structured thinking, ownership, and practical execution.

## Wording and Information Architecture

Current editorial direction:

- Keep headings short, personal, and useful for recruiters who scan quickly.
- Work headings from the value proposition: what Carole brings, what she makes easier for teams, and why her profile is relevant.
- Prefer human, specific headlines that sound like a real professional wrote them, for example "Erst verstehen, dann zuspitzen", "Komplexe Angebote so erzählen, dass Teams damit arbeiten können", or "Wo Produktmarketing, Website und Strategie zusammenkommen".
- Avoid generic label-like headlines such as "Was ich einbringe", "Wie ich arbeite", "Wofür ich stehe", and "Erfahrung, die Orientierung schafft" unless the surrounding content makes them clearly distinctive.
- Avoid long explanatory headlines that repeat the paragraph below them.
- Avoid redundant page structures. If two pages cover strongly overlapping proof points, combine them into one clearer page.
- Treat "Werdegang" as the primary place for professional stations, concrete work areas, education, and continuing education.
- Do not split "Arbeitsfelder" and "Erfahrung" into separate pages unless there is enough distinct source material to justify both.

## Design Direction

The portfolio should have a modern, refined visual style suitable for a Product Marketing Manager. It should feel professional and contemporary, not flashy or overly decorative.

Design priorities:

- Strong first impression above the fold.
- Clear hierarchy and fast scanning.
- Elegant typography.
- Responsive layout for mobile, tablet, and desktop.
- Accessible contrast and readable font sizes.
- Thoughtful use of spacing, visual rhythm, and sectioning.
- A visible call to action for contact or profile links.

Subpage spacing guidance:

- Keep the start page generous enough to create a strong first impression.
- Keep all other pages more compact vertically so they do not feel empty or unfinished.
- Use whitespace to create hierarchy, not large gaps between small amounts of content.

Avoid:

- Generic template aesthetics.
- Dense blocks of text.
- Overly playful visuals that weaken professional credibility.
- Heavy animations that distract from the content.
- Design choices that depend on server-side rendering or backend services.

## Technology Constraints

The site will be hosted on GitHub Pages. Choose technology that works well with static hosting.

Compatible options include:

- Plain HTML, CSS, and JavaScript.
- Static site generators that output static files.
- Frontend frameworks only if they can be built into static assets and deployed from GitHub Pages.

Do not require:

- A custom backend server.
- Runtime server-side rendering.
- Databases.
- Private environment variables at runtime.
- Platform-specific hosting features unavailable on GitHub Pages.

If using a build step, keep it simple and document how to run it locally. The final output must be deployable by GitHub Pages after pushing a commit.

## Implementation Guidelines

- Keep the site lightweight and fast.
- Favor semantic HTML and accessible components.
- Ensure the site works without authentication.
- Use relative paths or repository-aware asset paths suitable for GitHub Pages.
- Keep dependencies minimal and justified.
- Test the production/static build path before considering work complete.
- Make content easy to update as Carole provides more biography, work examples, testimonials, links, or case studies.

## Suggested Site Structure

The exact structure may evolve, but a strong first version should include:

- Hero section with Carole's name, role, positioning statement, and primary call to action.
- About section with a concise professional summary.
- Strengths or expertise section focused on product marketing capabilities.
- Selected work, impact areas, or case-study-ready placeholders.
- Experience or background section when source details are available.
- Contact section with clear next steps.

## Writing Style

Use polished, human, direct copy. The tone should be professional and warm.

Example direction:

- "I help teams turn complex products into clear stories customers understand."
- "I connect market insight, product strategy, and commercial storytelling."
- "My work sits at the intersection of customer understanding, positioning, and go-to-market execution."

Do not invent detailed facts. When information is missing, use tasteful placeholders or ask for source material.

## Definition of Done

Before completing significant website changes:

- The page renders correctly on desktop and mobile.
- Navigation and contact links work.
- Copy is proofread and aligned with the target audience.
- The implementation is compatible with GitHub Pages.
- Static assets load correctly with the intended deployment path.
- Any build or preview commands are documented if a framework or generator is introduced.

# Context about my technical skills
- I am not a programmer and not familiar with web development and/or git.
- If you have implemented a change that I requested, please always offer it to me to push them to git, so I can see the changes in action. Please make sure to perform local validation first before committing untested changes
- If you present me with multiple options please make sure to explain them in not too technical language to enable me to actually participate in the design in a meaningful way.
- The repository on github is public. Please stop me before we publish sensitive information (api keys etc) onto github!
