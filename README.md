# Mizan information site

Small static information site for the private Mizan assistant. It is published from a separate repository and contains no framework code, private planning records, credentials, or OAuth secrets.

The site uses relative links so it works both at the repository path on GitHub Pages and at the root of a custom domain. Add a confirmed custom domain in GitHub Pages and configure its DNS only after the owner confirms the exact hostname; verify ownership before entering it as an authorized domain in Google Cloud.

The public pages describe Mizan as a private personal service and Google OAuth as in production for external users, but not verified by Google; authorization may show a warning and the audience is capped at 100 users. The pages disclose the current Gmail and Calendar scopes separately from the actions Mizan currently exposes. Reconcile them against the exact OAuth scopes, effective host/model providers, retention, and support contact configured for Mizan when those details change.
