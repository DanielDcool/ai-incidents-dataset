# AI Incidents Dataset

A sourced, daily-updated list of real-world incidents where AI agents or AI models broke rules, escaped test environments, or were used in cyberattacks. Maintained by [AI WILL DESTROY](https://aiwilldestroy.com/), an AI-threats news tracker in English, Chinese and Japanese.

## Files

- `incidents.csv` has one row per incident: date, title, progress_delta, url (the full write-up), and source_urls (original reports), entry_type and entry_point.
- `entry_type` says how the incident started, according to its sources: `credentials_or_open_door` (a weak, default, leaked, unretired or predictable password or key, or a page with no login), `known_software_flaw`, `new_software_flaw` (a zero-day), `not_disclosed` (access confirmed, entry point not given), or `no_confirmed_intrusion` (attempts, blocked, internal, or alleged and denied), or `same_as_other_entry` (a later development, such as a lawsuit, about an intrusion already listed). `entry_point` is a one-line description. Analysis: https://aiwilldestroy.com/how-ai-attacks-got-in/
- `incidents.json` holds the same data as JSON.

Every incident links to its original sources (company disclosures, security-vendor research, major media). Each write-up says what is confirmed and what is not.

## Categories

- AI cyberattacks: https://aiwilldestroy.com/ai-cyberattacks/
- AI that escaped tests: https://aiwilldestroy.com/ai-escaped-tests/
- Rogue AI agents: https://aiwilldestroy.com/rogue-ai-agents/
- All AI threats: https://aiwilldestroy.com/ai-threats/

## License

CC BY 4.0. Please credit "AI WILL DESTROY (aiwilldestroy.com)" and link back.

## Updates

The data is updated daily from https://aiwilldestroy.com/signals/incidents.csv
