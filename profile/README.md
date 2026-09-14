<div align="center">

[**agentetna.com**](https://agentetna.com) · [Documentation](https://agentetna.com/docs.html) · [Changelog](https://agentetna.com/changelog.html) · [Hugging Face](https://huggingface.co/AgentEtna) · [Book a demo](https://cal.com/agententafounder/15min) · [X](https://x.com/AgentEtna)

&nbsp;

<!-- The full logo, centred, to close (2026-09-07, founder). It is the
     wordmark exactly as the site header sets it — Fraunces, weight 500 — as
     paths, so GitHub renders it without the font (scripts/build-wordmark.py
     in the product repo). One path in two inks: the ink follows GitHub's
     theme the way the app's own text follows its palette; nothing else about
     the mark changes. -->
<!-- ABSOLUTE URLs on purpose (2026-09-09): GitHub rewrites a relative img src to the repository's
     raw path, but leaves a <source srcset> alone — so a relative dark-mode source resolved against
     the org page (github.com/assets/…) and rendered as a broken image for everyone in dark mode.
     The light fallback worked, which is why it was missed. Keep both absolute. -->
<!-- ONE block, explicitly centred, with a <br> between the mark and the line (2026-09-10):
     GitHub ends an HTML block at the first blank line, so a <picture> and a <sub> in separate
     blocks can land side by side on one line, and the outer div's centring does not survive
     the split. -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AgentEtna/.github/main/profile/assets/wordmark-dark.svg?v=3">
    <img src="https://raw.githubusercontent.com/AgentEtna/.github/main/profile/assets/wordmark-light.svg?v=3" alt="Agent Etna" width="200">
  </picture>
  <br>
  <sub>The staging environment for AI agents.</sub>
</p>

</div>
