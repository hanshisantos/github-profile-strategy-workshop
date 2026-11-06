# USF example: turn a lab into a credible project story

## The public source

Santos Martinez's *USF AI Workshop: Build Your First AI Browser Extension* is a public educational project for the Azure Essentials track at Hackabull. Its citation file identifies version 1.0.0, released April 25, 2026. The repository includes a lab manual, starter extension and reference implementation. (Martinez, 2026)

Source snapshot reviewed for this guide: commit `bb95f42352e7b1c1df94a6aad14d7c2206c46336`.

- [README](https://github.com/hanshisantos/USF-AI-Workshop/blob/bb95f42352e7b1c1df94a6aad14d7c2206c46336/README.md)
- [Lab manual](https://github.com/hanshisantos/USF-AI-Workshop/blob/bb95f42352e7b1c1df94a6aad14d7c2206c46336/docs/LAB_MANUAL.md)
- [Architecture notes](https://github.com/hanshisantos/USF-AI-Workshop/blob/bb95f42352e7b1c1df94a6aad14d7c2206c46336/docs/ARCHITECTURE_NOTES.md)
- [Feature roadmap](https://github.com/hanshisantos/USF-AI-Workshop/blob/bb95f42352e7b1c1df94a6aad14d7c2206c46336/docs/FEATURE_ROADMAP.md)
- [Original citation file](https://github.com/hanshisantos/USF-AI-Workshop/blob/bb95f42352e7b1c1df94a6aad14d7c2206c46336/CITATION.cff)
- [MIT License](https://github.com/hanshisantos/USF-AI-Workshop/blob/bb95f42352e7b1c1df94a6aad14d7c2206c46336/LICENSE)

The original README credits William Gonzalez, Kyarra Gutierrez, Andrea Martini, David Warm and Andre Rodrigues as contributors. Victoria Entz is a co-presenter of this profile-strategy workshop, not a credited author of the source USF project.

## What changes in this workshop

The original lab asks participants to build an Azure OpenAI-powered Chromium extension. Here, the required exercise is to explain the evidence behind a project claim. Running the extension is not required.

The strategic improvement is to connect the artifact to a user problem, your contribution, one decision you can explain and a next-role skill. A technology list alone does not give the reader that context.

## Choose the claim your evidence supports

| If you did this | A defensible profile statement | Evidence to link |
| --- | --- | --- |
| Read the lab and architecture notes | "Reviewed an AI browser-extension lab and documented its trust boundaries." | Your own notes, labeled as a review |
| Completed the extension exercise | "Completed a guided AI browser-extension lab and recorded my functional checks." | Your fork, changes and actual check results |
| Changed and tested one feature | "Adapted the extension to [specific purpose] and checked [specific behavior]." | Your commit, test record and permitted screenshots |
| Proposed a backend boundary | "Designed a proposed backend proxy to avoid shipping API credentials in the browser." | Your design record, labeled proposed |
| Implemented and checked that boundary | "Implemented [specific control] and recorded [specific checks]." | Your implementation and observed results |

These statements are examples, not claims about your work. Use only the row that matches what you actually did.

## Example: a stronger project record

The following is a proposed learning exercise, not a completed implementation:

> **Direction:** I am exploring secure AI application development.
>
> **Problem:** A browser extension can help a user ask questions about a page, but its design needs clear boundaries for page content, model requests and credentials.
>
> **My planned contribution:** Adapt the USF workshop into a documented design that routes model requests through a backend rather than placing a reusable API credential in the extension.
>
> **Evidence to produce:** A data-flow diagram, a small implementation diff and checks showing that the extension package contains no model API credential. I will also record how the backend limits access and which controls remain unfinished.
>
> **Current limit:** This is a plan. I have not implemented or tested the proposed boundary.
>
> **Feedback request:** Can a reviewer explain where untrusted page content enters the design and identify a missing access or data-handling control?

After completing work, replace plans with your actual contribution and observed results. Do not remove the limitations simply to make the profile sound stronger.

## Keep the original demo separate from production

The historical lab includes Azure API-key setup. Do not copy a demonstration credential pattern into a public profile project.

For this workshop:

- Do not request, collect or publish API keys.
- Do not run the extension on private, workplace or sensitive pages.
- Do not send page content to a model without permission.
- Do not put reusable credentials in browser code or a public repository.
- If you implement a backend, document authorization, secret storage, data handling and operational limits before describing it as ready for others.
- Do not claim a system is "secure" merely because it runs or one check passed.

Use fictional or deliberately public content for any optional demonstration. Ask the resource owner before using a cloud service that can incur charges.

## Make the profile entry concise

Once supported by evidence, a project entry can use this structure:

> **[Your project title]**  
> Adapted from the USF AI Workshop by Santos Martinez. I contributed [specific change], checked [observed behavior] and documented [remaining limitation]. See [my evidence record and commit].

Add the full source citation in the project README. Pin your own fork only when you can explain what you changed. Keep the upstream credit visible.

## Reference

Martinez, S. (2026). *USF AI Workshop: Build your first AI browser extension* (Version 1.0.0) [Computer software]. GitHub. https://github.com/hanshisantos/USF-AI-Workshop

The source uses a special dash in its title. This guide renders the title with a colon to follow its plain-text house style without changing the work being referenced.
