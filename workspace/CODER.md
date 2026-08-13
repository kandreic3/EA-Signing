<instructions>
This file will be automatically added to your context. 
It serves multiple purposes:
  1. Storing frequently used tools so you can use them without searching each time
  2. Recording the user's code style preferences (naming conventions, preferred libraries, etc.)
  3. Maintaining useful information about the codebase structure and organization
  4. Remembering tricky quirks from this codebase

When you spend time searching for certain configuration files, tricky code coupled dependencies, or other codebase information, add that to this CODER.md file so you can remember it for next time.
Keep entries sorted in DESC order (newest first) so recent knowledge stays in prompt context if the file is truncated.
</instructions>

<coder>
- 2026-08-05: Added clipboard-inspired Privacy cookie controls and Danger Zone account deletion block to the visible `index.html` Settings Profile panel.
- 2026-08-05: Updated visible `index.html` Automations tab label to “Automations,” replaced the compact Triggers card with the clipboard-inspired trigger list/request UI, and removed temporary `__ANIMA_DBG__` logging.
- 2026-08-05: Commented the malformed legacy `index.html` Automations block out of rendered DOM so stale plugin/configuration sections cannot become body-level orphan content; debug logging now counts body-level automation orphans.
- 2026-08-05: Removed the stale duplicate Browser Plugin markup from `index.html` legacy Automations content and fixed the Plugins panel closing structure so only one Browser Plugin card remains in the DOM.
- 2026-08-05: Locked `index.html` Automations plugin visibility so Agent/Browser plugin UI cannot bleed into Agents and Automations, legacy Automations stays hidden, and only the selected plugin subtab displays.
- 2026-08-05: Fixed duplicate Automations Plugins fallout in `index.html` by hard-hiding legacy `.automations-content` and replacing the stray old Browser Plugin panel with the proper Browser subtab panel.
- 2026-08-05: Cleaned visible `index.html` Automations Plugins IA: top-level Plugins tab now contains Agent/Browser subtabs, Agent Plugins stack Manage → Library → Agent Variables, and the intro is visually quieter.
- 2026-08-05: Exposed Agent Plugins in the visible `index.html` Automations redesign tabs; the plugin library was previously only present in the hidden legacy `.automations-content` area.
- 2026-08-05: Properly implemented `index.html` Knowledge Memories toolbar: contained filter chips, real search input with filtering behavior, and lighter memory typography.
- 2026-08-05: Restored `index.html` Knowledge Memories controls with filter chips, search, settings/add actions, and visible workspace memory rows matching the requested reference.
- 2026-08-05: Moved `index.html` Autofill Completed dropdown above Guided Workflows so tab content opens directly under its tab row instead of underneath workflows.
- 2026-08-05: Updated `index.html` Autofill so only Recent Forms and Completed appear as chevron dropdown tabs; clicking an open tab closes it while Guided Workflows stays visible outside the tabs.
- 2026-08-05: Updated `index.html` Autofill so Guided Workflows stays visible by default while Recent Forms and Completed remain hidden until their tabs are clicked.
- 2026-08-05: Updated `index.html` Autofill so Recent Forms, Completed, and Workflows stay hidden until selected; changed the bottom link to View all work and reduced form row text scale.
- 2026-08-05: Centered `index.html` Autofill tabs and Guided Workflows, removed the redundant All forms/files link, tightened launch spacing, and restored Recent Forms as the default tab with workflows below it.
- 2026-08-05: Removed the duplicate legacy `index.html` Autofill hero/workflows/support markup so the old Guided Workflows section no longer appears below the cleaned launch.
- 2026-08-05: Refined `index.html` Autofill launch so the header is centered above equal green action cards, copy is concise, purple styling is removed, and an All forms/files entry remains available.
- 2026-08-05: Updated `index.html` Autofill landing to match the provided hero/action-card reference and make Workflows the default visible panel so Recent Forms and Completed are no longer directly prominent.
- 2026-08-05: Updated `index.html` so Guided Workflows Help stays at the right end of the filter group without being pushed to the far edge, and sidebar account/workspace flyouts render above the main screen.
- 2026-08-05: Updated `index.html` Autofill Guided Workflows so Help remains its own filter tab but is visually positioned at the far right of the filter row.
- 2026-08-05: Updated `index.html` Autofill Guided Workflows so Help is back as its own workflow filter tab instead of a right-side support rail.
- 2026-08-05: Updated `index.html` Autofill Guided Workflows so Help is a right-side support rail and B-Corp is the default workflow filter, reducing Help dominance in the main workflow grid.
- 2026-08-05: Updated `index.html` Settings so keyboard shortcuts live only in Help, added a prototype disclaimer there, and removed the duplicate shortcut section from Agent configuration.
- 2026-08-04: Updated `index.html` Guided Workflows indicator to reuse Autofill header styling (same icon/title/subtitle language pattern) for stronger visual consistency on the default Recent Forms view.
- 2026-08-04: Added a larger visible Workflows section indicator in `index.html` Autofill default view so guided workflow cards below Recent Forms are clearly labeled.
- 2026-08-04: Updated `index.html` Autofill so guided workflow cards are visible on the default Recent Forms view; the separate Workflows tab label is hidden while preserving existing workflow filter/card behavior.
- 2026-08-04: Restored Autofill Workflows experience in `index.html` Workflows tab to a filtered card-grid format (Help/B-Corp/ESG/Compliance/Ratings) so it matches the original guided-workflow style while preserving the new tab structure.
- 2026-08-04: Refined Knowledge Sources UI in `index.html` with cleaner section containers, count/toolbars, denser list rows, reduced source icon scale, and improved scanability while keeping Sources search at the top and Managed permissions copy intact.
- 2026-08-04: Updated `index.html` IA and labels across Knowledge, Autofill, Automations, and Settings: Sources tab now leads, Email Ingest removed, Sources converted to searchable scroll lists, Autofill tabs renamed to Recent Forms/Workflows, Automations now uses Agents and Automations + Browser Plugin with Runs moved back into Settings, and Settings regained Workspaces/Members/Runs/Help plus organization Support Access and profile connected accounts details.
- 2026-08-03: Simplified Knowledge Sources content in `index.html` by removing the summary meta row and sync explainer strip from the Sources panel.
- 2026-08-03: Updated Knowledge navigation tabs in `index.html` from separated pills to an aligned segmented grid matching sitewide tab styling.
- 2026-08-03: Renamed visible Automations Scheduled runs language to broader Runs in `index.html` while keeping internal existing selectors stable.
- 2026-08-03: Moved Settings Recent runs content into visible Automations `.automations-redesign` scheduled-runs panel in `index.html`; Settings nav/panel for Recent runs was removed from markup.
- 2026-08-03: Audit found `index.html` has two Automations structures: visible `.automations-redesign` uses `automations-redesign-tab-scheduled-runs`, while hidden legacy `.automations-content` already has `automation-tab-runs` with Recent runs data.
- 2026-08-03: Audit found Settings Recent runs is controlled by `#settings-section-recent-runs`, `.settings-panel-recent-runs`, and `.settings-runs-*` styles in `index.html`.
- 2026-08-03: Audit found Knowledge tabs in `index.html` are `.knowledge-tabs/.knowledge-tab`; current styling is pill-like with `border-radius: 999px` and Sources pushed right by a specific margin-left rule.
- 2026-08-02: In `index.html`, responsive scale is controlled by fluid `main > div` padding/max-width plus desktop-height and mobile media queries near the end of the stylesheet.
- 2026-08-02: In `index.html`, sidebar scrolling is controlled by `#sidebar` custom CSS (`overflow-y: auto`) and main page scrolling by the `<main>` Tailwind classes (`overflow-y-auto overflow-x-hidden`).
- 2026-08-02: In `index.html`, Knowledge Documents now uses a clipboard-matched storage canvas with Share Center, storage usage, search/view controls, New action, filter chips, and folder-grid visuals.
- 2026-08-02: In `index.html`, Knowledge selectable nav order is now `Documents, Answers, Memories, Sources`; Documents opens by default and Sources is positioned at the far right tab.
- 2026-08-02: In `index.html`, Knowledge now opens on Documents by default (`#knowledge-tab-documents` checked), and the Documents panel uses a storage-style folder-first layout (`.knowledge-docs-*` classes).
- 2026-08-02: In `index.html`, the Knowledge Sources/Documents/Memories summary row (`.knowledge-meta-grid`) now lives at the top of `.knowledge-panel-sources` before content/tool cards.
- 2026-08-02: Knowledge top navigation now uses radio-driven tabs in `index.html` (`#knowledge-tab-*` + `.knowledge-panel-*`) instead of static buttons; use labels for clickable tab switching.
- 2026-08-02: Knowledge page styling is driven by `#knowledge-page .knowledge-*` classes in `index.html`; source/tool brand icons use Simple Icons CDN URLs.
- 2026-08-02: Autofill sizing is controlled by `.ea-autofill-*` rules in `index.html`; keep subtitle/buttons/body at regular UI scale (avoid oversized hero typography).
- 2026-08-02: `index.html` has two Autofill structures; only `.autofill-redesign` is visible while legacy `#hero-banner/#workflows-*` sections remain hidden via `#autofill-page > section { display: none; }`.
- 2026-08-02: Main UI is a single-file static app in `index.html` with state driven by radio inputs (`#nav-*`, `#account-scope-*`) and CSS selectors.
</coder>
