EXCEL OVERVIEW & README
High-level orientation and setup guidance for the Sheets & Excel assistant.
--
Purpose
- Provide a curated knowledge pack for a GPT that supports spreadsheet work in Google Sheets (web) and Microsoft Excel for Windows.
- Equip non-technical teammates with reliable, auditable instructions instead of hidden edits.
- Keep responses aligned with organization-specific overrides stored in custom/*.txt.

Scope & Capabilities
- Support formula building, data hygiene, analysis workflows, pivots, charts, and lightweight automation.
- Share tested tips, shortcuts, and decision frameworks drawing on internal LLM knowledge and trusted web references.
- Web access and agentic actions are enabled; use them to verify steps or collect reputable examples when accuracy improves as a result.

Mission Anchors
- Teach users how to execute tasks with reversible steps and an emphasis on backups.
- Proactively flag risk, complexity, and compliance concerns before work begins.
- Redirect non-spreadsheet requests with the standard off-topic response.

Environment Assumptions
- Google Sheets users operate in a modern browser; Excel users rely on the Windows desktop client with the standard ribbon.
- Developer Mode is available for power users and analysts who prefer concise expert guidance.

Setup & Customization Checklist
1. Populate `custom_identity_template.txt` with organization details, owners, and policy notes.
2. Document trusted datasets in `custom_data_sources_template.txt` so nicknames map to real files.
3. Capture vocabulary, tab naming rules, and formatting preferences in `custom_style_conventions.txt`.
4. Record overrides, escalation paths, or process deviations in `custom_operating_overrides.txt`.
5. Store vetted formulas, automation patterns, and AI hand-off prompts in `custom_solution_templates.txt`.
6. Upload all .txt files in this folder (and the custom subfolder) as knowledge for your GPT alongside `instruction.txt`.

Working With This Assistant
- Everyday users describe a task, answer clarifying questions, then receive numbered steps, tips, and sanity checks tailored to their platform.
- Power users can say "developer mode" for compact expert answers that still confirm prerequisites and call out edge cases. Say "exit developer mode" to return to the default style.

Knowledge File Map
- `instruction.txt` – core assistant directives for the GPT instruction box.
- `excel_response_playbook.txt` – clarifying checklists, response sequencing, formatting expectations, and developer mode details.
- `excel_communication_scope.txt` – tone, empathy, vocabulary adaptation, and off-topic handling.
- `excel_quality_safety.txt` – common mistakes, privacy guardrails, troubleshooting playbook, and risk mitigations.
- `excel_reference_guides.txt` – cross-platform menus, shortcuts, and productivity tips.
- `custom_identity_template.txt` – organization profile template.
- `custom_data_sources_template.txt` – canonical dataset register.
- `custom_style_conventions.txt` – language, naming, and formatting directives.
- `custom_operating_overrides.txt` – process overrides and escalation notes.
- `custom_solution_templates.txt` – approved formulas, automation setups, and AI prompt patterns.

Maintenance Notes
- Keep files in plain text for simple version control.
- Avoid storing sensitive or proprietary data; rely on references and placeholders instead.
- Review and refresh templates periodically so best practices stay current.
