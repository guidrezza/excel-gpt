EXCEL ASSISTANT README
Overview and setup steps for this instruction pack.
--
What this is:
- A set of plain-text knowledge files that guide a GPT specializing in Google Sheets and Microsoft Excel for Windows.
- Web access and agentic capabilities are enabled; leverage them alongside internal LLM knowledge to enrich guidance.
- Instructions in custom/*.txt override base files when conflicts appear.

Quick start:
1. Fill custom/custom_identity_template.txt with your organization details.
2. Register trusted datasets in custom/custom_data_sources_template.txt.
3. Document vocabulary and naming preferences in custom/custom_language.txt and workflow conventions in custom/custom_conventions.txt.
4. Review excel_operating_principles.txt and adjust defaults (date format, allowed tools, formula posture).
5. Populate custom/custom_formula_templates.txt, custom/custom_automation_templates.txt, custom/custom_ai_prompts_examples.txt, and custom/custom_instructions.txt with vetted examples or overrides.
6. Upload all .txt files in this folder (and the custom subfolder) as knowledge for your GPT.

How to use:
- Everyday users: Ask for a task. The assistant clarifies missing inputs, detects the platform, then returns numbered steps, tips, placeholders, and sanity checks.
- Power users: Say "developer mode" for compact responses that still honor prerequisites, platform detection, and custom directives.

File guide:
- excel_overview.txt - mission, scope, and capabilities.
- excel_audience_tone.txt - audience, tone, and voice.
- excel_operating_principles.txt - governing rules for responses.
- excel_response_flow.txt - default conversation structure.
- excel_developer_mode.txt - toggling developer mode behavior.
- excel_equivalent_menus.txt - cross-platform menu mappings.
- excel_off_topic.txt - how to respond outside scope.
- excel_clarifying_questions.txt - discovery checklists.
- excel_step_by_step_style.txt - formatting expectations and tip usage.
- excel_common_mistakes.txt - pitfalls to address proactively.
- excel_data_privacy.txt - privacy reminders.
- excel_troubleshooting.txt - quick fixes for common issues.
- excel_glossary_conventions.txt - naming and data standards.
- excel_tips.txt - shortcuts and best-practice reminders for Sheets and Excel.

Custom folder (custom/*.txt):
- custom_identity_template.txt - organization-specific metadata.
- custom_data_sources_template.txt - reference data catalog.
- custom_language.txt - vocabulary and terminology preferences.
- custom_conventions.txt - preferred spreadsheet conventions.
- custom_formula_templates.txt - formula library template.
- custom_automation_templates.txt - automation library template.
- custom_ai_prompts_examples.txt - pre-built AI hand-off prompts.
- custom_instructions.txt - overrides for response patterns or scripting formats.

Notes:
- Avoid hard-coded company details; customize the templates before distribution.
- Keep instructions in plain text for easy version control and updates.
- Periodically review placeholders to ensure they reflect current best practices and leverage new tips surfaced via internal LLM knowledge or web resources.

Contributing:
- Share updates or new sections via your standard change-management process.
- Do not store sensitive or proprietary formulas in these files without approval.
