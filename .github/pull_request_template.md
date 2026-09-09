<!--
Pull request template for AI-Automations-Enterprise-Systems.
Keep every "## " heading exactly as written: the crucible / pr-check workflow reads them.
Text inside these comment blocks is guidance and disappears when the PR is rendered.
-->

## Linear
<!-- The issue this PR closes. Required: the check fails without a 1915-NNN id in the title or body. -->
1915-

## Summary
<!-- Two or three sentences. What changed and why, for a teammate who did not watch you work. -->

## Authored by
<!-- One line. Examples:
     human
     Claude Code · https://claude.ai/code/session_…
     Codex · https://chatgpt.com/s/…
     human + Claude Code (agent drafted, human edited) -->
human

## Verified by running
<!-- The commands you actually ran and their last lines. "Tests pass" is not evidence.
     Agents: paste output, do not summarize it. -->
```
$
```

## Data or credential impact
<!-- Every system this PR reads or writes, and where any credential lives.
     Write "None" if none. The check warns while this still reads "None / describe". -->
None / describe

## Risk and rollback
<!-- What breaks if this is wrong, who notices, how to undo it.
     "Low. Revert the PR." is a complete answer for most changes. -->

## Checklist
- [ ] Linear issue is In Review and links here
- [ ] No secrets, tokens, or customer data in the diff
- [ ] Scope matches the issue; anything extra got its own issue
- [ ] Docs updated if behavior changed

<details>
<summary>Reviewer notes</summary>

<!-- Where to look first, what you are unsure about, alternatives you rejected. Empty is fine. -->

</details>
