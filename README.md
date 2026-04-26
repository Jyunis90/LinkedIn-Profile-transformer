# LinkedIn Profile Transformer

> Reusable Claude prompts to transform any LinkedIn profile for recruiter visibility — built and battle-tested on a real profile.

Two ready-to-paste prompts that turn Claude into a LinkedIn coach. Pick the version that matches how you want to work — automated via browser, or fully manual.

---

## 🎯 What this does

Takes any LinkedIn profile from "invisible to recruiters" to **fully optimized for recruiter search** in two structured passes (~60 minutes total):

- **Pass 1** (~20 min): Headline, fix typos in job titles, Languages, About
- **Pass 2** (~40 min): Experience descriptions with skills tagged per role, global Skills cleanup, Certifications

The prompt forces Claude to:
- Extract and diagnose the current profile against the user's career target
- Identify broken auto-translated skills (e.g. `Lavado` → `Washing`), empty roles, missing keywords
- Generate copy-paste-ready text for each field
- Walk the user through edits one at a time, waiting for confirmation
- Stay honest — flag weak claims, refuse to inflate beyond what the CV supports

---

## 📦 Two versions

### 🅰️ [`prompt-side-panel.md`](./prompt-side-panel.md)

For users with **Claude in Chrome** installed (works on Chrome, Edge, and Brave).
Claude opens the user's LinkedIn directly, extracts the profile, and guides edits in the side panel.

**Pros:** Faster. Claude reads the profile itself.
**Cons:** Requires the Chrome extension and a paid Claude plan (Pro / Max / Team / Enterprise).

### 🅱️ [`prompt-copy-paste.md`](./prompt-copy-paste.md)

For users on **regular Claude.ai** (web or mobile), no extensions needed.
The user pastes their profile text manually; Claude returns the rewrite plan.

**Pros:** Works for anyone with a Claude account, including free tier.
**Cons:** Slower — manual extraction up front.

---

## 🚀 How to use

1. Pick the version that matches your setup.
2. Open the file and **fill in the 9-question intake** at the top (target role, industries, languages, etc.).
3. Paste the prompt into Claude (side panel or claude.ai).
4. Follow the field-by-field guidance.

The intake is the most important part — vague targets produce vague rewrites.

---

## 🧪 Why it works

Built from a real session that took a profile from:
- Headline: `Analyst` (one word)
- 6 of 7 experiences with **empty descriptions**
- Skills section containing literal junk like `Washing` (auto-translation of `Lavado`)
- Zero Languages, zero Certifications

…to a fully indexed, recruiter-searchable profile with proper keyword targeting for AML / Financial Crime / KYC / FATF / OFAC roles.

The two-pass structure exists because doing it all at once is too long; the field-by-field handoff exists because pasting 12 things into LinkedIn at once produces mistakes.

---

## ⚠️ Honest caveats

- **Claude in Chrome is officially supported on Chrome and Edge only.** Brave works (Chromium-based) but isn't supported by Anthropic — your mileage may vary.
- **The `Recruiters only` toggle on LinkedIn isn't 100% private.** If your current employer has LinkedIn Recruiter Lite, they can still see you flagged. Decide accordingly.
- **The prompts only generate content — they don't post, message, or change account settings.** That's intentional. You stay in control of every edit.
- **Garbage in, garbage out.** Without a real CV or solid intake answers, the rewrite will be generic. Don't skip the questionnaire.

---

## 🛠️ Contributing

Pull requests welcome. Especially interested in:
- Translations of the prompt to other languages
- Variants for specific industries (tech, finance, healthcare, etc.)
- Improvements to the intake questionnaire

---

## 📄 License

MIT — use it, fork it, modify it, ship it. Attribution appreciated but not required.
