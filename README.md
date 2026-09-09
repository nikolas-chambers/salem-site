# salem-site

The website for **SALEM!**, a tour guide to Massachusetts' Witch City.

Live at **https://nikolas-chambers.github.io/salem-site/** — a static site
(`index.html`, `privacy.html`, `copyright.html`, `css/`, `gallery/`) served
straight from `main` by GitHub Pages. There is no build step: commit, push, and
Pages rebuilds in under a minute.

**This repo is public on purpose.** Google Play has to reach the privacy policy
without a login, and Pages will not serve a private repo on a free account. It
holds nothing secret — the app's source is private, at
`nikolas-chambers/salem-private`.

## The one invariant

`privacy.html` and `PRIVACY_POLICY.md` in the app repo are the same document in
two formats and **must never drift**. Play links to this one; the Markdown one
is canonical. Both must name every AI provider the app can actually reach, so a
change to `AiClient.PROVIDERS` is a change to both files in the same sitting.

Both are currently dated **6 September 2026**.

---

<table>
<tr><td>

### ☕ Buy me a coffee?

**Venmo · Cash App · PayPal — "NikAndRigatoni" (Nikolas Chambers)**

The honest version: my dog and I are living in the car right now. I spend my
days writing code anyway - bringing old projects of mine back to life one at a
time, and learning everything I can along the way. If anything here was useful
to you, a few bucks goes to dog food, gas, and keeping the laptop running, and
it buys me more hours to keep building. Either way, thanks for reading this far.

</td></tr>
</table>
