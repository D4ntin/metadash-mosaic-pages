# Brand assets: source and licence

Fetched 2026-11-03 (production 08) from the archive's own site, byte for byte, never edited:

| file | source | what it is |
|---|---|---|
| `fortunoff-lockup.svg` | https://fortunoff.library.yale.edu/wp-content/themes/fortunoff/img/logo.svg | the site header's lockup: the Yale logo (white "Yale" on #02356B) and the wordmark *Fortunoff Video Archive / For Holocaust Testimonies*, outlined, in #0D99AB |
| `fortunoff-lockup-reversed.svg` | https://fortunoff.library.yale.edu/wp-content/themes/fortunoff/img/logo-footer.svg | the same lockup as the site's dark footer carries it: the wordmark in white, the Yale square unchanged |

Copied 2026-11-04 (production 08, round 2), byte for byte, never edited:

| file | source | what it is |
|---|---|---|
| `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png` | `../critical-editions/static/` (byte-identical to `../metadash-legacy/public/`) | the TV colour-bars icon, the one https://fortunoff.aviaryplatform.com/ serves (the owner's download of it is pixel-identical to the `.ico`'s 32 px frame); the dashboard's favicon and the header's Aviary link icon. Not a Yale mark. Replaces round 1's Yale "Y" favicon from the archive's site |

No Yale face ships. The dashboard's name is set in *Metadash Serif*, a subset of Source Serif 4 (SIL OFL), not a brand asset.
Its source and licence are in `app/src/lib/fonts/SOURCE.md` (the owner's pick, round 5, 2026-11-05). The two YaleNew Roman files
the prototype tried (the critical-editions webfont and a woff2 of the foundry's OTF, © Carter & Cone Type, licensed to Yale) were
removed in round 4. Their last commit is `c3b0908`.

**Licence.** The lockup: © Yale University; not openly licensed. The Yale logo is governed by Yale's identity rules
(https://yaleidentity.yale.edu/core-identity-elements/yale-logo-and-wordmarks/yale-logo): shown only in its own colours, scaled
proportionally, never the base of a new logo, clear space about the height of the "Y". Used here as the archive's own dashboard
carries its brand; the archive's sign-off on that use is the owner's to obtain (Stephen's review round, production 26).
