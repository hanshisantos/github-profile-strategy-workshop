# Profile lab: from direction to evidence

Finish with a profile that answers three questions: What are you working toward? What have you actually done? Where can someone inspect it?

You need a personal GitHub account. Local work also needs Git and an editor. You can complete the browser-only path without installing anything.

## 1. Choose a direction before editing

Write one sentence in your own words:

> I am building toward [role or problem area], bringing [current strength] and developing [next skill].

Pick one project that can support part of that sentence. A documented learning exercise is acceptable. Label it as learning rather than professional experience.

## 2. Fork the workshop

Open [hanshisantos/github-profile-strategy-workshop](https://github.com/hanshisantos/github-profile-strategy-workshop), select **Fork** and choose your personal account as owner. Keep the workshop repository name so it remains distinct from your profile repository.

GitHub's [forking guide](https://docs.github.com/en/pull-requests/how-tos/work-with-forks/fork-a-repo) explains the supported browser and CLI paths. A fork keeps the upstream relationship while allowing you to work in your own space.

## 3. Clone your fork

Replace `YOUR-USERNAME` before running this command. Clone your fork, not Santos's upstream repository:

```powershell
git clone https://github.com/YOUR-USERNAME/github-profile-strategy-workshop.git
Set-Location .\github-profile-strategy-workshop
git remote -v
```

Confirm that `origin` points to your account. Create a working branch:

```powershell
git switch -c profile-workshop
```

If the directory already exists, open it and check its remote instead of cloning over it.

**Browser-only alternative:** open your fork, navigate to `templates/PROFILE-README.md` and use GitHub's file editor to draft your changes on a branch. Copy the finished Markdown into the separate profile repository in step 5. Review the preview before committing.

## 4. Draft your profile and project evidence

Edit [the profile template](../templates/PROFILE-README.md). Replace the fields with your own focus, contribution and next step. Use [the project evidence template](../templates/PROJECT-EVIDENCE.md) to prepare one project story in your fork.

Keep the profile short. Link to the longer project record rather than putting every assignment, tool or course on the profile page.

Use the [USF case study](USF-CASE-STUDY.md) to distinguish:

- What the original project provides
- What you personally reviewed or changed
- What you checked and what the evidence shows
- What remains untested or planned

If all you did was read the lab, say that. Do not use "built" or "implemented" until you have done the work.

Save the workshop draft in your own fork:

```powershell
git add templates/PROFILE-README.md templates/PROJECT-EVIDENCE.md
git diff --cached
git commit -m "Draft my profile direction and project evidence"
git push -u origin profile-workshop
```

Review that diff before committing. Ensure no personal data, secrets or restricted material is included.

## 5. Create or update your profile repository

GitHub displays a profile README when the repository is public, its name matches your username and a nonempty `README.md` exists at the root. See [Managing your profile README](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).

For an account named `YOUR-USERNAME`, the profile repository is:

```text
YOUR-USERNAME/YOUR-USERNAME
```

If it does not exist, select **New repository**, use your exact username as its name, choose **Public** and add a README. If it already exists, preserve useful content and review a change rather than replacing it blindly.

Copy your completed profile-template content into that repository's root `README.md`. Do not copy this workshop's main README.

For local editing, open a second terminal in the directory where you keep your projects:

```powershell
git clone https://github.com/YOUR-USERNAME/YOUR-USERNAME.git
Set-Location .\YOUR-USERNAME
git switch -c improve-profile
```

Edit `README.md` in that profile repository, then:

```powershell
git add README.md
git diff --cached
git commit -m "Connect my profile to verified project evidence"
git push -u origin improve-profile
```

Open a pull request in your profile repository, review the rendered Markdown and merge it into that repository's default branch. The workshop branch and the profile branch belong to different repositories.

## 6. Curate your pinned work

Open your profile and choose **Customize your pins**. Select projects whose READMEs make your contribution understandable. Follow [GitHub's pinning instructions](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile).

Start with two or three meaningful projects if you have them. That is a workshop recommendation, not a GitHub requirement. Label coursework and forks honestly. Explain the contribution inside each project's README.

Avoid third-party statistics badges or visitor counters by default. Links and clear evidence are enough for this exercise, without adding outside services.

## 7. Credit, review and publish

Complete [Citations](CITATIONS.md) and [Review checklist](REVIEW-CHECKLIST.md). Then open your public profile and confirm the README and intended project links work.

Ask a partner:

> Can you identify my direction, find the evidence for one claim and tell what I contributed?

Use the answer to make one revision. Finish with a concrete next action and date, not a promise to "learn more."

## What to share

Share your profile link voluntarily with a partner or mentor. You do not need to submit your profile, identity, resume or career plan to the upstream workshop repository.

Pull requests to the shared workshop should contain reusable improvements to instructions or templates only.
