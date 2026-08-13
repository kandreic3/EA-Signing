<instructions>
This file powers chat suggestion chips. Keep it focused and actionable.

# Be proactive
- Suggest ideas and things the user might want to add *soon*. 
- Important things the user might be overlooking (SEO, more features, bug fixes). 
- Look specifically for bugs and edge cases the user might be missing (e.g., what if no user has logged in).

# Rules
- Each task must be wrapped in a "<todo id="todo-id">" and "</todo>" tag pair.
- Inside each <todo> block:
  - First line: title (required)
  - Second line: description (optional)
- The id must be a short stable identifier for the task and must not change when you rewrite the title or description.
- You should proactively review this file after each response, even if the user did not explicitly ask, maintain it if there were meaningful changes (new requirement, task completion, reprioritization, or stale task cleanup).
- Think BIG: suggest ambitious features, UX improvements, technical enhancements, and creative possibilities.
- Balance quick wins with transformative ideas — include both incremental improvements and bold new features.
- Aim for 3-5 high-impact tasks that would genuinely excite the user.
- Tasks should be specific enough to act on, but visionary enough to inspire.
- Remove or rewrite stale tasks when completed, obsolete, or clearly lower-priority than current work.
- Re-rank by impact and user value, not just urgency.
- Draw inspiration from the project's existing features — what would make them 10x better?
- Don't be afraid to suggest features the user hasn't explicitly mentioned.
</instructions>

<todo id="wire-profile-picture-upload">
Wire profile picture upload flow
Connect the new profile picture area to file picking, preview, validation, and account persistence.
</todo>

<todo id="decide-knowledge-sources-scale-pattern">
Finalize long-term Sources scaling pattern
Validate whether the new scrolling list should become the permanent pattern for large source catalogs and define pagination/virtualization requirements.
</todo>

<todo id="wire-sidebar-nav-state-memory">
Persist selected sidebar page and account scope
Store selected nav route and personal/business scope in localStorage so refresh keeps the user on the same context.
</todo>

<todo id="add-interactive-table-actions">
Add functional actions to forms, automations, and runs rows
Hook row menus, status filters, new automation actions, and view-all actions to interactive states.
</todo>

<todo id="connect-settings-members-workspaces-data">
Back Settings Members and Workspaces with real data
Replace static counts with account-scope aware member and workspace data for personal and business plans.
</todo>
