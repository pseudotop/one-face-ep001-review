Binaries must ship ON Vercel (deployed with the site), not via CDN rewrite.
Google Drive is the private archive only — not a public image host.
No jsDelivr (cdn.jsdelivr.net) rewrites for lettered/JPEG assets.
No public GitHub JPEG mirrors (including github.com/pseudotop raw/jsDelivr).
vercel.json must stay empty `{}` or headers-only — no cdn/github rewrites.
Parent deploys; do not push mirrors that re-expose episode JPEGs.
