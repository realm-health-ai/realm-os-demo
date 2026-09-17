# realm-os-demo

Hosting for a narrated walkthrough of a REALM conformity assessment, aimed at notified
bodies. The walkthrough itself is generated from `docs/demo/narration.md` in the `realm-os`
repository; this repository holds only the built static site.

## Note on access

**This repository is public, and so is everything in it.** The site is served from a
deliberately obscure path and carries `noindex` plus a `robots.txt` that disallows all
crawlers, so it will not appear in search results and cannot be reached from a guessable
URL. That keeps it unlisted. It does not make it private: anyone who finds this repository
can read every file directly.

If the material needs actual access control, it should not be hosted from a public
repository. Put it behind an authenticating edge such as Cloudflare Access, which verifies
an email one-time PIN before serving any file and can allowlist specific domains.

## Contents

The walkthrough comprises three views of the same script: a recorded video, an interactive
single-screen player, and a reading playbook. Screens are unretouched captures from a
running REALM-OS node.

The model and the pre-market cohort behind the figures are real; the post-market
surveillance dataset is synthetic, and the narration voice is machine synthesised. All three
facts are stated in the walkthrough itself.
