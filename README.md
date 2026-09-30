# Security-Scanner
This app scans windows machines for missing OS and Application Patches &amp; Upgrades. It also detect security events detected by defender end points. 
About WinPatch — what it does, the four capability areas, attribution
Applications Required — .NET 6 Desktop Runtime, winget/App Installer, a browser, optionally Excel
Services Required — Windows Update service, WMI, internet access, and when admin rights are actually needed
Step-by-Step Guide — launch → scan patches → install patches → detect apps/services → check app updates, each with the exact buttons to click
How to Download Reports — which export buttons live on which tab, what each produces, and the save/open flow
Plus a short Troubleshooting section for the common snags (WU service not running, greyed-out install buttons, winget missing, WSUS-restricted results)
Defender status — run/AV status, real-time protection, tamper protection, engine/signature version, last signature update, last quick scan and last full scan
Threat detections — every entry in Defender's history (name, severity, status) with a reliable Action Needed flag built from Defender's own AdditionalActionsBitMask signal
App & browser control — SmartScreen (apps/files and Edge) + a best-effort Exploit Protection summary
Device security — Memory integrity (Core isolation), Secure Boot, TPM
Device performance & health — system drive free space, last boot time (labeled as best-effort, not a full mirror of Windows Security's telemetry-backed page)
Protection history — recent events from the actual Defender operational event log, with friendly labels for well-known event IDs
Highlights panel — everything above rolled into one severity-ranked list (Critical → High → Medium → Low) with plain-English recommendations, plus an "Overall Severity Highlight" card at the top
