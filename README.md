# realm-os-demo

Hosting for narrated walkthroughs of one medical-AI device through a REALM node, from both
sides of a conformity assessment: how a notified body reads the dossier, and how a
manufacturer gets the device there. The walkthroughs are generated from scripts in
`docs/demo/` of the `realm-os` repository; this repository holds only the built static site.

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

For notified bodies, three views of one script: a recorded video, an interactive
single-screen player, and a reading playbook. For manufacturers, two interactive players:
bringing a device onto a node (packaging, testing, signing, importing, certifying), and
evaluating it on a held-out test set. Screens are unretouched captures from a running
REALM-OS node; terminal steps are a real session against the published model image.

The model and every computed figure are real. The pre-market cohort is real clinical data and
is the manufacturer's own 30% hold-out, so evaluating on it reproduces the declared
performance under the node's control; it is not external validation. The post-market
surveillance dataset is synthetic, and the narration voice is machine synthesised. All of
this is stated in the walkthroughs themselves.
