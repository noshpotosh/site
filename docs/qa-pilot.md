# QA pilot

Shared skills and workflows are pinned to 55c20059792644fcdca42b9118c319828fe66d87. Mechanical PR checks run automatically; model findings are advisory. Add OPENAI_API_KEY as an owner-managed repository secret to enable Codex review and weekly audits. No provider key was configured when this PR was prepared.

The remote main branch contains index.html, not the unpublished local navigation/physics test suite. This adoption does not publish or copy that local work. After its source lands, add CI for node --test tests/screen-navigation.test.mjs and node tests/runner-physics.cjs. Browser checks additionally need reproducible Playwright setup. These checks are currently unavailable, not passing.

After this workflow lands and its checks pass, preserve existing branch protection and add the observed review / review / QA / policy check as required. Do not require an absent workflow before merging adoption. Agents prepare recommendations; merges and history rewrites remain manual.
