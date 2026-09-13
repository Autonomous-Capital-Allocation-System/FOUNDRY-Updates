# FOUNDRY 2.0.0-beta.17

Beta.17 corrects the supervised browser handoff when Live AI accurately leaves
unknown product details for human confirmation.

## Highlights

- Honest placeholders and `Needs confirmation` content no longer prevent a
  Chrome Companion pairing session.
- Missing core copy or missing registered assets continue to block safely.
- Fields containing unresolved information are explicitly flagged and withheld
  from destination forms instead of being pasted into them.
- Complete, unambiguous fields can still be prepared during the same supervised
  session.
- Gumroad, Patreon, and Product Hunt mappers share the corrected behavior.
- Updated user manual and private-beta testing guide.

## Required Chrome extension update

Remove or reload the prior unpacked extension and load the `browser_extension`
folder from the Beta.17 Chrome Companion ZIP. The application and extension must
both be Beta.17 for the new per-field attention flags to be honored.

## Private-beta trust status

The Mac package uses an ad-hoc beta signature and is not yet Developer ID signed
or notarized. The Windows installer is not yet Authenticode signed. Download
only from the official ACAS Tools FOUNDRY update repository.
