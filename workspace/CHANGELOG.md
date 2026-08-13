<instructions>
## 🚨 MANDATORY: CHANGELOG TRACKING 🚨

You MUST maintain this file to track your work across messages. This is NON-NEGOTIABLE.

---

## INSTRUCTIONS

- **MAX 5 lines** per entry - be concise but informative
- **Include file paths** of key files modified or discovered
- **Note patterns/conventions** found in the codebase
- **Sort entries by date** in DESCENDING order (most recent first)
- If this file gets corrupted, messy, or unsorted -> re-create it. 
- CRITICAL: Updating this file at the END of EVERY response is MANDATORY.
- CRITICAL: Keep this file under 300 lines. You are allowed to summarize, change the format, delete entries, etc., in order to keep it under the limit.

</instructions>

<changelog>
- 2026-08-05: Updated `index.html` Settings Profile with Privacy cookie controls, browser privacy policy note, and a Danger Zone account deletion request block matching the provided reference.
- 2026-08-05: Updated `index.html` Automations: renamed the “Agents and Automations” tab/card to “Automations,” implemented the clipboard-inspired Triggers list and request integration form, and removed temporary `__ANIMA_DBG__` logs.
- 2026-08-05: Prevented malformed legacy `index.html` Automations markup from rendering by commenting the stale block out of the DOM and updated temporary `__ANIMA_DBG__` logging to report body-level automation orphans.
- 2026-08-05: Removed duplicate `Browser Plugin` markup from hidden legacy `index.html` Automations content, fixed missing closing tags around the visible Plugins panel, removed a duplicate Agent Variables ID block, and refined temporary `__ANIMA_DBG__` logging to count Browser Plugin cards.
- 2026-08-05: Fixed `index.html` Automations plugin bleed by forcing plugin fragments out of Agents and Automations, hiding legacy Automations, and showing only the active Agent/Browser plugin subtab; added temporary `__ANIMA_DBG__` visibility logging.
- 2026-08-05: Fixed duplicate `index.html` Automations Plugins cleanup: hardened legacy Automations hiding and moved Browser Plugin into the intended Plugins subtab panel instead of leaving a stray duplicate panel.
- 2026-08-05: Cleaned `index.html` Automations Plugins layout: grouped Agent Plugins and Browser Plugin under one Plugins tab, added Agent/Browser subtabs, stacked Manage before Library before Agent Variables, and reduced the intro prominence.
- 2026-08-05: Exposed the requested Agent Plugins UI in visible `index.html` Automations tabs with Library/Manage columns, real search input, plugin rows, and Agent Variables.
- 2026-08-05: Fixed `index.html` Knowledge Memories implementation: search is now a real input with client-side filtering, toolbar controls stay within the page, and memory text/filter weights are lighter.
- 2026-08-05: Restored `index.html` Knowledge Memories UI with All/Personal/Workspace/Organization/Archived filters, search, action buttons, and the visible workspace memory rows.
- 2026-08-05: Fixed `index.html` Autofill dropdown order so Completed opens directly below the tab row before Guided Workflows instead of rendering underneath workflows.
- 2026-08-05: Updated `index.html` Autofill tabs: removed Workflows from the tab row, added chevrons to Recent Forms/Completed, and made clicking an already-open tab close its panel while Guided Workflows remains visible.
- 2026-08-05: Updated `index.html` Autofill so Guided Workflows displays by default under the launch area while Recent Forms and Completed remain hidden until selected.
- 2026-08-05: Updated `index.html` Autofill tabs so form/workflow content stays hidden until clicked, changed the Recent Forms footer link to “View all work” pointing at My Work, and reduced form title/status/update text hierarchy.
- 2026-08-05: Refined `index.html` Autofill spacing and alignment: centered Recent Forms/Completed tabs and Guided Workflows, removed the redundant All forms/files link, tightened launch spacing, and made Recent Forms the default view with workflows below.
- 2026-08-05: Removed duplicate legacy `index.html` Autofill hero, Guided Workflows, workflow-card grid, and support footer markup so only the cleaned Autofill launch/file access area remains visible.
- 2026-08-05: Refined `index.html` Autofill launch: centered the header above equal green Upload/Create cards, shortened copy, removed purple secondary styling, and added an All forms/files entry for file access.
- 2026-08-05: Updated `index.html` Autofill landing: replaced the button row with large launch cards inspired by the reference, made Workflows the default Autofill panel, and hid Recent Forms/Completed tabs from the primary view.
- 2026-08-05: Updated `index.html`: removed the auto spacer from the Guided Workflows Help filter so it sits at the right end of the tab group, and changed sidebar organization/workspace flyouts to fixed high-z overlays so they no longer open behind the main screen.
- 2026-08-05: Updated `index.html` Autofill Guided Workflows: kept Help as its own filter tab and moved that Help tab to the far right of the workflow filter row.
- 2026-08-05: Updated `index.html` Autofill Guided Workflows: restored Help as its own workflow filter tab, moved help cards back into the card grid, and removed the visible right-side support rail.
- 2026-08-05: Updated `index.html` Autofill Guided Workflows: moved Help into a right-side support rail, defaulted workflow filters to B-Corp, and tightened the main grid so Help no longer dominates the guided workflow layout.
- 2026-08-05: Updated `index.html` Settings: removed keyboard shortcuts from Agent configuration, kept shortcuts in Help, and added a prototype disclaimer saying the shortcuts are not true to the live website.
- 2026-08-04: Updated `index.html` Guided Workflows heading block to match Autofill header styling (shared icon/title/subtitle visual language) on the default Recent Forms view.
- 2026-08-04: Updated `index.html` Autofill default view with a larger “Guided Workflows” section indicator so workflow cards are clearly signposted below Recent Forms.
- 2026-08-04: Updated `index.html` Autofill tab behavior so Workflows content appears on the default Recent Forms page; hid the separate Workflows tab label while keeping existing workflow filter/card interactions.
- 2026-08-04: Updated Autofill Workflows tab in `index.html` to match earlier guided-workflow UX: replaced table-like workflows view with filter chips + card grid including Help, B-Corp, ESG, Compliance, and Ratings workflow cards.
- 2026-08-04: Refined Knowledge Sources visual layout in `index.html` only: added cleaner section cards/toolbars, compact row styling, and better list density/scanability while preserving top search and Managed permission-level messaging.
- 2026-08-04: Updated `index.html` per IA feedback: reordered Knowledge tabs to Sources→Documents→Answers→Memories (Sources default), removed Email ingest, added Sources search + scrolling list layout and Managed section continuity; renamed Autofill tabs to Recent Forms/Workflows, aligned Completed content with My Work; reworked Automations to Agents and Automations + Browser Plugin with new/create+view automation entry points and moved Runs into Settings; restored Settings Workspaces/Members/Runs/Help, added Organization Support Access delete action, and added Profile connected emails/accounts.
- 2026-08-03: Simplified Knowledge Sources in `index.html`; removed the top Sources/Documents/Memories summary row and bottom sync explainer strip.
- 2026-08-03: Aligned Knowledge Documents/Answers/Memories/Sources tabs in `index.html` as a less-rounded segmented control matching sitewide tab styling.
- 2026-08-03: Renamed the visible Automations tab/card/button language from Scheduled runs to Runs in `index.html`; internal selectors remain unchanged.
- 2026-08-03: Moved the visible Recent runs list from Settings into the Automations Scheduled runs panel in `index.html`; removed the Settings Recent runs tab and panel markup.
- 2026-08-03: Audited `index.html` Automations, Settings, and Knowledge structures; located visible Scheduled runs tab, hidden legacy Recent runs panel, Settings Recent runs panel, and Knowledge pill tab selectors for the next move/refine steps.
- 2026-08-02: Tightened responsive scale in `index.html` with fluid page padding, smaller page/card typography, mobile sidebar stacking, and removed temporary `__ANIMA_DBG__` logs.
- 2026-08-02: Fixed scrolling in `index.html` by replacing `#sidebar { overflow: visible; }` with vertical scrolling, changing `<main>` to vertical scroll, and adding temporary `__ANIMA_DBG__` scroll diagnostics.
- 2026-08-02: Restyled Knowledge Documents in `index.html` to match the clipboard storage view with top storage header, usage bar, search/actions, filter chips, and folder-grid canvas.
- 2026-08-02: Reordered Knowledge selectable tabs in `index.html` to `Documents, Answers, Memories, Sources` so the default Documents view appears first in nav and Sources sits on the far right.
- 2026-08-02: Updated `index.html` Knowledge so Documents is the default tab on open, restyled the Documents panel to a storage-style folder-first starting view, and left-aligned Sources meta cards.
- 2026-08-02: Moved the Knowledge summary row (Sources/Documents/Memories) to the top of the Sources panel in `index.html` so it appears above content/tool sections instead of at the bottom.
- 2026-08-02: Updated `index.html` Knowledge top controls from static buttons to clickable radio tabs (Sources/Documents/Answers/Memories) and cleaned visual hierarchy by reducing oversized title/card/meta typography.
- 2026-08-02: Refined Knowledge UI in `index.html` to match the provided reference; updated Sources/MCP card layout and added correct brand icons for Google Drive, SharePoint, Asana, Atlassian, and Salesforce.
- 2026-08-02: Updated Scratchpad layout in `index.html` so the composer/input area stays anchored to the bottom of the viewport; threads now use internal scrolling within the chat list area.
- 2026-08-02: Removed forced internal scroll behavior in `index.html` by changing the main content div to `overflow-hidden` and relaxing viewport-based `min-height` rules that were causing unnecessary scrolling.
- 2026-08-02: Added global `details > summary` marker reset in `index.html` to remove remaining native disclosure arrows from sidebar switcher divs across browsers.
- 2026-08-02: Removed sidebar switcher arrows in `index.html` (all three account/workspace carets and summary markers) and removed the side-nav Browser Plugin item.
- 2026-08-02: Removed Settings-page arrow icons in `index.html` (memories external-arrow and billing carets) from the Settings content area.
- 2026-08-02: Added a clear active indicator line for selected Settings top tabs in `index.html` so selection state is visible without shadow styling.
- 2026-08-02: Removed Settings tab shadow styling in `index.html`; active/hover tab states now follow the same no-shadow treatment used across other tab sets (e.g., Automations).
- 2026-08-02: Adjusted Settings tab interaction styling in `index.html` to remove the new filled hover/selected treatment and match the existing app-wide tab behavior.
- 2026-08-02: Updated Settings section switching in `index.html` to a horizontal top-tab row above content panels; removed left-rail tab layout so selectors align with the app-wide tab pattern.
- 2026-08-02: Audited heading hierarchy in `index.html`; reduced oversized Automations panel headers (including Scheduled runs) and lowered Settings card title scale so section headers sit clearly below page-level H1s.
- 2026-08-02: Unified typography hierarchy in `index.html` so header/sidebar font treatment carries across Autofill, Automations, Notifications, Knowledge, and Settings by normalizing page-level font-family and reducing inconsistent heavy heading weights.
- 2026-08-02: Updated `index.html` so Recent runs appears only in the dedicated Recent runs Settings tab; removed the duplicate Recent runs card from Agent configuration and unified topbar/sidebar font family to match nav/header typography.
- 2026-08-02: Made `index.html` Settings sections fully clickable; left nav now switches Profile/Organization/Agent/Recent runs/Billing panels, topbar menu routes to matching Settings sections, and in-panel links now jump to appropriate sections.
- 2026-08-02: Further refined `index.html` Settings page for closer screenshot parity; tightened scale/spacing, updated nav/item density, switched identity fields to input-style blocks, and adjusted memories/runs card structure.
- 2026-08-02: Refined `index.html` Settings page to closely match the provided reference with a denser two-column layout, icon-led tabs, identity/memories card treatment, and recent runs row structure.
- 2026-08-02: Removed the `Documents` sidebar nav item from `index.html` for both scopes so Knowledge is the single source for documents.
- 2026-08-02: Updated `index.html` sidebar Browser Plugin nav item to use the Google Chrome icon for consistent plugin branding.
- 2026-08-02: Updated `index.html` Automations redesign visuals to match the previous design system; corrected Triggers/Browser Plugin icons and restored font/button hierarchy without changing layout structure.
- 2026-08-02: Updated `index.html` Automations redesign to use Autofill-style tabs; Triggers, Browser Plugin, and Scheduled runs now show only their matching panel when clicked.
- 2026-08-02: Updated scope parity in `index.html`; Personal now has Autofill access, Personal no longer force-switches to Scratchpad, and Documents moved under Knowledge for both scopes.
- 2026-08-02: Made Autofill tabs in `index.html` interactive with radio-driven state; Templates and Completed are now clickable and switch their own table views.
- 2026-08-02: Reduced Autofill text weight in `index.html`; softened title, tabs, form titles, status chips, and action text for cleaner visual balance.
- 2026-08-02: Fixed oversized Autofill typography in `index.html`; reduced hero subtitle/button/link scale and normalized spacing to remove visual inconsistencies.
- 2026-08-02: Refined Autofill UI in `index.html` to better match the screenshot: tighter hero copy/actions, underlined tabs, icon-based form rows, expanded list, and bottom “View all completed forms” link.
- 2026-08-02: Removed Autofill chat composer in `index.html` and made Business scope switching default to the Autofill page.
- 2026-08-02: Converted bottom Personal/Business scope controls into a connected segmented toggle in `index.html` with unified shell and active-state styling.
- 2026-08-02: Recreated new design direction in `index.html`; added Knowledge and Settings pages, redesigned Autofill and Automations views, and updated sidebar nav to include Knowledge/Settings while keeping Browser Plugin and Help visible.
- 2026-07-30: Kept shared bottom sidebar links in `index.html`; Help and Browser Plugin now remain visible for both organization and personal scopes.
- 2026-07-30: Removed sidebar helper descriptions in `index.html`; Your Work and Knowledge Base now show headings directly above nav items.
- 2026-07-30: Added personal workspaces in `index.html`; personal account view now shows a workspace switcher with private and sample workspaces.
- 2026-07-30: Added Organization and Workspace labels in `index.html`; sidebar switchers now clearly separate account and workspace scope.
- 2026-07-30: Fixed active account indicators in `index.html`; checkmarks now follow FermCorp vs Personal selection instead of staying on org.
- 2026-07-30: Closed account switcher after account selection in `index.html`; clicking FermCorp or Personal now dismisses the flyout after switching.
- 2026-07-30: Coordinated dropdown open states in `index.html`; user, organization, and workspace menus now close competing menus when opened.
- 2026-07-30: Moved settings into the user dropdown in `index.html`; clicking Kai Andreic now opens Settings, Languages, and Billing.
- 2026-07-30: Refined sidebar flyouts in `index.html`; fixed clipping, softened styling to match nav cards, removed all-caps labels, and added profile images.
- 2026-07-30: Added right-side account/workspace flyout switchers in `index.html`; included counts, emails, account actions, sample workspace, and new workspace action.
- 2026-07-30: Cleaned Scratchpad layout in `index.html`; fixed row alignment, text overflow, composer spacing, and page clipping.
- 2026-07-30: Added Scratchpad page in `index.html` using the provided chat-list design; personal account switching now opens Scratchpad by default.
- 2026-07-30: Added personal-account sidebar state in `index.html`; personal view now shows only Scratchpad, Automations, and Documents under Your Work.
- 2026-07-30: Added sidebar account switcher in `index.html`; org card now toggles between FermCorp organization and Kai personal account.
- 2026-07-30: Updated notifications digest in `index.html`; removed archive review and replaced mixed new memories with clickable Personal, Workspace, and Org memory lists.
- 2026-07-30: Added clickable weekly memory notifications in `index.html`; bell now opens a digest with memory counts, new memories, and archive recommendations.
- 2026-07-30: Cleaned Plugins hierarchy in `index.html`; added page intro, tightened plugin grid/card typography, and normalized plugin form text.
- 2026-07-30: Wired Automations internal tabs with tablist/tabpanel targets in `index.html` for clearer clickable page switching.
- 2026-07-30: Mapped clipboard-inspired Triggers, Plugins, Configurations, and Recent runs content into Automations tabs in `index.html`.
- 2026-07-30: Added internal clickable Automations tab controls in `index.html`; created panels for Automations, Triggers, Plugins, Configurations, and Recent runs.
- 2026-07-30: Removed Automations child links from sidebar in `index.html`; preparing them to become internal page tabs.
- 2026-07-30: Added clickable Automations page in `index.html`; removed the sidebar dropdown while keeping child links listed underneath.
- 2026-07-30: Moved Automations out from under Autofill in `index.html`; kept it as a standalone sidebar dropdown directly below Autofill.
- 2026-07-30: Centered Autofill hero content/actions in `index.html`; narrowed main content sections so the intro buttons feel aligned with the page.
- 2026-07-30: Applied low-fidelity Autofill layout in `index.html`; moved hero actions below intro, renamed Guided workflows, and added clickable workflow filters with card grid.
- 2026-07-30: Refined Autofill sidebar hierarchy in `index.html`; Automations is now a compact expandable subsidiary menu with working open/close behavior.
- 2026-07-30: Added Settings dropdown in `index.html`; clicking the header gear now shows Languages and Billing with a redirect indicator.
- 2026-07-30: Added Automations dropdown children in `index.html`; included Triggers, Plugins, Configurations, and Recent runs under Autofill.
- 2026-07-30: Moved Automations under Autofill in `index.html`; renamed the former Agent nav item and removed it from the bottom links.
- 2026-07-30: Refined header/sidebar controls in `index.html`; boxed the user name, added a header bug icon, moved settings after notifications, and removed sidebar settings.
- 2026-07-30: Updated header account area in `index.html`; added a user name before logout and removed the language flag from the topbar.
- 2026-07-30: Moved org/workspace selectors in `index.html`; removed FermCorp/Main Workspace from the topbar and added stacked dropdown-style cards to the sidebar.
- 2026-07-30: Updated topbar EA logo in `index.html`; replaced the previous brand image with the provided EA logo asset and matched its displayed width.
- 2026-07-30: Refined Autofill text hierarchy in `index.html`; reduced oversized hero/workflow/footer type, tightened button text scale, and removed temporary debug logs.
- 2026-07-30: Normalized Autofill UX in `index.html`; removed fake imperfection overrides, restored readable spacing/type, replaced purple/light CTAs with EA green buttons, and added temporary click debug logs.
- 2026-07-30: Added UX fix tasks to `workspace/TODO.md`; flagged inconsistent button styling, non-sitewide colors, fake imperfection overrides, card hierarchy, and page hierarchy.
- 2026-07-30: Incorporated B Corp and ESG workflow groups in `index.html`; added matching category labels, cards, icons, and button treatment.
- 2026-07-30: Added EA screenshot imperfections via CSS overrides in `index.html`; tightened offsets, uneven spacing, scale, and panel/card proportions.
- 2026-07-30: Updated notifications digest in `index.html`; removed list-description copy and ensured Personal, Workspace, and Org counts match visible entries.
- 2026-07-30: Realigned workspace rows in `index.html`; removed workspace avatars so names and descriptions line up cleanly.
<!-- NEXT_ENTRY_HERE -->
</changelog>
