# NexChat admin site

Private admin panel for NexChat payments, live at
https://nexchatadmin.vercel.app/ — NOT linked from the public site.

Payment form + auto check (TRX ID present, amount Rs 50, not a
duplicate, TRX ID at least 8 chars) + Accept / Reject / Block.
Auto check cannot verify a TRX ID against the EasyPaisa account —
final money must be checked in the EasyPaisa statement.

Deployed via Vercel Git integration on the `nexchatadmin` project.
Static site, no build step.
