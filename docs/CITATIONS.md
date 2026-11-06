# Cite the source and make your contribution clear

Attribution tells readers whose work you used. A citation helps them find the source. A license tells them what reuse is permitted. None of these replaces the others.

## 1. Credit the original project

When you adapt the USF exercise, add a visible note in your project README:

> Adapted from the USF AI Workshop by Santos Martinez. My contribution is [specific change]. The upstream repository credits William Gonzalez, Kyarra Gutierrez, Andrea Martini, David Warm and Andre Rodrigues as contributors.

Use your actual changes. A fork by itself is not evidence of an original implementation.

Preserve the source license and copyright notice when copying or modifying its licensed code or materials. The USF repository uses the [MIT License](https://github.com/hanshisantos/USF-AI-Workshop/blob/bb95f42352e7b1c1df94a6aad14d7c2206c46336/LICENSE). Do not relicense someone else's work merely by adding a new citation.

## 2. Add an APA 7 reference

For the USF source, use its published author, year and version:

> Martinez, S. (2026). *USF AI Workshop: Build your first AI browser extension* (Version 1.0.0) [Computer software]. GitHub. https://github.com/hanshisantos/USF-AI-Workshop

In text:

> My learning project adapts the USF browser-extension workshop (Martinez, 2026).

For this workshop:

> Martinez, S. (2026). *Build securely. Grow strategically: GitHub profile strategy workshop* (Version 1.0.0) [Workshop materials]. GitHub. https://github.com/hanshisantos/github-profile-strategy-workshop

Victoria Entz is credited as workshop co-presenter. Do not add her as a software author or cite a quotation from her unless the actual contribution or quotation is confirmed. Co-presenter credit and repository authorship are different records.

## 3. Use a source-specific link

Link the particular file, release or commit supporting the claim. For a source snapshot, include its commit SHA so a future reader can inspect what you reviewed.

For this guide's USF source:

```text
https://github.com/hanshisantos/USF-AI-Workshop/tree/bb95f42352e7b1c1df94a6aad14d7c2206c46336
```

A branch URL can change over time. Describe the version you actually used. Do not invent a version, publication date, test result or DOI.

## 4. Add your own CITATION.cff when appropriate

GitHub can expose a **Cite this repository** action when a supported `CITATION.cff` file is present on the default branch. It can generate APA and BibTeX citations from that metadata. (GitHub, n.d.-a)

Use [the starter citation file](../templates/CITATION.cff) as a field guide. Put a completed `CITATION.cff` at the root of your project only after replacing the placeholders:

- Use your project's real title and authors.
- Include only people whose authorship is established.
- Use the date and version of a release you actually made.
- Use your repository's actual license.
- Link your project as the repository URL.
- Cite upstream work separately in the README and retain its notices.

You do not need a DOI to make a repository citable. A DOI is a persistent identifier issued by a registration service, not a number to invent. If you later archive a public release through a service such as Zenodo, follow the actual archive process and use only the DOI it issues. (GitHub, n.d.-b)

## 5. Disclose AI assistance without overstating it

Use a short project note when required by your course, event or organization:

> AI assistance: [tool] helped with [specific drafting or coding task]. I reviewed [specific output], made [specific changes] and performed [actual checks]. Remaining limitations: [limits].

Do not cite an AI-generated response as evidence that an external factual claim is true. Verify the original source. Do not claim you reviewed or tested something you did not inspect.

Institutional rules take precedence over this suggested disclosure format.

## 6. Keep a small source ledger

| Claim or reused material | Original source | Your change | Verification |
| --- | --- | --- | --- |
| [Claim or file] | [Author, URL and version] | [Actual contribution] | [What you checked and date] |

Prefer a few traceable sources over a long list that does not support the work. Check each link before publishing.

## References

GitHub. (n.d.-a). *About CITATION files*. Retrieved November 6, 2026, from https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files

GitHub. (n.d.-b). *Referencing and citing content*. Retrieved November 6, 2026, from https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content

Martinez, S. (2026). *USF AI Workshop: Build your first AI browser extension* (Version 1.0.0) [Computer software]. GitHub. https://github.com/hanshisantos/USF-AI-Workshop
