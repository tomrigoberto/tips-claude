# TaxStatus Daily Tips — Routine Setup Guide

This guide walks you through creating the routine at https://claude.ai/code/routines so the daily tips post to `#tips-claude` without your laptop being involved.

## Before you start

1. The curriculum file (`claude-tips-curriculum.md`) needs to be in the repo at https://github.com/tomrigoberto/tips-claude on the `main` branch. Push it now if you haven't.
2. The Slack connector needs to be enabled at https://claude.ai/customize/connectors with write access to `#tips-claude`.
3. Have `ROUTINE-PROMPT.md` open so you can paste the prompt block.

## Step-by-step

### 1. Open the routines page

Go to https://claude.ai/code/routines and click "Create routine" (or the equivalent "New" button).

### 2. Name the routine

Use a name like: `TaxStatus daily tip → #tips-claude`

### 3. Choose schedule type

Pick "Recurring" / cron schedule (not "Run once").

### 4. Set the cron expression

`0 14 * * 1-5`

That is "every weekday at 14:00 UTC." 14:00 UTC = 10:00 AM ET while EDT is in effect. The entire series runs May 19 to July 13, 2026 — all within EDT — so this single cron value is correct for the whole window. (DST ends Nov 1, 2026, well after the series finishes.)

### 5. Choose the environment

Select the **Default** environment (`env_018TYGiZi7Gn1ZksstsMYAzn`, anthropic_cloud). Anything that runs `Bash` and reads files works.

### 6. Choose the model

Default to `claude-sonnet-4-6`. The task is simple and Sonnet is more than sufficient. No need to spend Opus on this.

### 7. Attach the repository

Add a git source:

- Repository URL: `https://github.com/tomrigoberto/tips-claude`
- Branch: `main`

The routine clones this on each run, so `claude-tips-curriculum.md` will be in the working directory.

### 8. Attach the Slack connector

In the MCP connections or "Tools" section of the create form, attach Slack from your connected list. Make sure the connector's scope includes posting to `#tips-claude`. If Slack isn't listed there, head to https://claude.ai/customize/connectors first, connect it, then come back.

### 9. Allowed tools

At minimum, allow:

- `Bash`
- `Read`
- `Grep`
- Whatever Slack tool names appear from the Slack connector (typically something like `slack_send_message`)

You can allow `Edit` and `Write` too, but the routine doesn't need them for normal operation.

### 10. Paste the prompt

Open `ROUTINE-PROMPT.md`. Copy everything between the `---BEGIN PROMPT---` and `---END PROMPT---` markers (not including the markers themselves). Paste it into the routine's prompt / message field.

### 11. Save and enable

Save the routine with "enabled" set to on.

## Day 1 logistics

Today is Tue 2026-05-19. Day 1 is supposed to post at 10am ET today, but 10am ET has already passed. Two options:

- **Option A — post Day 1 manually.** After saving the routine, hit "Run now" on it once. The agent will compute "today = Day 1," read Day 01 from the file, and post it. From Wed 2026-05-20 onward, the cron handles everything.
- **Option B — let Day 1 slip to tomorrow.** Do nothing. Tomorrow at 10am ET the agent computes "Wed 2026-05-20 = Day 2" and posts Day 02, never posting Day 01. You'd need to decide whether to backfill manually or just accept that the series starts on Day 2.

Option A is the right call if you want the full 40-day arc as written.

## Verifying it works

After Day 1 posts:

1. Check `#tips-claude` — the message should match Day 01 from the curriculum file, with `**bold**` rendered as Slack-bold (single asterisk) not literal asterisks.
2. Go to https://claude.ai/code/routines, click the routine, and look at run history. The run log should show "Day 1 posted at <timestamp>."

If something looks wrong, the most common fixes are:

- Bold/italic showing as literal asterisks → the conversion step skipped. Edit the prompt to be more explicit, or check that Sonnet read the conversion rules.
- Wrong day posted → check the start date in the prompt and confirm the host clock vs America/New_York math.
- Nothing posted → check that the Slack connector is attached and the channel name in the prompt matches an existing channel the connector can write to.

## Stopping or pausing the series

- Pause: toggle "enabled" off in the routine page.
- Stop permanently: pause it, then delete via https://claude.ai/code/routines.
- Skip a single holiday: pause the day before, re-enable after.
