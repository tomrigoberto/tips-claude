# TaxStatus Claude Daily Tips Curriculum

This file is read by a Claude Code Routine that posts one tip per workday to #tips-claude. Each tip is bounded by `---DAY-NN---` and `---END-DAY-NN---` markers. The Routine picks today's tip by counting workdays elapsed since the start date.

**Start date:** Monday of Week 1 (set in the routine prompt)
**Posting cadence:** Monday–Friday, 9:00 AM ET
**Total tips:** 40 (8 weeks × 5 workdays)

---

---DAY-01---
**Subject:** 👋 Kickoff: why we're doing this

Good morning, TaxStatus.

Starting today, we're rolling out Claude across the company. Over the next 8 weeks, we're going from "I've heard of AI" to "Claude is in my workflow every day."

*Why now:* The advisors we serve are evaluating AI to make sense of tax data, plan strategy, and serve clients faster. If we're going to lead WealthTech, the people who build the product and run the company need to use the best AI tools available — fluently.

*What to do today:*
1. Open claude.ai. Sign in with your work email (SSO).
2. Download the desktop app (Mac/Windows) and the mobile app.
3. Send Claude one message about something on your plate today. Anything. "Help me think through X." See what happens.

*What to expect from this rollout:*
• One post per workday. ~2 minutes to read. Always one concrete action.
• Fridays = wins. Share what you shipped.
• No dumb questions. Reply in thread.

Let's go. 🚀
---END-DAY-01---

---DAY-02---
**Subject:** The single most important habit

If you take one thing from this whole rollout, take this:

> Treat Claude like a smart new colleague who joined yesterday — knows a lot, but knows nothing about us.

New colleagues need context. Project background. Examples of how we write. Who the audience is. What "good" looks like.

When people get bad results from AI, 9 times out of 10 it's because they gave it a prompt they would never give a real person.

*Compare these two:*
❌ "Write a follow-up email to a prospect."
✅ "Write a follow-up email to a $250M RIA principal I met at Future Proof last week. She runs a tax-focused practice and was interested in our IRS transcript monitoring. Tone: warm, peer-to-peer, no jargon. ~120 words. End with a specific next step. Here's our last conversation: [paste notes]."

The second one gets you a usable draft. The first one gets you generic AI sludge.

*Today's exercise:* Pick one task on your list. Write the prompt twice — once lazy, once with full context. Send both. See the difference. Reply in thread with what you noticed.
---END-DAY-02---

---DAY-03---
**Subject:** The C.R.A.F.T. prompt framework

You don't need this forever — once it's in your muscle memory, you'll just do it. But for week one, use this checklist.

*C.R.A.F.T.*
• **Context** — what's the situation, who's involved, what's the background
• **Role** — who do you want Claude to act as ("act as a senior compliance attorney reviewing this clause...")
• **Ask** — what specifically you want it to do
• **Format** — bullets? memo? table? word count?
• **Tone** — formal, casual, peer-to-peer, executive

*Try this template:*
> "Context: [2–3 sentences]. Act as a [role]. I need you to [ask]. Format it as [format]. Tone: [tone]. Here's the source material: [paste]."

*Today:* Take a task you'd normally spend 30+ minutes on. Try CRAFT. Time it. Reply in thread with the time delta.
---END-DAY-03---

---DAY-04---
**Subject:** Iterate — don't restart

Common mistake from new users: they get a bad first answer, give up, and go back to doing it manually.

The right move: keep the conversation going.

*Three iterations that fix 80% of bad outputs:*
1. "Make it shorter / longer / more specific."
2. "That's too generic. Here's what we actually mean: [add detail]. Try again."
3. "Critique your own answer first. What's weak about it? Then rewrite."

The third one is unfairly effective. Try it today on something Claude already wrote for you.

*Bonus move:* When Claude does something perfectly, tell it. "This is exactly right — remember this style." Then ask it to do another task in the same style. It's scary how well this works.
---END-DAY-04---

---DAY-05---
**Subject:** Week 1 wins 🎉

First week down. The hardest one.

*Share-out — reply in thread with:*
• One task Claude helped you ship this week
• One thing you tried that flopped (this is more valuable than the wins)
• One question you have going into next week

*What's coming next week:* We're going to go deeper on prompting — the techniques that separate "I use AI sometimes" from "AI is part of how I work." We'll cover examples, role-prompting, reasoning, and how to get Claude to push back on you instead of just agreeing.

Have a great weekend. 👋
---END-DAY-05---

---DAY-06---
**Subject:** Show, don't tell — example-driven prompting

When you want a specific style or format, examples beat instructions every time.

*Instead of describing what you want...*
> "Write a follow-up email to a prospect that's friendly but professional, not too long, with a clear next step..."

...give Claude 1–2 examples of follow-ups you (or someone here) actually sent that landed well. Then ask:

> "Match this voice and structure for this new prospect: [details]."

This is called "few-shot prompting" and it's the single biggest unlock once you have CRAFT down.

*TaxStatus-specific exercise:* Pull two of our best advisor-facing emails (sales, CS, whoever — your function). Paste both into Claude as examples. Ask it to draft a third for a new prospect. Notice how much closer it lands. Share what worked in thread.
---END-DAY-06---

---DAY-07---
**Subject:** Role-prompting — who do you need Claude to be?

"Act as a..." is the cheat code most people underuse.

*Try these today:*
• "Act as a skeptical RIA principal evaluating our pitch. Find the three weakest points and tell me how you'd push back."
• "Act as a §7216 compliance attorney reviewing this marketing copy. What needs to change?"
• "Act as the customer who just churned. Write the email I should have sent to keep them."
• "Act as a senior product manager. Critique this PRD as if you were going to ship it Monday."

Role-prompting changes what's in Claude's working context. A "skeptical RIA principal" thinks differently from a "supportive coach" — and both are useful in different moments.

*Bonus:* For really high-stakes work, have Claude play three roles back-to-back on the same artifact. "First as the buyer, then as the compliance reviewer, then as the CEO." You'll catch things you would have missed.
---END-DAY-07---

---DAY-08---
**Subject:** Get Claude to think before it talks

For anything complex — strategy, analysis, anything where the answer isn't obvious — add this to your prompt:

> "Think through this step by step before answering. Show me your reasoning, then give me the recommendation."

This is "chain of thought" and it dramatically improves quality on hard problems. The downside: longer outputs. Don't use it for "what's the capital of France." Use it for "should we change our pricing model?"

*When to reach for it:*
• Strategy decisions with tradeoffs
• Diagnosing why something isn't working
• Comparing options
• Forecasting / "what could go wrong"

*Today:* Take a decision on your plate. Ask Claude to think it through step by step, then give you a recommendation. Don't just take the recommendation — read the reasoning. That's the actual value.
---END-DAY-08---

---DAY-09---
**Subject:** Make Claude argue with you

One of Claude's default behaviors is to be helpful and agreeable. That's usually good. But when you're making a real decision, agreeable isn't what you need.

*Try these:*
• "Steelman the opposite of what I just said. Be your most convincing self."
• "What am I most likely getting wrong here? Don't be polite."
• "Pre-mortem this plan: assume it failed in 6 months. Why?"
• "You're my smartest advisor and you think this is a bad idea. Make the case."

If you don't explicitly invite pushback, you won't get it. And if you only use AI for affirmation, you're using it wrong.

*TaxStatus-specific exercise:* Take one current bet (a feature, a partnership, a messaging angle, a hire). Have Claude steelman against it. Reply in thread with the most uncomfortable thing it said.
---END-DAY-09---

---DAY-10---
**Subject:** Week 2 recap + sensitive data 101

*Recap of where we are:*
• CRAFT prompts ✓
• Examples > descriptions ✓
• Role-prompting ✓
• Reasoning ✓
• Pushback ✓

Before we move into Projects and Connectors next week, one important note.

*Sensitive data — read this carefully.* Claude Team has enterprise-grade security and your conversations are not used to train models. But our compliance obligations under §7216, FCRA, and our contractual commitments still apply.

*Default rules:*
• No client SSNs, full tax IDs, account numbers, or raw IRS transcript data in prompts — ever.
• Aggregated, anonymized, or hypothetical examples are fine.
• If you're not sure whether something is OK to share with Claude, ask in #compliance or DM me before posting it.
• The same rules you follow for Slack, email, and Google Docs apply to Claude.

Have a great weekend. Next week we go from "Claude as a chat tool" to "Claude as part of TaxStatus."
---END-DAY-10---

---DAY-11---
**Subject:** Meet Projects

So far you've been chatting with Claude one conversation at a time. Useful, but it forgets everything between chats.

**Projects** fix that. A Project is a persistent workspace where you load:
• Background documents Claude should always know about
• Style/voice guidelines
• Custom instructions (how you want it to behave in this Project)

Every chat inside that Project starts with all of it loaded. No more "let me re-paste our brand guidelines for the 12th time."

*Today:*
1. Click "Projects" in the left sidebar of Claude.
2. Create one called something like "Inbox" or "My Workspace."
3. In Custom Instructions, paste 3–5 sentences about your role and how you want Claude to communicate with you.
4. Upload 1–2 docs you reference a lot. Try a chat. Notice how it shifts.

We'll set up a shared TaxStatus team Project tomorrow.
---END-DAY-11---

---DAY-12---
**Subject:** The TaxStatus shared Project

I've set up a shared team Project called **"TaxStatus — Shared Context."** You should see it in your Projects list.

*What's in it:*
• Our positioning + messaging doc
• Brand voice guidelines
• Top 5 advisor personas we sell to
• Our top 3 competitive battlecards (Holistiplan, FP Alpha, TaxPlanIQ)
• A do-not-say list (e.g., not "IRS approved vendor")

*Try this today:* Open the shared Project. Run any TaxStatus-flavored task you have right now — drafting an email, summarizing a meeting, writing a LinkedIn post. Compare it to what you would have gotten in a blank chat.

The difference is the entire point of Projects. The work is sharper because the model finally has our context.

*Reminder:* The shared Project is for company context, not client data. Same sensitive-data rules apply.
---END-DAY-12---

---DAY-13---
**Subject:** Function-specific Projects

Beyond the shared TaxStatus Project, every function should have its own:
• **Sales** — prospect research templates, discovery question library, top objections + best responses, win/loss notes
• **CS** — onboarding playbook, top support questions, escalation patterns
• **Product/Eng** — current roadmap, PRD templates, design system, architecture overview
• **Marketing** — brand guidelines, content calendar, top-performing posts, swipe file
• **Ops/Finance** — vendor list, recurring report templates, policy docs
• **Leadership** — board materials, OKRs, key strategic docs

*Today:* Set up a Project for your function. Doesn't have to be perfect. Get the bones in.

Tomorrow we'll add Connectors so Claude can pull live data instead of you copy-pasting it.
---END-DAY-13---

---DAY-14---
**Subject:** Connectors — stop copy-pasting

Right now you're probably copying data from Google Drive, Slack, HubSpot, or Microsoft 365 into Claude. Connectors eliminate that.

*What Connectors let Claude do:*
• Search your Google Drive / SharePoint and read documents directly
• Search Slack channels and threads you have access to
• Look up contacts, deals, and notes in HubSpot
• Pull in calendar events and recent emails
• Fetch meeting notes from Granola or Zoom
• And many more, depending on what we connect

*Today's setup:* Go to Settings → Connectors. Connect the tools you use daily. At minimum: Google Drive (or M365) and your meeting note tool.

*Try this prompt:*
> "Find the latest version of [doc name] in my Drive, read it, and give me a 10-line summary I can share with my team."

When this works, it feels like cheating. It's not. It's the new default.
---END-DAY-14---

---DAY-15---
**Subject:** Week 3 wins + the shift

You should be feeling the shift this week. Chat-as-a-tool was useful. Projects-with-context is qualitatively different.

*Share-out — reply in thread:*
• Which Project gave you the biggest "aha"
• One Connector you set up and what it unlocked
• One thing that's still clunky (we'll fix it together)

*Looking ahead:* Next week — role-specific deep dives. Sales day, CS day, product/eng day, marketing day, ops/leadership day. The goal: by end of next week, every function has at least 3 named, repeatable Claude workflows.

Weekend assignment (optional): pick one workflow you do every week. Imagine if Claude did 80% of it. We'll build it Monday.
---END-DAY-15---

---DAY-16---
**Subject:** Sales day

Sales team — this one's for you. Everyone else, read it anyway. The pattern applies.

*Three workflows to build today:*

1. **Pre-call research.** Drop a prospect's name + firm. Ask Claude to pull from AdvizorPro (if connected) + public sources to brief you in 5 bullets: AUM, focus, recent moves, hooks for our pitch, likely objections.
2. **Post-call follow-up.** Paste your meeting notes (or have Granola/Zoom feed them in). Ask for: a recap email to the prospect, an internal CRM note, and 2–3 next-step recommendations.
3. **Discovery question generator.** Paste a prospect profile. Ask for 10 questions tailored to their practice that would surface whether they're a fit for TaxStatus.

*Sales-specific prompt template:*
> "Act as a tax-focused RIA principal evaluating TaxStatus. Here's their profile: [paste]. I have a discovery call in 1 hour. Generate: (1) 5 things I should know before the call, (2) 3 likely objections and how to handle them, (3) 10 discovery questions ordered from low-risk to high-risk."

Build all three workflows today. Save the prompts in your Sales Project. Tomorrow they take 30 seconds, not 30 minutes.
---END-DAY-16---

---DAY-17---
**Subject:** Customer success + support day

CS team, this is your day. The job is part-relationship, part-detective. Claude is great at both.

*Three workflows to build:*

1. **QBR / health-check prep.** Paste account history, recent tickets, usage data. Ask: "Generate a 1-page QBR with: usage trends, risks, expansion opportunities, and the 3 things I should say first on the call."
2. **Support response drafting.** Paste an incoming question. Ask Claude to draft a response using the support knowledge in your Project. Always review before sending.
3. **Churn-risk diagnosis.** Paste account context. Ask: "Pre-mortem this account. If they churn in 90 days, what would the reason most likely be? What can I do this week to address it?"

*Important note:* Claude is not your client-facing voice. It's your drafting partner. Every external message gets your eyes on it before it sends.
---END-DAY-17---

---DAY-18---
**Subject:** Product + engineering day

Product + eng — today's for you. Two tracks: one for product (everyone), one for engineering (Premium-seat folks).

*Product workflows (everyone):*
1. **PRD drafting.** Drop in a problem statement + user research. Ask Claude to draft a PRD using our template (load the template into your Project).
2. **Spec review.** Paste a spec. Ask: "What's ambiguous? What edge cases are missing? What would an engineer reading this push back on?"
3. **User interview synthesis.** Paste 3–5 interview transcripts. Ask: "Find recurring patterns. What are the top 3 themes? Quote evidence."

*Engineering workflows (Premium seats):* For folks with Premium seats, you have **Claude Code** — Claude in your terminal/IDE that can read your repo, write code, run tests, and open PRs. We'll do a deeper Code session in Week 6. For now:
• Install: `npm install -g @anthropic-ai/claude-code`
• Run `claude` in a repo. Ask it to summarize the architecture. Get a feel for it.
• Reference: docs.claude.com/en/docs/claude-code (verify current install steps in case of changes)
---END-DAY-18---

---DAY-19---
**Subject:** Marketing + ops + leadership

Three functions, three workflows each. Pick yours.

*Marketing:*
1. **LinkedIn engine.** Paste a topic + your voice examples. Ask for 3 post variants. Pick one, refine, ship.
2. **Content repurposing.** Drop a long blog post or whitepaper. Ask for: 5 LinkedIn posts, 3 email subject lines, a 90-second video script.
3. **Inc 5000 / award applications.** Paste the prompt + our context. Get a first draft. (We literally drafted recent applications this way.)

*Ops + Finance:*
1. **Vendor evaluation.** Paste pricing docs / SOWs. Ask for an apples-to-apples comparison + the 3 questions you should ask before signing.
2. **Monthly reporting.** Drop in raw QuickBooks or analytics exports. Ask for an exec-ready summary with the 3 things leadership should notice.
3. **Policy drafting.** Need a new internal policy? Draft it with Claude, then have it red-team itself.

*Leadership:*
1. **Board prep.** Drop in metrics + recent context. Ask for: a 1-page narrative, the 5 most likely board questions, and recommended responses.
2. **Strategy stress-test.** Paste a strategic bet. Ask Claude to steelman, pre-mortem, and identify the 3 biggest assumptions.
3. **1:1 prep.** Paste recent context on a direct report. Ask for 3 things worth discussing this week.
---END-DAY-19---

---DAY-20---
**Subject:** Halfway! Week 4 share-out

You're officially halfway through. Look back at where you were on Day 1.

*Share in thread:*
• The most valuable workflow you built this week
• A prompt template worth stealing (paste it)
• One thing you want to learn in weeks 5–8

*Champion share-outs:* Our champions will each do a 5-minute demo Monday at the team meeting. Come ready to steal.

*What's next:* Weeks 5–6 are where things get fun. Skills (Claude becomes a specialist in our work). Cowork (Claude does multi-step work autonomously). Artifacts (Claude builds interactive things). This is where you start to feel the leverage.

Have a great weekend. 🎯
---END-DAY-20---

---DAY-21---
**Subject:** Champion demos + intro to Skills

Champion demos happening at team meeting today — be there.

*New concept this week: Skills.* You've heard me say "treat Claude like a smart new colleague." Skills are how you give that colleague a permanent handbook for a specific type of work.

A Skill is a folder of instructions Claude loads automatically when relevant. Claude already ships with built-in Skills for creating Word docs, Excel files, PowerPoints, and PDFs — that's why those outputs are so much better than vanilla chat.

*Why they matter for us:* Anyone here who repeatedly needs Claude to follow a TaxStatus-specific workflow (compliance review, board memo formatting, advisor-facing pitch deck, weekly partner report) can build a custom Skill so the team gets identical, high-quality output every time.

*Today:* Try this prompt:
> "Create a Word doc summarizing [your project]. Use a clean professional format with a title, exec summary, and key sections."

Notice it looks like a real document, not a markdown dump. That's the docx Skill working. Tomorrow: building our own.
---END-DAY-21---

---DAY-22---
**Subject:** Build a custom Skill (without coding)

You can build Skills in Claude itself. No code required.

*A starter Skill we'll all use:* "TaxStatus brand voice" — a Skill that loads our voice guidelines, do-not-say list, and approved positioning whenever Claude writes anything external-facing.

*How to build it (3 steps):*
1. In Claude, go to Settings → Capabilities → Skills.
2. Use the Skill Creator (it walks you through Q&A). Tell it: "I want a Skill that ensures Claude writes in TaxStatus's brand voice whenever the request is for external-facing content."
3. Paste in our voice guide and approved messaging. Save.

*Note:* Custom Skills on Team plan are individual to each user — they're not shared org-wide automatically. We'll build a TaxStatus Skill registry channel where people post their best Skills so others can install them too.

*Want sources?* Anthropic's docs on Skills: support.claude.com (search "Skills"). The product changes quickly — when in doubt, trust the in-app instructions.
---END-DAY-22---

---DAY-23---
**Subject:** Artifacts — Claude builds you tools

Have you noticed Claude sometimes produces a little app or interactive doc to the right of the chat? That's an **Artifact**.

*Artifacts let Claude build:*
• Interactive calculators (e.g., "compare two pricing scenarios")
• Drafts of documents you can edit live
• Simple web tools, dashboards, prototypes
• Diagrams, charts, slides
• Mini-apps that even call back to Claude itself for AI features

*Try one today:*
> "Build me a quick interactive tool where I can paste a prospect's firm name, AUM, and tax-planning focus, and it gives me a tailored 60-second pitch + three discovery questions. Make it look clean."

You'll get back a tool, in chat, that works. Use it. Refine it. Ship it.

*Why this matters:* You don't need engineering for everything anymore. If you can describe a useful tool clearly, Claude can build a first version. Most of our internal "I wish we had a thing for X" problems are now 10-minute problems.
---END-DAY-23---

---DAY-24---
**Subject:** Research mode for the deep questions

When you need real depth — a competitive analysis, a market scan, a regulatory question — turn on **Research**. Research mode runs multiple searches that build on each other, reads sources, and synthesizes a cited report.

*Use it for:*
• Competitive deep dives (e.g., "How is FP Alpha positioning itself this quarter? What's their pricing? What customers are switching?")
• Regulatory updates (e.g., "What's changed in CFPB guidance on data sharing in the last 6 months?")
• Industry scans (e.g., "Which WealthTech vendors raised in Q1? What did they raise on?")
• Prospect-firm deep research before a high-stakes meeting

*Caveats:*
• Research takes longer (minutes, not seconds). Worth it for high-stakes work.
• Always check citations. AI can still get specifics wrong.
• Treat Research output as a strong first draft of analysis, not a final answer.

*Today:* Run one Research task this week. Share the topic in thread.
---END-DAY-24---

---DAY-25---
**Subject:** Week 5 wins + a question

Week 5 done.

*Share-out:*
• One custom Skill you built or want to build
• One Artifact you made
• One Research output that genuinely changed how you're thinking about something

*A question for you:* Look at your last full work week. Walk through the day mentally. Where are the moments you didn't reach for Claude — but in hindsight, should have? Reply in thread.

Those moments are where we go next. Week 6 = autonomy. Cowork. Multi-step work. Less prompting, more goal-setting.
---END-DAY-25---

---DAY-26---
**Subject:** Meet Cowork — Claude that works on your computer

Up to now, you've been chatting. Cowork is different. You give Claude a goal, and it works on your machine — across your files, folders, and apps — until the goal is done.

*What it can do:*
• Organize messy folders (e.g., your Downloads, an attachments archive)
• Read a batch of source files and produce a synthesized report
• Move data between apps (Excel → PowerPoint, transcripts → CRM notes)
• Run on a schedule (Friday file cleanup, Monday meeting prep)
• Handle tasks that would take you 45 minutes of click-paste-format

*Today:* Open Cowork (in Claude's desktop app). Give it a small first task — something boring you'd rather not do. Watch it work.

*Caveat:* Cowork is agentic — it takes real action on your machine. Start with low-stakes tasks. Watch what it does. Approve actions when prompted. Build trust before handing off anything sensitive.
---END-DAY-26---

---DAY-27---
**Subject:** Three Cowork tasks worth handing off

Try at least one of these today.

**1. The Friday file dump:**
> "Look at my Downloads folder. Sort files by type into subfolders. Delete anything older than 30 days that isn't in [list of file types I want to keep]. Show me what you plan to do before doing it."

**2. Meeting prep:**
> "Look at my calendar for tomorrow. For each meeting, pull anything relevant from my recent Drive files, Slack mentions, and email. Build me a 1-page briefing doc per meeting."

**3. Synthesis from a folder:**
> "In folder [path] there are 12 meeting transcripts from prospect calls this quarter. Read all of them. Build me a one-page summary: top 5 objections we heard, top 3 features they wanted, and 3 representative quotes for each."

Pick one. Run it. Share the result in thread.
---END-DAY-27---

---DAY-28---
**Subject:** Engineering track — Claude Code in depth

Premium-seat engineers — today's for you. Everyone else, this is also useful context for how product/eng will move faster.

*What Claude Code is:* A command-line tool that gives Claude full access to your codebase. It can read files, write code, run tests, explore the repo, open PRs, use MCP servers, and handle multi-step development work autonomously.

*Three patterns worth learning this week:*
1. **The exploration pattern.** `claude` in a repo, then "explain how [feature] works end to end." Get oriented in unfamiliar code in 5 minutes instead of a day.
2. **The implementation pattern.** Write a clear spec (use chat-Claude to refine it first). Hand the spec to Claude Code. Review the PR carefully.
3. **The CLAUDE.md pattern.** Each repo gets a CLAUDE.md file at the root that tells Claude how this codebase is organized, what conventions matter, and how to test changes. Build it once, every future task is faster.

*Source:* Anthropic's docs: docs.claude.com/en/docs/claude-code. Verify install commands and current capabilities there — Claude Code ships changes often.
---END-DAY-28---

---DAY-29---
**Subject:** Scheduling and recurring work

Last big concept this week: making Claude work happen automatically.

*What you can automate:*
• Weekly: Claude pulls last week's wins from Slack and drafts a 1-paragraph update for leadership
• Monthly: Claude reads all your CS health-check notes and flags accounts trending down
• Daily: Claude pulls your calendar and drafts briefings for each meeting
• Quarterly: Claude reviews your prospect emails and identifies the top 5 dormant relationships worth re-engaging

*Where to set it up:* Cowork has scheduled tasks (in desktop). Routines (in Claude Code) extends this to run even when your laptop is closed. Check current availability in-app — this area is moving fast.

*Today's exercise:* Pick one recurring thing on your calendar. Even if you don't fully automate it this week, write the prompt as if you were going to. Share in thread.

*Fun fact:* The daily tips you're reading right now? Posted by a Routine. Eating our own dog food.
---END-DAY-29---

---DAY-30---
**Subject:** 6 weeks in. Take a breath.

Six weeks. Roughly 30 hours of practice for most of you. Look back.

*Self-assessment — on a 1–5 scale, where are you on each?*
1. I can write a good prompt without thinking about it.
2. I use Projects for my recurring work.
3. I've set up Connectors that save me real time.
4. I've built or installed at least one Skill.
5. I've handed off a multi-step task to Cowork.
6. Claude is part of how I work — not a tool I sometimes remember.

Reply in thread with your numbers (no judgment — this tells me where to focus weeks 7–8).

*What's next:* Last two weeks. We move from learning to shipping. Every person designs a personal Claude operating model. Leadership designs the long-term TaxStatus-wide operating model. We measure what changed.
---END-DAY-30---

---DAY-31---
**Subject:** Design your Claude operating model

This week is about turning practice into a habit.

*Your assignment: a personal "How I Work With Claude" doc.* One page. Cover these:

1. **Daily rituals.** When do you open Claude? Morning planning? Pre-meeting prep? End-of-day wrap?
2. **Default Projects.** Which Projects do you live in? What's loaded in each?
3. **Power workflows.** The 3–5 named workflows you now run regularly. With prompt templates.
4. **Guardrails.** What do you NOT use Claude for? (Sensitive data, certain client comms, etc.)
5. **Next 30 days.** One workflow you want to build but haven't yet.

Build this in a Claude Project so it's easy to update. Share in #claude-rollout when done. We'll harvest the best ones into a shared library.
---END-DAY-31---

---DAY-32---
**Subject:** The "first 15 minutes" ritual

A pattern from the people who get the most leverage from AI:

> The first 15 minutes of the workday is Claude time.

*A sample script:*
1. Open your daily-planning chat in your "My Workspace" Project.
2. "Here's my calendar today: [paste]. Here's what's on my mind: [dump it]. Help me prioritize. What am I missing? What's the one thing I should not skip?"
3. For your top meeting today, run a prep flow: "Brief me on [topic / person]. Pull from [relevant Project]. Give me 3 things to say and 1 question to ask."
4. For your top deliverable today, get a first draft going. Don't finish it — start it.

Now your day has direction, your hard meeting has prep, and your big deliverable has momentum. By 9:15.

*Try it tomorrow.* Report back Thursday on whether it changed your day.
---END-DAY-32---

---DAY-33---
**Subject:** When NOT to use Claude

A more sophisticated view of the tool: knowing when to put it down.

*Bad uses:*
• **High-stakes client communication you should be writing yourself.** A condolence note, a partnership ask, a hard conversation. Claude can help you think — but the voice should be yours.
• **Decisions where you're looking for validation.** If you already know the answer and just want someone to agree, Claude will oblige. Don't use that as confirmation.
• **Anything with sensitive data outside our guardrails.** SSNs, raw transcripts, client account numbers — never.
• **Tasks where the friction IS the value.** Some thinking has to happen in your own head. Don't outsource the parts that make you good at your job.
• **Time-sensitive specialized knowledge where you can't verify.** When Claude could be wrong and you can't check, slow down.

*Today:* Add a "What I do NOT use Claude for" section to your personal operating model doc.
---END-DAY-33---

---DAY-34---
**Subject:** Cross-pollinate — steal from each other

A reminder of why we did this in Slack and not as private trainings:

The best Claude prompts in the company are sitting in someone else's head right now. Today we get them out.

*Today:*
1. Reply in thread with your single best prompt template. The one you reach for over and over.
2. Read other people's. Steal at least one. Use it tomorrow.
3. Drop a 👀 emoji on prompts that surprise you.

After this thread, I'll harvest the top 20 into our shared Project. That becomes our internal prompt library, version 1.
---END-DAY-34---

---DAY-35---
**Subject:** Week 7 wins

You should have:
• A written personal operating model doc
• A morning ritual (or a deliberate decision not to)
• A clearer view of when NOT to use Claude
• A few stolen prompts from teammates

*Share-out — reply with:*
• Your personal operating model doc (link or paste)
• One workflow that's become so reflexive you almost forgot you're using Claude for it
• One open question heading into the final week

*Heads up:* Next week is the final week. We'll cover: measurement (what changed?), the long-term TaxStatus operating model, AI literacy beyond Claude, and graduation. Make it count.
---END-DAY-35---

---DAY-36---
**Subject:** Measurement — what actually changed?

No rollout is real until you measure it.

*Today: a self-audit. Reply in thread with three answers. Be honest.*

1. **Time saved.** What's one task per week that used to take you 30+ minutes and now takes 5? Roughly how much time per week has Claude given you back?
2. **Quality lifted.** Where is the output better — not just faster — because Claude is involved?
3. **Things you stopped doing.** What's a task or decision you used to procrastinate on that you now actually do, because Claude lowered the activation cost?

*Why this matters:* I want to take the team data to leadership (and to the board, where relevant) to anchor the next phase of investment. Real numbers from real workflows are more compelling than vendor case studies.
---END-DAY-36---

---DAY-37---
**Subject:** AI literacy beyond Claude

Claude is our standard. That doesn't mean we ignore the rest of the field.

*Things worth knowing:*
• **Model choice matters.** Inside Claude, Opus is the most capable model; Sonnet is the workhorse; Haiku is the fast/cheap option. For most daily work, the defaults are fine. For high-stakes reasoning, switch to Opus.
• **Other AI tools have legitimate use cases.** ChatGPT, Gemini, Perplexity, others. If a teammate or customer mentions them, we engage with curiosity, not defensiveness.
• **AI changes the WealthTech competitive landscape.** Holistiplan, FP Alpha, TaxPlanIQ are all building AI features. So are advisors evaluating us. Knowing how AI works is now a job requirement, not a bonus.
• **Hallucinations are real.** Claude is the most reliable of the major models on this, in my experience — but no model is immune. Verify anything important.
• **The field moves fast.** What's state-of-the-art today is the baseline in 6 months. Stay curious.

*Reading list:* Optional but recommended — Anthropic's blog (anthropic.com/news), the "How to use Claude well" support articles (support.claude.com).
---END-DAY-37---

---DAY-38---
**Subject:** The TaxStatus operating model

Leadership-level post. Sharing publicly because everyone should know how we're going to operate from here.

*Going forward at TaxStatus:*
1. **Claude is our default AI tool.** Standard seats for everyone; Premium seats for engineers and others who need Claude Code.
2. **AI literacy is part of every role.** New hires get this 8-week curriculum (compressed) as part of onboarding.
3. **The shared TaxStatus Project is maintained by leadership.** Updated quarterly. Your function's Project is maintained by your function lead.
4. **Sensitive data rules are non-negotiable.** §7216, FCRA, client data policy applies to Claude same as anywhere else. When in doubt, ask compliance.
5. **The #claude-wins channel stays open.** Share what you ship.
6. **Prompt library lives in the shared Project.** Contributions welcome. Theft encouraged.
7. **Quarterly check-ins.** Once per quarter, we revisit: what's changed in the product, what new workflows are worth adopting, what to retire.

This is now how we work.
---END-DAY-38---

---DAY-39---
**Subject:** One more thing — how to keep learning

You're going to be using Claude for years. The product is going to change a lot. Here's how to stay current without it eating your life.

*Low-effort, high-yield habits:*
• **Read the in-app release notes when you see them.** They're short.
• **Anthropic's news page (anthropic.com/news)** — skim monthly.
• **Follow 2–3 voices, not 20.** Engineering blogs from Anthropic, maybe Simon Willison's blog, maybe one or two practitioners in our space. Resist the urge to subscribe to everything.
• **When you find a new feature, try it once that day.** If it sticks, integrate. If it doesn't, move on.
• **Ask Claude what's new.** Genuinely — "What's new in Claude in the last month I might have missed?" Then verify.

*When you're stuck:* Drop questions in #tips-claude. The community is the documentation.
---END-DAY-39---

---DAY-40---
**Subject:** 🎓 Graduation

Eight weeks. Forty workdays. You did it.

*Where you started:* "What is Claude?" → "Claude is part of how I work."

*What's actually different.* A few things you couldn't do on Day 1 that you can do now:
• Get a meaningful first draft of anything in 90 seconds
• Walk into a high-stakes meeting fully briefed in 15 minutes
• Build internal tools without engineering involvement
• Hand off entire multi-step tasks and walk away
• Pre-mortem decisions in 10 minutes instead of skipping the step
• Synthesize hours of meeting transcripts in minutes

That's the actual TaxStatus advantage now. Not "we have AI." Everyone has AI. **We use it fluently, in regulated work, with judgment.**

*Final share-out — reply in thread:*
• One thing Claude does for you now that you'd hate to give up
• One person here who helped you most this rollout (shout-out)
• One bet about how our work will be different in 6 months

*And...* thank you. Genuinely. Adopting new tools is hard, especially when it's on top of the day job. You showed up.

Now let's go build the most AI-fluent company in WealthTech. 🚀
---END-DAY-40---
