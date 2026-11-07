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

> Martinez, S. (2026). *Build securely. Grow strategically: GitHub profile strategy workshop* (Version 1.0.1) [Workshop materials]. Zenodo. https://doi.org/10.5281/zenodo.24025600

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

## 7. Add your own work to ORCID

An ORCID record connects a researcher to their work. Adding an ORCID to `CITATION.cff` does not itself add the repository to that researcher's record. ORCID provides a separate BibTeX import workflow. (ORCID, n.d.)

For this repository, Santos Martinez's author identifier is [0009-0001-5997-303X](https://orcid.org/0009-0001-5997-303X), matching the USF source's citation metadata.

If you plan to archive the work with Zenodo, complete that process first, update the citation with the issued DOI and then import the final record. Do not create a second ORCID entry for the same work merely to add its DOI.

If you are adding your own authored work to your ORCID record:

1. Sign in to [your ORCID record](https://orcid.org/my-orcid) and check Works for an existing entry before importing.
2. Download the work's BibTeX file. This repository provides [CITATION.bib](../CITATION.bib) for its author's record.
3. In Works, select **+Add**, then **Add BibTeX** and choose the downloaded `.bib` file.
4. Review the imported title, author, year, repository URL and work type. This record describes workshop materials, not a journal article.
5. Complete the import, choose the intended visibility and confirm that the work appears once in your record.

The repository was first released November 6, 2026. Version 1.0.1 was published November 6 in fixed EST, corresponding to November 7 in UTC; its Zenodo record uses November 7, 2026 as the publication date. November 14, 2026 is the planned workshop date, not its publication date. Use the verified version DOI `10.5281/zenodo.24025600`. Preserve Victoria Entz's co-presenter credit without changing the established repository authorship.

Participants should cite the original workshop in their projects, not list it as their own authored work. Add a separate ORCID work only for an original contribution whose authorship you can support.

## 8. Archive a release with Zenodo

**Current status:** Version 1.0.1 is published on GitHub and archived in [Zenodo record 24025600](https://zenodo.org/records/24025600). Its DOI `10.5281/zenodo.24025600` resolves to that record. The archived version, author ORCID, MIT license and source repository link have been verified.

The release DOI is `10.5281/zenodo.24025600`. Zenodo also supplies the all-versions concept DOI `10.5281/zenodo.24025599`; use the release DOI when citing the specific version demonstrated in this workshop.

Zenodo supports `CITATION.cff` metadata for GitHub releases. This repository uses that file as its author and release metadata source. A separate `.zenodo.json` is unnecessary here and would take precedence over `CITATION.cff` if both were present. (Zenodo, n.d.-a)

The repository owner completes the setup:

1. Sign in to [Zenodo](https://zenodo.org) and connect the `hanshisantos` GitHub account. Link the author's ORCID account if desired.
2. Open [Zenodo's GitHub integration](https://zenodo.org/account/settings/github/), select **Sync now** and enable `hanshisantos/github-profile-strategy-workshop`. (Zenodo, n.d.-b)
3. Prepare a new release containing the current citation metadata. Keep `CITATION.cff`, `CITATION.bib` and the visible citation aligned with that release's actual version and date. Do not move the existing `v1.0.0` tag to newer content.
4. Publish the new GitHub release after enablement, then wait for Zenodo to process it. Inspect any reported errors rather than assuming the archive succeeded. (Zenodo, n.d.-c)
5. Open the resulting Zenodo record. Review the title, Santos's author ORCID, license, version and description. Victoria remains credited as workshop co-presenter.
6. Copy the DOI issued for that specific archived release. Add it to the root and preferred citation metadata, the BibTeX file and the visible reference. Do not invent a DOI or display an unverified DOI badge.
7. Add the finalized work to ORCID, or update the existing entry with the DOI rather than importing a duplicate.

The repository URL identifies the live project. A release DOI should identify the particular archived version being cited. Check which version the record describes before using its identifier.

## References

GitHub. (n.d.-a). *About CITATION files*. Retrieved November 6, 2026, from https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files

GitHub. (n.d.-b). *Referencing and citing content*. Retrieved November 6, 2026, from https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content

Martinez, S. (2026). *USF AI Workshop: Build your first AI browser extension* (Version 1.0.0) [Computer software]. GitHub. https://github.com/hanshisantos/USF-AI-Workshop

ORCID. (n.d.). *Importing works from a BibTeX file*. Retrieved November 6, 2026, from https://support.orcid.org/hc/en-us/articles/360006894794-Importing-works-from-a-BibTeX-file

Zenodo. (n.d.-a). *CITATION.cff file*. Retrieved November 6, 2026, from https://help.zenodo.org/docs/github/describe-software/citation-file/

Zenodo. (n.d.-b). *Enable a repository*. Retrieved November 6, 2026, from https://help.zenodo.org/docs/github/enable-repository/

Zenodo. (n.d.-c). *Archive a release from GitHub*. Retrieved November 6, 2026, from https://help.zenodo.org/docs/github/archive-software/github-upload/
