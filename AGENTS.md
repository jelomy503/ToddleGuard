## Model configuration: Fast mode is off

Fast mode must never be enabled for any model, on any agent, subagent, cloud agent, background job or automation working on this repository, unless Jeremy explicitly turns it on himself for that run.

- This covers every model and every version, for example "Grok 4.7 High - Fast", "Grok 4.6 High - Fast", or any model with `fast: true`.
- When you launch, configure or suggest a model for another agent, always set `fast` to `false` or leave it off, and never pick a "Fast" variant.
- If you notice you are running in Fast mode without Jeremy having turned it on, say so in your first message and in the PR description.
- Only Jeremy can change this rule.
