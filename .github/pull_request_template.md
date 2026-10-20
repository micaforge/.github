<!--
  Org-wide PR template (micaforge/.github). Every repo in the org
  inherits this file. A repo may extend it with its own
  .github/pull_request_template.md.

  The verification bundle is produced by the PR AUTHOR before requesting
  review: run every applicable check, paste results — not claims.
  The REVIEWER spot-checks 2–3 verifiable claims (re-run a command,
  eyeball the screenshots) before approving — never approve on claims
  alone. Docs-only PRs mark code checks N/A. An unchecked box with no
  explanation blocks review.
-->

## Summary
<!-- one paragraph: what changed and why -->

## Changes
<!-- bullet list of the actual changes -->

## Tier
<!-- T0 docs-only fast path · T1 standard · T2 high-blast-radius (+adversary).
     Declared by the author, confirmed by the reviewer; a wrongly-low tier
     is itself a finding. -->
Tier: T1 — <!-- why -->

## Verification bundle
<!-- The author ran every applicable check. Paste results, not claims. -->
- [ ] `bun run typecheck` — <!-- green / N/A (docs-only) -->
- [ ] `bun run build` — <!-- green / N/A -->
- [ ] `bun test` — <!-- green / N/A (no suite yet) / new tests: <names> -->
- [ ] `mica-audit` — <!-- clean / findings: <link> -->
- [ ] UI change? before/after screenshots at 390px + 1440px attached —
      <!-- yes, attached / N/A -->

## Flow / cycle
<!-- link to the brief/cycle this PR implements, if any -->

## Reviewer notes
<!-- anything the reviewer should look at first -->
