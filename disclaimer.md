# VoltDeck — Disclaimer

> Single source of truth for the user-facing disclaimer text. The same text appears verbatim in:
> - The first-launch onboarding screen (in-app)
> - Settings → About → Legal & Disclaimer (in-app)
> - The App Store description "Important Notice" section
> - The GitHub Pages support / privacy site
>
> The Swift constant `DisclaimerText.full` in `VoltDeck/Util/DisclaimerText.swift` is the in-app source. **Keep this markdown file in sync with that constant.**
>
> Apple compliance constraint: once V1.0 ships, this text can be made MORE generous (add features) but never LESS generous (don't remove obligations the user agreed to). See `docs/IMPLEMENTATION.md` §11 "Post-launch IAP description constraint."

---

VoltDeck is a code-reference and calculation tool for licensed electrical professionals. It is currently an early release.

**THIS APP IS NOT A SUBSTITUTE FOR YOUR PROFESSIONAL JUDGMENT, THE OFFICIAL NEC TEXT, OR YOUR AUTHORITY HAVING JURISDICTION (AHJ).**

Calculations in VoltDeck have not been independently audited or certified. You must:

- Verify every result against another calculator, hand calculation, or the NEC text before relying on it.
- Obtain AHJ approval for any installation that depends on a VoltDeck calculation.
- Treat results as a starting point for your own analysis, not as a final answer.

The developer assumes no liability for outcomes resulting from use of this app, including but not limited to incorrect wire sizing, incorrect overcurrent protection, code violations, fires, electrical injury, or installation failures. Use of VoltDeck is entirely at your own risk.

VoltDeck references the National Electrical Code® (NEC®) and NFPA 70®, both registered trademarks of the National Fire Protection Association (NFPA), Quincy, MA. VoltDeck is an independent product and is not affiliated with, endorsed by, or sponsored by NFPA. The NEC text itself is not reproduced — only re-tabulated numerical lookups and computed values are shown.
