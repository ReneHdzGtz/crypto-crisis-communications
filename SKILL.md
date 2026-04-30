---
version: 1.0.0
name: crypto-crisis-communications
description: >
  Expert system for managing communications during crises in Web3 and crypto environments.
  Use this skill whenever the user needs to respond to a smart contract exploit, security
  incident, rug pull accusations, FUD campaigns, negative viral content, governance attack,
  team controversy, or any reputational crisis affecting a crypto project, protocol, or DAO.
  Also trigger for phrases like "we got hacked", "exploit on our protocol", "FUD spreading",
  "community is panicking", "negative news", "crisis response", "how do we respond",
  "our token is crashing", "bad press", "controversy", "our community is angry",
  "someone is spreading misinformation", "protocol vulnerability disclosed", or any situation
  requiring urgent or sensitive communication management in a Web3/crypto context.
---

# Crypto Crisis Communications Skill
**For:** Protocol marketing leads, DAO communication teams, Web3 founders, community managers  
**Philosophy:** In crypto, your response speed and honesty matter more than the incident itself. Silence kills trust. Transparency rebuilds it.

---

## CRITICAL: Crisis Triage First

**Before executing any module, ask:**
1. What happened? (technical, community, financial, legal, reputational)
2. When did it happen / when was it discovered?
3. Is it ongoing or contained?
4. What do you know for certain vs. what is still uncertain?
5. What platforms are the conversation happening on?

**Then classify and route:**

| Crisis Type | Severity | Module |
|---|---|---|
| Smart contract exploit / hack | 🔴 Critical | [MODULE 1: Security Incident Response] |
| FUD / misinformation campaign | 🟡 High | [MODULE 2: FUD & Misinformation] |
| Token price crash / community panic | 🟡 High | [MODULE 3: Market Crisis Response] |
| Governance attack / hostile proposal | 🟡 High | [MODULE 4: Governance Crisis] |
| Team controversy / personal scandal | 🟠 High | [MODULE 5: Reputational Crisis] |
| Negative press / media attack | 🟠 Medium | [MODULE 6: Media Crisis] |
| Community revolt / mod controversy | 🟡 Medium | [MODULE 7: Community Conflict] |
| Post-crisis recovery plan | Any | [MODULE 8: Recovery & Trust Rebuild] |

---

## MODULE 1 — Security Incident Response (Exploit / Hack)

**Trigger:** Smart contract was exploited, funds were drained, vulnerability was found, or protocol was attacked.

### The First 2 Hours Are Everything

**Minute 0–15: Internal lockdown**
- [ ] Confirm the incident is real (on-chain data, wallet drains, team reports)
- [ ] Pause all marketing/community activity immediately
- [ ] Alert all team members — no one tweets independently until cleared
- [ ] Contact security team / auditors / white-hat contacts
- [ ] Screenshot and archive all on-chain evidence

**Minute 15–30: First public statement**
Do NOT wait until you have all the answers. Post a "we are aware" statement first.

```
FIRST STATEMENT TEMPLATE:
──────────────────────────
We are aware of an issue affecting [PROTOCOL].

We are actively investigating. No further actions are needed from users at this time.

We will provide a full update within [X hours].

[Link to official status page or Discord channel for updates]
```

**What NOT to do in the first 30 minutes:**
- ❌ Minimize the incident ("it's just a small bug")
- ❌ Speculate publicly about the cause
- ❌ Blame users, auditors, or third parties before investigation is complete
- ❌ Stay silent — silence in crypto reads as "they're hiding something"
- ❌ Delete previous posts or try to hide the incident
- ❌ Let team members post individual takes on their personal accounts

**Minute 30–60: Action statement**

```
ACTION STATEMENT TEMPLATE:
───────────────────────────
UPDATE on [Protocol] security incident — [Time] UTC

What we know:
• [Confirmed fact 1 — on-chain if possible]
• [Confirmed fact 2]
• [Estimated impact — funds at risk or already lost]

What we're doing:
• [Action 1: e.g., "Paused deposits and withdrawals"]
• [Action 2: e.g., "Engaged [security firm] to investigate"]
• [Action 3: e.g., "Deployed a contract patch — pending audit"]

What we don't know yet:
• [Uncertainty 1 — be specific about what's still being investigated]

Next update: [specific time, not "soon"]

If you have funds in [Protocol], [specific instruction — withdraw / do not interact / hold]

Incident report will be published within [X hours/days].
```

### Hour 2–24: Ongoing Management
- Post updates every 2–4 hours even if there's no new information ("Still investigating — no new findings yet. Next update at [time].")
- Designate one spokesperson — no multiple voices giving conflicting info
- Open a dedicated #incident channel in Discord for Q&A — keeps main channels cleaner
- Do NOT engage with trolls, accusers, or price speculators during active incident

### The Full Post-Mortem (24–72 hours after containment)

```
POST-MORTEM REPORT — [Protocol Name] Security Incident
────────────────────────────────────────────────────────
Date: [incident date] | Published: [report date]

EXECUTIVE SUMMARY:
[3–4 sentences: what happened, scope of impact, current status]

TIMELINE:
[HH:MM UTC] — [Event]
[HH:MM UTC] — [Event]
...

ROOT CAUSE:
[Technical explanation — be specific. Vague explanations signal cover-up.]

IMPACT:
• Funds affected: [$X / X tokens]
• Users affected: [X wallets / accounts]
• Systems affected: [specific contracts/components]

WHAT WE DID:
[Chronological response actions with timestamps]

RECOVERY PLAN:
• [How affected users will be compensated, if at all]
• [Timeline for protocol resumption]
• [Security improvements being implemented]

PREVENTION MEASURES:
• [What we're changing to prevent recurrence]
• [Additional audits or monitoring being added]

ACKNOWLEDGMENTS:
[Thank white-hats, security researchers, or community members who helped]

We take full responsibility for [specific aspects].
[If appropriate: what we could have done differently]

Contact for affected users: [email or Discord channel]
```

---

## MODULE 2 — FUD & Misinformation Response

**Trigger:** False or misleading information is spreading about the project, and community is reacting to it.

### Step 1: Assess Before Responding

**Do not respond immediately.** Ask:
- Is this claim actually false, or is it uncomfortable truth?
- What is the source — troll, competitor, credible voice, or media?
- Is this getting traction (retweets, engagement) or is it contained?
- Does engaging amplify it or defuse it?

**Rule:** Responding to small FUD can make it bigger. Only respond when:
1. The claim is specific and factually incorrect
2. It's gaining traction (>500 engagements or picked up by influencers)
3. You have clear evidence to counter it

### Step 2: FUD Response Framework

**Type A — Factual Error (wrong numbers, fake screenshot, outdated info):**

```
FACTUAL CORRECTION TEMPLATE:
──────────────────────────────
We've seen [brief description of the claim] spreading. Let's set the record straight.

[CLAIM]: "[Quote or summary of false claim]"
[FACT]: "[Accurate information with verifiable source — link to on-chain data, doc, or announcement]"

[Optional: Brief explanation of why this claim may have originated]

If you have questions, reach out at [contact] or join [Discord/Telegram].
```

**Type B — Deliberate Smear / Competitor Attack:**

```
SMEAR RESPONSE TEMPLATE:
─────────────────────────
We're aware of [vague reference to campaign, don't amplify by naming it].

Rather than engage with bad-faith accusations, we'll let our work speak:
• [Recent achievement or verifiable metric]
• [Link to audit / transparency report]
• [Link to on-chain data or community vote]

We've always been transparent about [topic of accusation]. Here's the full context: [link]

The team is focused on building. That's where our energy stays.
```

**Type C — Influencer or KOL Spreading FUD:**
- If small influencer (<50K): ignore unless it gains traction
- If mid-tier (50K–500K): DM directly with factual correction — offer context privately first
- If large (500K+): Public response required, but factual and non-aggressive
- Never: get into a Twitter fight, name-call, or threaten legal action publicly

### Step 3: Community Briefing
Once the FUD is addressed publicly, post in Discord/Telegram:

```
Hey everyone — you may have seen [brief description] circulating.

Here's what's actually true: [facts + links]

The community team is monitoring this. No action needed from you.

If you see it spreading, you can share [link to official statement].
Thank you for trusting us to address it directly.
```

---

## MODULE 3 — Market Crisis Response (Token Crash / Panic)

**Trigger:** Token price is crashing, community is panicking, or a macroeconomic event is causing fear.

### What Never to Do During a Price Crash:
- ❌ Comment on price ("we believe in our project's long-term value" = "we know the price is tanking")
- ❌ Post "buy the dip" or anything that reads as shilling
- ❌ Go silent (silence = founders dumped and left)
- ❌ Blame macro conditions exclusively
- ❌ Make promises about price recovery

### What Actually Works:
- ✅ Acknowledge the market environment without commenting on price
- ✅ Post a development update — show you're still building
- ✅ Be visible and present in community channels
- ✅ Share upcoming milestones — shift focus from price to roadmap
- ✅ Address specific FUD or concerns that accompany the panic

### Community Message During Market Panic:

```
To the [Protocol] community:

Markets are moving. We see you, and we hear the concerns.

What we know doesn't change with price:
• [Milestone or development happening right now]
• [Team is full and committed — names/roles if helpful]
• [On-chain metric that shows real activity — TVL, transactions, active users]

What we're focused on:
• [Upcoming deliverable 1]
• [Upcoming deliverable 2]

We won't tell you what to do with your assets. We'll just keep building.

[Founder/Team name]
[Date and time — shows this is current, not a scheduled post]
```

---

## MODULE 4 — Governance Crisis

**Trigger:** Malicious governance proposal, hostile takeover attempt, governance vote being gamed, or community split on major decision.

### Immediate Response Framework

**Hour 1:**
- [ ] Announce you're aware of the proposal/situation in official channels
- [ ] Pause or extend voting period if technically possible and within governance rules
- [ ] Publish a neutral summary of what's happening (not your opinion yet)
- [ ] Invite structured discussion — provide a dedicated thread or channel

**Governance Communication Template:**

```
[GOVERNANCE ALERT] — [Proposal Number/Name]

We want to make sure the community has full context on [proposal].

WHAT IS BEING PROPOSED:
[Neutral, factual summary — no editorial yet]

WHAT THIS WOULD MEAN:
[Impact on protocol, treasury, users — factual]

OUR CONCERN / SUPPORT (if applicable):
[If the team has a position, state it clearly with reasoning]

WHAT WE'RE ASKING:
• Read the full proposal: [link]
• Join the discussion: [link to forum/Discord thread]
• Vote by [date and time]: [Snapshot link]

This is the community's decision. We're providing context to help you decide.
```

### After Contentious Vote
Whether the team's preferred outcome wins or loses:

```
The community has voted [for/against] [proposal].

[If team supported it]: Thank you for your trust. Here's how we implement it: [next steps]
[If team opposed it]: We respect the outcome. Here's how we move forward together: [next steps]

Democracy in DAOs means accepting outcomes we disagree with. We remain committed to the community.
```

---

## MODULE 5 — Reputational Crisis (Team Controversy)

**Trigger:** Team member involved in scandal, doxxed, or past behavior surfaced.

### Key Principles:
- **Acknowledge fast, investigate before making claims**
- **The team is responsible for its members — don't distance too quickly**
- **If the accusation is verified: accountability is the only recovery path**
- **If the accusation is unverified: due process, not public trial**

### Response Template (verified incident):

```
We have seen the reports regarding [role, not name unless public].

We take this seriously. Here is what we are doing:

1. [Specific action: e.g., "The team member has been removed from their role pending investigation"]
2. [Structural change: e.g., "We are reviewing our onboarding and vetting process"]
3. [Affected parties: e.g., "Anyone affected can reach us at [contact]"]

We understand this shakes trust. We are committed to [specific commitment].

Full update by [specific date].
```

---

## MODULE 6 — Media Crisis

**Trigger:** Negative press article, investigative piece, or media narrative spreading about the project.

### Media Response Ladder

**Level 1 — Minor blog post, small outlet, low traction:**
- Don't respond publicly
- Optional: DM the journalist with a factual correction
- Monitor for spread

**Level 2 — Mid-tier outlet, growing traction:**
- Prepare a public response (use factual correction template from Module 2)
- Request right of reply from the publication
- Brief key community members / moderators with talking points

**Level 3 — Major outlet (CoinDesk, Bloomberg, Reuters, WSJ):**
- Respond publicly within 4 hours
- Designate a spokesperson — founder or senior team member
- Post response on official channels and offer interview/follow-up
- Legal review before posting (if allegations involve fraud, regulatory matters)

### Official Statement Template for Press:

```
[Protocol Name] Response to [Publication] Article — [Date]

We have reviewed the [Publication] article published on [date].

[Point 1]: [Factual correction or clarification with source]
[Point 2]: [Context that was missing from the article]
[Point 3]: [What we are doing differently or have already done]

We are committed to transparency and welcome further questions at [press@protocol.com].

[Founder name], [Title]
```

---

## MODULE 7 — Community Conflict

**Trigger:** Moderators acting badly, community is divided, internal drama escalating publicly.

### De-escalation Sequence

1. **Acknowledge privately first** — DM key community leaders before posting publicly
2. **Don't take sides publicly** until you have full context
3. **Create a cooling-off channel or thread** for structured discussion
4. **Post community values statement** — remind community of shared purpose
5. **If a moderator is the problem:** remove them from public role before addressing publicly

### Community Reset Message:

```
To the [Protocol] community:

We've seen tensions rise around [topic]. We want to address this directly.

[Brief, honest summary of what happened — don't spin it]

We should have [what the team could have done better].

Going forward:
• [Specific change 1]
• [Specific change 2]

The community we're building is worth this work. Thank you for holding us accountable.

[Team]
```

---

## MODULE 8 — Recovery & Trust Rebuild

**Trigger:** Post-crisis, team wants to rebuild community trust and protocol reputation.

### 30-Day Trust Recovery Plan

**Week 1 — Radical Transparency:**
- Daily updates in Discord/Telegram (even if nothing new)
- Publish all relevant data publicly (treasury, on-chain metrics, team activity)
- Founder/team visible in community every day — answer questions personally

**Week 2 — Accountability Demonstration:**
- Publish post-mortem or full incident report (if not done during crisis)
- Share what has changed structurally (new audits, new processes, team changes)
- Host a community AMA — unfiltered questions from the community

**Week 3 — Proof of Work:**
- Ship something tangible: update, feature, integration, or fix
- Acknowledge community members who stayed during the crisis
- Invite community feedback on the recovery process

**Week 4 — Forward Focus:**
- Announce next milestones publicly
- Shift narrative from incident to roadmap
- Recognize community builders and contributors publicly

### Metrics to Track During Recovery:
- Discord/Telegram active user count (daily)
- Token holder count (are people leaving?)
- Sentiment tracking (manual or tool-based)
- Media coverage tone
- Developer activity (GitHub commits, new builders asking questions)

---

## General Quality Rules

1. **Speed beats polish in a crisis.** A fast, imperfect response beats a slow, perfect one.
2. **Say what you know AND what you don't know.** Admitting uncertainty builds more trust than false confidence.
3. **Never delete.** In blockchain, nothing is deleted. Screenshots exist. Deletion looks like a cover-up.
4. **One voice per crisis.** Multiple team members posting contradictory takes destroys credibility instantly.
5. **Don't punish the community for the crisis.** They are your allies, not your problem.
6. **Lawyers slow things down — sometimes that's the right call.** When regulatory matters are involved, get legal review before posting. For everything else, move fast.
7. **The cover-up is always worse than the crime.** In crypto, transparency is the only brand strategy that survives long-term.

---

*Crypto Crisis Communications Skill v1.0*  
*Built for protocol marketing leads and DAO teams who need to communicate clearly and fast when things go wrong.*
