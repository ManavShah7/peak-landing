# Peak — landing page

Static landing page for Peak, an iOS fitness companion.
No build step: `index.html`, `img/`, `fonts/`. Open the file, or serve the folder.

## Design system
Built on the same system as manavshah.me. The tokens, type ramp, containers,
section padding, easing and the `[data-reveal]` entrance are taken verbatim
from that site's `app/globals.css`, whose numbers were measured off apple.com
product pages. The one substitution is the accent: Peak's lime stands where the
portfolio's pink does, and only ever on black, where it has contrast.

SF Pro Display is self-hosted in `fonts/` for non-Apple hardware; on Apple
hardware `-apple-system` resolves to the system cut and the optical axis picks
Text or Display by size.

## Images
Frames pulled from the September capture reel in `peakv1/captures/`.

## Waitlist
Posts to the `waitlist` table in Supabase with the public anon key. Every table
in that project has RLS enabled and no policy grants the anon role, so the key
carries insert and nothing else.
