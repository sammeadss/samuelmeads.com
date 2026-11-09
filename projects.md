---
title: "Projects"
permalink: /projects/
feature_row_setctl:
    - title: "Setctl (in development)"
      excerpt: |
        A minimal, terminal-style iOS workout logger for serious weightlifters. Local-first, so logging is instant and fully offline, with the ability to sync across devices.

        `Swift` `SwiftUI` `GRDB / SQLite` `Supabase` `StoreKit 2` `Metal` `GitHub Actions`

        Remaining: crash reporting, store assets, and TestFlight.
      url: "https://github.com/sammeadss/setctl"
      btn_label: "View on GitHub"
      btn_class: "btn--primary"
feature_row_choonit:
    - title: "Choonit (in development)"
      excerpt: |
        A web app for logging and ranking the music you listen to. Instead of star ratings, you pick between records you've already ranked, and Choonit works out a 0-10 score from the ranking.

        `TypeScript` `Next.js` `React` `Supabase` `PostgreSQL` `Drizzle` `Tailwind CSS`
      url: "https://github.com/sammeadss/choonit"
      btn_label: "View on GitHub"
      btn_class: "btn--primary"
feature_row_homelab:
    - title: "Homelab (in development)"
      excerpt: |
        A documented, security-minded homelab built to learn networking, virtualization and security properly. Each design decision is written up as an architecture decision record (ADR) with evidence. The repository is private for now, but will be made public.

        `Debian` `Proxmox` `nftables` `Docker` `Tailscale` `Loki` `Wazuh`
---

{% include feature_row id="feature_row_setctl" type="left" %}

{% include feature_row id="feature_row_choonit" type="left" %}

{% include feature_row id="feature_row_homelab" type="left" %}
