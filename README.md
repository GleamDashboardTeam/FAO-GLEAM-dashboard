# GLEAM Lens: Youth Dashboard Challenge 2027

**Two footprints. One view. Your vision.**

An open call from the [Food and Agriculture Organization of the United Nations (FAO)](https://www.fao.org) and its [Global Livestock Environmental Assessment Model (GLEAM)](https://www.fao.org/gleam/en/) team for student teams to design **one GLEAM dashboard** that brings livestock greenhouse gas emissions and water use together.

> 📅 **Round 1 deadline: 15 March 2027, 23:59 Rome time (CET)**
>
> 📝 **Apply:** [online application form](https://forms.cloud.microsoft/e/wq0Mey9Mky)
>
> ✉️ **Questions:** [info-gleam@fao.org](mailto:info-gleam@fao.org)

---

## Contents

- [Why this challenge](#why-this-challenge)
- [The challenge](#the-challenge)
- [Who can take part](#who-can-take-part)
- [Key dates](#key-dates)
- [What you can win](#what-you-can-win)
- [How to take part](#how-to-take-part)
- [Data and resources](#data-and-resources)
- [What to submit in Round 1](#what-to-submit-in-round-1)
- [How to submit](#how-to-submit)
- [How Round 1 is assessed](#how-round-1-is-assessed)
- [Use of AI](#use-of-ai)
- [Open-Source Sharing Agreement](#open-source-sharing-agreement)
- [Pre-submission checklist](#pre-submission-checklist)
- [FAQ](#faq)
- [Contact](#contact)
- [Licence and acknowledgement](#licence-and-acknowledgement)

---

## Why this challenge

GLEAM is developed by FAO for the environmental assessment of livestock agrifood systems. Its public results are currently served through two separate dashboards, both with 2015 as the reference year:

- [GLEAM Emissions dashboard](https://foodandagricultureorganization.shinyapps.io/GLEAMV3_Public/)
- [GLEAM Water dashboard](https://foodandagricultureorganization.shinyapps.io/GLEAMV3_WATER_Public/)

They are among FAO’s most widely used dashboards, with over 1,500 users per month. The GLEAM team plans to merge them into one. Rather than design it only in-house, we are opening the question to young data and design talent. The goals are better user-centred design, a stronger and younger GLEAM Network, and visible proof of GLEAM’s commitment to openness, in line with the AGPL-3.0 licence adopted for GLEAM.

## The challenge

Show us what **one** GLEAM dashboard could look like: a single experience in which users explore livestock **emissions and water use side by side**, for policymakers, researchers, students and the wider public.

In **Round 1** we are looking for a **working first version**, not a finished product: a clickable demo built with real GLEAM data, plus a short design concept explaining who it is for and why it is designed the way it is.

The challenge runs in two rounds:

| Round | Who | What |
|---|---|---|
| **Round 1** | All teams | Clickable demo + design concept (max. 3 pages) |
| **Round 2** | 5 finalists | Revised app, improved with GLEAM mentorship and data clinics |

## Who can take part

- Teams of **1 to 5 members**, with one **Team Leader** who is the single contact with FAO.
- Every member must be **currently enrolled** in an undergraduate, master’s or doctoral programme.
- Participants from **any country** are welcome. Interdisciplinary teams (data, design, animal science, environment) are encouraged.
- Each person may join **one team only**.
- FAO staff and consultants, their immediate family members, and students or direct supervisees of jurors are not eligible.
- Participation is **free and fully online**. The working language is **English**.

## Key dates

| Date | Milestone |
|---|---|
| 15 December 2026 *(TBC)* | Call opens; data package available in this repository |
| **15 March 2027, 23:59 Rome time** | **Round 1 submission deadline** |
| 16 March – 7 April 2027 | Screening and jury review |
| By 9 April 2027 | 5 finalists announced; all teams informed |
| April – June 2027 | Round 2: finalists improve their apps with GLEAM mentorship and data clinics |
| **15 June 2027** | **Round 2 submission deadline (finalists only)** |
| September 2027 | Award to the winning team at the Global Conference on Sustainable Livestock Transformation, Rome |

## What you can win

**One winning team** receives:

- ✍️ Authorship credit on the global GLEAM dashboard
- 🤝 Collaboration opportunity with the GLEAM team
- 📊 Professional training in livestock data and analysis
- 🌍 Exposure to the global GLEAM network and international experts
- ✈️ An invitation to receive the award at the **Global Conference on Sustainable Livestock Transformation 2027** in Rome, Italy

All 5 finalists receive written jury feedback and GLEAM mentorship during Round 2.

## How to take part

1. **Get the data** from this repository ([Data and resources](#data-and-resources)).
2. **Build your clickable demo** and **write your design concept** (max. 3 pages).
3. **Deploy** the demo to a public link (for example on shinyapps.io, Posit Connect Cloud, Streamlit Community Cloud, Hugging Face Spaces or GitHub Pages).
4. **Prepare your GitHub repository** with all Round 1 components ([What to submit](#what-to-submit-in-round-1)).
5. **Sign** the [Open-Source Sharing Agreement](#open-source-sharing-agreement) and add it to your repository.
6. **Give read access** to the GLEAM account ([How to submit](#how-to-submit)).
7. **Register and submit** through the [online application form](https://forms.cloud.microsoft/e/wq0Mey9Mky) before the deadline.

## Data and resources

| Resource | What it is | How to use it |
|---|---|---|
| **GLEAM Lens data package**: [`data/`](data/) *(available from launch)* | GLEAM 3 results on livestock greenhouse gas emissions and water use (reference year 2015), with data dictionary, region lists and units | The **only** data source for values shown in your demo |
| **Current dashboards** | [Emissions](https://foodandagricultureorganization.shinyapps.io/GLEAMV3_Public/) and [Water](https://foodandagricultureorganization.shinyapps.io/GLEAMV3_WATER_Public/) | What exists today, and what to improve |
| **GLEAM model code** | [github.com/un-fao/GLEAM](https://github.com/un-fao/GLEAM) | Reference for how GLEAM results are produced and for definitions; you do not need to run the model |
| **GLEAM website** | [www.fao.org/gleam](https://www.fao.org/gleam/en/) | Background, methodology and publications |
| **Full instructions** | [`docs/`](docs/) | Submission instructions, assessment criteria and the Open-Source Sharing Agreement |

**Data rules.** Do not invent, gap-fill, extrapolate or alter values, by hand or with AI. Any derived indicator (for example water use per kg of protein) must be computed from the data package, with its formula explained in your README or design concept. If you add context from another source, label it clearly on screen and cite it.

### Demo requirements

- **Any development framework** (e.g. R Shiny, Shiny for Python, Dash, Streamlit, JavaScript). 
- **Clickable and real:** a user can click through your main user journey, and the screens show real values from the data package. Covering **both emissions and water** is essential; covering every indicator is not.
- **Public link** that opens without sign-in and stays online until at least **30 April 2027**.
- **Runs from your code:** someone else can run it by following your README (`renv.lock` for R or `requirements.txt` for Python recommended).
- **Clear for users:** plain-language labels, units and the reference year (2015) wherever values appear.
- **Safe:** no passwords, API keys or tokens in the code; no tracking or analytics that collect visitors’ personal data.
- **Open:** prefer open-source packages whose licences are compatible with AGPL-3.0.
- **Names and logos:** use the FAO and GLEAM names only to describe your participation; do not add the FAO logo.

## What to submit in Round 1

| # | Component | Requirements | Location in your repository |
|---|---|---|---|
| 1 | **Clickable demo** | Public link to the deployed demo | `demo_link.md` |
| 2 | **Source code** | Complete app code that runs following the README | `app/` |
| 3 | **Design concept** | PDF, max. **3 pages**: target users and key tasks; how emissions and water are integrated; information architecture; key design choices; what you would build next | `docs/design_concept.pdf` |
| 4 | **README** | See below | `README.md` |
| 5 | **Licence file** | GNU AGPL-3.0 licence text | `LICENSE` |
| 6 | **AI-use disclosure** | Completed template (below) | `docs/ai_use_disclosure.md` |
| 7 | **Signed agreement** | Open-Source Sharing Agreement signed by the Team Leader | Repository root |

⚠️ **Never put personal documents (e.g. student IDs) in your repository.**

### Recommended repository layout

```text
gleam-lens-<team-name>/
├── README.md
├── LICENSE                                        # AGPL-3.0
├── GLEAM_Lens_Open_Source_Sharing_Agreement_signed.pdf
├── demo_link.md                                   # public link to the demo
├── app/                                           # app code
├── docs/
│   ├── design_concept.pdf
│   └── ai_use_disclosure.md
└── media/
    └── screenshots/                               # optional: 2–3 key screens
```

Name your repository `gleam-lens-<team-name>` (lower case, hyphens, no spaces). If the data package is larger than 100 MB, do not commit it; state in your README where the app expects it (e.g. a `data/` folder listed in `.gitignore`).

### Your README must include

1. **Team:** team name; members with roles and universities.
2. **Concept summary:** who the dashboard is for and the core idea, in about 5 sentences.
3. **Demo link.**
4. **How to run:** language and version, packages, where to place the data, and the command to start the app.
5. **Data used:** files and variables from the data package, and formulas for any derived indicator.
6. **Licences:** code under AGPL-3.0; other materials (design concept, images) under CC BY 4.0.
7. **AI use:** one line summarising AI use, pointing to `docs/ai_use_disclosure.md`(docs/ai_use_disclosure.md).
8. **Acknowledgement:** “Built with data from FAO’s Global Livestock Environmental Assessment Model (GLEAM).”

## How to submit

Your repository may stay **private**.

1. On GitHub, open your repository and go to **Settings → Collaborators and teams**.
2. Under **Manage access**, click **Add people** and add the GLEAM dashboard team account `info-gleam@fao.org`.
3. Grant at least **Read** access.
4. Complete the [online application form](https://forms.cloud.microsoft/e/wq0Mey9Mky) with your team details, repository link and demo link, and submit.

At the deadline, the GLEAM team records the latest commit on your default branch. **Commits made after 15 March 2027, 23:59 Rome time are not assessed.** Do not change the deployed demo after the deadline, except to keep it online.

**Not using GitHub?** Repositories on other platforms (e.g. GitLab) are accepted: grant access to `info-gleam@fao.org` on that platform, or share a read-only link, and enter it in the application form.

## How Round 1 is assessed

**Step 1: Screening (pass/fail).** We check eligibility, the signed agreement, that all components are present, that the demo opens from its public link and shows real GLEAM data, and we trace at least 3 displayed values back to the data package. Any invented or untraceable value leads to elimination. Minor, correctable omissions may be fixed within 48 hours of notice.

**Step 2: Jury review.** Two jurors score each demo, read together with the design concept:

| Criterion | Weight | What the jury looks for in Round 1 |
|---|---|---|
| Coherence of Emissions and Water integration | 25% | One experience, not two dashboards side by side; shared filters; views that show trade-offs and co-benefits |
| User-centred design and storytelling | 25% | Clear users and tasks; key insights reachable in a few clicks |
| Usability and accessibility | 25% | Plain language; readable on mobile; colour-blind-safe; light on bandwidth |
| Technical feasibility and handover | 25% | Clean, documented code; runs from the README; credible plan to develop further |

The **5 highest-scoring teams** become finalists and receive written jury feedback, which is the starting point for GLEAM mentorship in Round 2. Full details are in the assessment criteria in [`docs/`](docs/).

## Use of AI

AI tools, including “vibe coding” (building an app largely by prompting an AI code assistant), are welcome, provided you respect these rules:

1. **No AI-generated numbers.** Every value shown must be traceable to the data package.
2. **Disclose** all AI use in `docs/ai_use_disclosure.md`(docs/ai_use_disclosure.md).
3. **Understand your work.** Your team must be able to explain and change every part of your app.
4. **Check facts** about GLEAM methods against official documentation; no invented references.
5. **Respect licences, privacy and security.** Never paste personal data, passwords or keys into AI tools.

Undisclosed significant AI use, or values that cannot be traced to the data package, lead to disqualification.

<details>
<summary><b>AI-use disclosure template</b> (copy into <code>docs/ai_use_disclosure.md</code>)</summary>

```markdown
# AI-use disclosure – <Team Name>

| Question | Answer |
|---|---|
| Which AI tools did you use? (name and version) | |
| For which tasks? (code, design ideas, text, translation, images, testing…) | |
| Approximately what share of the code was AI-generated? | 0–25% / 25–50% / 50–75% / >75% |
| How did you verify data accuracy and scientific content? | |
| Did you enter any personal or non-public data into AI tools? | Yes / No |

We understand and can explain all parts of our submission.
Signed (all members): <names>
```

</details>

## Open-Source Sharing Agreement

A signed agreement is **mandatory**: submissions without it are incomplete and will not be assessed. In it, the Team Leader confirms on behalf of all members that the work is original, that it is released under **AGPL-3.0** (code) and **CC BY 4.0** (other materials), that all members are eligible, and that the challenge rules, including the AI rules, have been followed. Members keep their intellectual property. One signature covers both rounds. Read the whole agreement before signing.

1. Download the agreement (docs/open_source_sharing_agreement.word): Word (.docx) to fill in, or PDF to read from [`docs/`](docs/).
2. Enter the date and the Team Leader’s full name at the top.
3. In the Article 2 table, list every member with full name, role (Team Leader/team member), university and team name.
4. Fill in the Team Leader’s name and signature at the end. Leave the FAO block blank.
5. Save as PDF named `open_source_sharing_agreement_signed.pdf` and commit it to your repository root before the deadline. Do not send it by email.

## Pre-submission checklist

- [ ] Demo deployed; public link opens without sign-in and shows real GLEAM data for emissions **and** water
- [ ] App runs from a clean checkout following the README
- [ ] Repository named `gleam-lens-<team-name>`; GLEAM account has Read access
- [ ] `demo_link.md`, `app/`, `README.md` and `LICENSE` (AGPL-3.0) in place
- [ ] `docs/design_concept.pdf`: 3 pages maximum
- [ ] `docs/ai_use_disclosure.md` completed
- [ ] `GLEAM_Lens_Open_Source_Sharing_Agreement_signed.pdf` at the root, all members listed, signed
- [ ] No secrets, personal documents or third-party material without rights in the repository
- [ ] [Application form](https://forms.cloud.microsoft/e/wq0Mey9Mky) submitted before **15 March 2027, 23:59 Rome time**

## FAQ

<details>
<summary><b>Do we need to know GLEAM already?</b></summary>

No. The data package includes a data dictionary, and the current dashboards and the GLEAM website explain the indicators. Interdisciplinary teams are encouraged.
</details>

<details>
<summary><b>Which programming language or framework must we use?</b></summary>

Any framework is accepted. The current GLEAM dashboards are built with R Shiny, so Shiny-based solutions are easiest for FAO to adopt, but this is not a requirement.
</details>

<details>
<summary><b>Can we submit more than once?</b></summary>

Yes. You can update your repository until the deadline, and if you submit the application form more than once, the latest response received before the deadline counts.
</details>

<details>
<summary><b>Do we need to prove we are students?</b></summary>

Yes, if asked. FAO may request proof of enrolment at any time and will request it from all finalists before they are announced. Never put proof of enrolment in your repository.
</details>

<details>
<summary><b>Who owns our work?</b></summary>

You keep your intellectual property. By signing the Open-Source Sharing Agreement, you release your code under AGPL-3.0 and other materials under CC BY 4.0, so FAO and others can reuse them under those licences.
</details>

Have another question? Open an [issue](../../issues) in this repository (do not post personal information) or email us. Answers of general interest will be added here, so all teams receive the same information.

## Contact

📧 [info-gleam@fao.org](mailto:info-gleam@fao.org). Please use the subject **“GLEAM Lens – Question – &lt;Team Name&gt;”**.

## Licence and acknowledgement

The code and documentation in this repository are released under the [GNU Affero General Public License v3.0](LICENSE). Terms of use for the GLEAM data package are given in [`data/`](data/) *(TBC)*.

When using GLEAM data, please acknowledge: *“Data from FAO’s Global Livestock Environmental Assessment Model (GLEAM).”*

---

<sub>GLEAM Lens: Youth Dashboard Challenge 2027 is organised by the GLEAM team, Animal Production and Health Division, Food and Agriculture Organization of the United Nations (FAO), Rome.</sub>
