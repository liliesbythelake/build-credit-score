# Build Credit

A plain-language, multilingual tool that helps newcomers to the United States understand and build their credit — starting from wherever they actually are, whether that's no credit history at all or an existing file they want to improve.

**Live demo:** _(add your GitHub Pages link here once enabled)_

## Why this exists

Credit is one of the least explained, most consequential parts of moving to the US financial system. Almost every major decision — renting an apartment, buying a car, getting a mortgage — runs through a three-digit number that most newcomers have never encountered before and no one sits down to explain. This project started from that gap, informed by firsthand experience navigating it.

## What it does

- A short intake (SSN/ITIN status, existing bank account, current credit history, goal) generates a **personalized, phase-based plan** rather than one generic checklist
- The plan **starts at the right point** for the person answering — someone who already has a bank account and some credit history doesn't repeat steps they've already done
- An **interactive simulator** shows how habits like on-time payment and credit utilization affect an estimated score over 12 months
- A **plain-language education section** covers what a credit score is, how the three credit bureaus work, and where to check it for free
- A **bank and credit card comparison** with real pros, cons, and requirements (ITIN vs. SSN, deposit requirements, etc.), linking to official sites
- **Full translation** into Spanish, Persian (with Dari/Afghan terms noted), Arabic, Ukrainian, and Somali — with English financial terms kept alongside translations throughout, since that's the vocabulary someone will actually need when talking to a real bank or landlord
- Progress is saved locally in the browser (no account, no server, no tracking)

## Status

This is a working prototype, not a finished, launch-ready product. Specifically, before this should be used by real people at scale:

- [ ] Native-speaker review of all five translations (AI-translated, not yet reviewed)
- [ ] Verification that bank/card details, rates, and eligibility requirements are current
- [ ] User testing with people from the actual communities this is meant to serve
- [ ] A disclosure statement on affiliate/compensation status (currently: none)

See the in-app Privacy and Accessibility sections (in the footer) for what's already handled on those fronts.

## Tech

Single self-contained HTML file — no build step, no dependencies, no backend. Open `index.html` in any browser, or serve it via GitHub Pages.

## License

MIT
