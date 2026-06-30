# Workflow Templates — The Boardroom

> **Key takeaway:** A workflow is a repeatable process you write once and use forever. Claude follows it step by step so you get consistent results without reinventing the wheel each time.

---

## What Is a Workflow?

A workflow is a step-by-step SOP (Standard Operating Procedure) written in Markdown. It tells Claude — or anyone — exactly how to accomplish a specific task.

If you've done Lesson 1.1.2 (The WAT Framework), workflows are the **first layer**: the instructions that drive everything. The Agent (Claude) reads the workflow, decides what to do, and executes the tools in the right order.

**The format is simple:**
1. **Objective** — What this accomplishes
2. **Required Inputs** — What you need before starting
3. **Tools Used** — What platforms, scripts, or services are involved
4. **Process Steps** — The sequence of operations
5. **Expected Outputs** — What gets delivered and where
6. **Edge Cases** — Known issues, things to watch for

You can use these workflows in two ways:
- **Claude.ai:** Paste the workflow into a conversation and tell Claude to follow it
- **Claude Code:** Save the workflow as a file in your `workflows/` directory — Claude Code reads it and executes the steps

---

## How to Use These Templates

1. Pick the workflow closest to what you need
2. Copy the entire code block
3. Replace everything in `[BRACKETS]` with your specifics
4. Save it as a `.md` file or paste it into Claude

Once it's written, you use it over and over. That's the point — you systematize the work once, then it runs consistently every time.

---

## Template 1: Content Creation Workflow

**From idea to published content + social posts.**

```markdown
# Content Creation Workflow

## Objective
Take a content topic from idea to published blog post with accompanying social media posts. Produce consistent, on-brand content without starting from scratch each time.

## Required Inputs
- Topic or working title: [TOPIC]
- Target keyword(s): [PRIMARY KEYWORD, SECONDARY KEYWORDS]
- Target audience: [WHO THIS IS FOR — e.g., "small business owners looking to automate"]
- Target word count: [WORD COUNT — e.g., 1,500-2,000]
- Brand voice reference: [LINK TO BRAND GUIDE OR SHORT DESCRIPTION — e.g., "professional but conversational, no jargon"]
- Platform(s) for social posts: [PLATFORMS — e.g., LinkedIn, Instagram, Twitter]

## Tools Used
- Claude (drafting, editing, repurposing)
- [YOUR CMS — e.g., WordPress, Webflow, Ghost] (publishing)
- [YOUR SOCIAL TOOL — e.g., Buffer, Hootsuite, manual posting] (scheduling)
- [YOUR SEO TOOL — e.g., Ahrefs, SEMrush, Google Search Console] (keyword validation)

## Process Steps
1. **Research**: Search the target keyword. Read the top 5 results. Note what they cover and what they miss.
2. **Outline**: Create a structured outline with H2 and H3 headings. Include the angle that differentiates your piece from existing content.
3. **Draft**: Write the full post following the outline. Include:
   - Hook in the first 2 sentences
   - Subheadings every 200-300 words
   - At least one real example or case study
   - Clear CTA at the end
4. **Edit**: Review for brand voice, factual accuracy, and flow. Cut anything that doesn't earn its place.
5. **SEO Check**: Verify the target keyword appears in the title, first paragraph, at least 2 subheadings, and the meta description.
6. **Social Posts**: Repurpose the blog post into:
   - 1 LinkedIn post (key insight + link)
   - 1 Instagram caption (value-first, CTA to bio link)
   - 3 tweets/threads (pull the best points)
7. **Publish**: Post to CMS, schedule social posts, share in relevant communities.

## Expected Outputs
- 1 published blog post (in CMS)
- 1 LinkedIn post (scheduled)
- 1 Instagram caption (scheduled)
- 3 tweets (scheduled)
- Meta title and description (in CMS)

## Edge Cases & Learnings
- If the topic is too broad, narrow to a specific angle before outlining
- If you can't find a differentiated angle, pick a different topic — don't publish commodity content
- If social posts feel forced, the blog post may need a stronger core insight
- [ADD YOUR OWN LEARNINGS HERE AS YOU USE THIS WORKFLOW]
```

---

## Template 2: Client Onboarding Workflow

**From signed contract to project kickoff — nothing falls through the cracks.**

```markdown
# Client Onboarding Workflow

## Objective
Systematically onboard a new client from signed contract to project kickoff. Ensure every step is completed, every expectation is set, and the client feels confident they made the right choice.

## Required Inputs
- Client name and contact info: [CLIENT NAME, EMAIL, PHONE]
- Service purchased: [SERVICE OR PACKAGE NAME]
- Contract/SOW details: [LINK OR SUMMARY — scope, timeline, payment terms]
- Project start date: [DATE]
- Internal team assigned: [TEAM MEMBER(S) OR "SOLO"]

## Tools Used
- [YOUR EMAIL TOOL — e.g., Gmail, Outlook]
- [YOUR PROJECT MANAGEMENT TOOL — e.g., Notion, Asana, Monday, Trello]
- [YOUR FILE STORAGE — e.g., Google Drive, Dropbox]
- [YOUR CALENDAR TOOL — e.g., Google Calendar, Calendly]
- [YOUR INVOICING TOOL — e.g., Stripe, QuickBooks, FreshBooks]

## Process Steps
1. **Welcome Email** (Day 0 — same day contract is signed):
   - Send personalized welcome email with:
     - Confirmation of what they purchased
     - What to expect in the first week
     - Link to intake form/questionnaire
     - Next steps with dates
2. **Create Project Workspace** (Day 0-1):
   - Set up project in [PM TOOL] with milestones and deadlines
   - Create shared folder in [FILE STORAGE] with:
     - Signed contract
     - Brand assets (if applicable)
     - Project brief
3. **Send Intake Form** (Day 0-1):
   - Send questionnaire covering:
     - Business goals and priorities
     - Logins and access needed
     - Brand guidelines, assets, existing materials
     - Communication preferences (email, Slack, phone)
     - Key contacts and decision-makers
4. **Review Intake Responses** (Day 2-3):
   - Flag any missing information
   - Follow up on incomplete items
   - Update project brief with client inputs
5. **Schedule Kickoff Call** (Day 3-5):
   - Book 30-60 min kickoff meeting
   - Send calendar invite with agenda:
     - Introductions (if team involved)
     - Review scope and timeline
     - Confirm communication cadence
     - Address questions
     - Agree on first deliverable and deadline
6. **Kickoff Call** (Day 5-7):
   - Run the meeting from the agenda
   - Document decisions and action items
   - Send recap email within 24 hours
7. **Begin Work** (Day 7+):
   - Start first deliverable per timeline
   - Set up recurring check-in (weekly or biweekly)
   - Send first invoice per payment terms

## Expected Outputs
- Welcome email sent
- Project workspace created (PM tool + file storage)
- Intake form sent, received, and reviewed
- Kickoff call completed with recap sent
- First deliverable in progress
- Recurring check-in scheduled

## Edge Cases & Learnings
- If client doesn't complete intake form within 3 days, follow up by phone — email gets buried
- If client wants to change scope before kickoff, document it as a change order before proceeding
- If multiple stakeholders are involved, identify the single decision-maker early
- [ADD YOUR OWN LEARNINGS HERE]
```

---

## Template 3: Lead Generation & Follow-Up Workflow

**From lead capture to closed deal — no lead left behind.**

```markdown
# Lead Generation & Follow-Up Workflow

## Objective
Systematically capture, qualify, nurture, and convert leads into paying clients. Ensure timely follow-up so no opportunity is lost to slow response.

## Required Inputs
- Lead source: [WHERE LEADS COME FROM — e.g., website form, Instagram DMs, referrals, Skool, cold outreach]
- Service/offer: [WHAT YOU'RE SELLING]
- Ideal client profile: [WHO YOUR BEST CLIENTS ARE — industry, size, budget, pain points]
- Response time target: [e.g., "respond within 2 hours during business hours"]

## Tools Used
- [YOUR CRM — e.g., HubSpot, Pipedrive, Notion, Google Sheets]
- [YOUR EMAIL TOOL — e.g., Gmail]
- [YOUR CALENDAR TOOL — e.g., Calendly]
- Claude (drafting personalized responses, proposals)

## Process Steps
1. **Capture**: When a lead comes in, log it in [CRM] with:
   - Name, email, phone
   - Source (how they found you)
   - What they asked about
   - Date received
2. **Qualify** (within 2 hours):
   - Does this match your ideal client profile?
   - Can you deliver what they need?
   - Is the budget realistic?
   - Tag as: Hot (ready to buy), Warm (interested, needs nurture), or Cold (not a fit)
3. **Initial Response** (within 2 hours for Hot, same day for Warm):
   - Acknowledge their interest
   - Ask 2-3 qualifying questions
   - Suggest a discovery call with calendar link
4. **Discovery Call** (within 3-5 days of initial contact):
   - Understand their problem, goals, timeline, budget
   - Explain your approach and what results look like
   - If it's a fit, tell them you'll send a proposal
   - If it's not a fit, refer them to someone who can help (builds goodwill)
5. **Proposal** (within 48 hours of discovery call):
   - Use Claude to draft from your discovery notes
   - Include: scope, timeline, investment, next steps
   - Send with a note: "Happy to walk through this on a quick call if helpful"
6. **Follow-Up Sequence** (if no response to proposal):
   - Day 3: "Just checking in — any questions about the proposal?"
   - Day 7: Add value — share a relevant insight, article, or example
   - Day 14: "Want to revisit this when timing is better? No pressure."
   - Day 30: Final follow-up, then move to Cold
7. **Close**: Once accepted:
   - Send contract/invoice
   - Begin onboarding workflow (see Template 2)

## Expected Outputs
- Every lead logged in CRM with status
- Response sent within target time
- Discovery calls booked for qualified leads
- Proposals sent within 48 hours
- Follow-up sequence completed (no lead forgotten)

## Edge Cases & Learnings
- If a lead ghosts after the discovery call, the proposal may be too high or the pain isn't urgent enough — note this pattern
- If most leads come from one source, double down on that channel
- If conversion rate drops below [YOUR TARGET — e.g., 20%], review your qualifying criteria
- [ADD YOUR OWN LEARNINGS HERE]
```

---

## Template 4: Weekly Business Review Workflow

**From raw numbers to clear decisions — every week.**

```markdown
# Weekly Business Review Workflow

## Objective
Review business performance weekly. Identify what's working, what's not, and decide on priorities for the next week. Make decisions from data, not gut feeling.

## Required Inputs
- Revenue data for the week: [SOURCE — e.g., Stripe dashboard, QuickBooks, bank account]
- Expense data: [SOURCE — e.g., credit card statements, accounting software]
- Pipeline/leads data: [SOURCE — e.g., CRM, email, DMs]
- Key metrics: [WHAT YOU TRACK — e.g., revenue, leads, close rate, website traffic, social followers]
- Last week's priorities: [WHERE YOU TRACK THESE — e.g., Notion, Google Doc]

## Tools Used
- [YOUR ACCOUNTING TOOL — e.g., QuickBooks, Wave, spreadsheet]
- [YOUR CRM — e.g., HubSpot, Notion]
- [YOUR ANALYTICS — e.g., Google Analytics, social platform insights]
- Claude (analysis and recommendations)

## Process Steps
1. **Pull Numbers** (15 min):
   - This week's revenue (total + by source)
   - This week's expenses (total + by category)
   - Net profit/loss
   - Pipeline: new leads, proposals sent, deals closed
   - Key platform metrics (website traffic, social engagement, email opens)
2. **Compare to Targets** (10 min):
   - Revenue vs. monthly target (are you on pace?)
   - Lead flow vs. target
   - Compare to same week last month
3. **Analyze with Claude** (10 min):
   - Paste your numbers into Claude and ask:
     "Here are my numbers for the week. What trends do you see? What should I be concerned about? What's working?"
   - Review Claude's analysis — does it match your intuition?
4. **Review Last Week's Priorities** (5 min):
   - What got done? What didn't?
   - If something didn't get done, why? (Wrong priority? No time? Blocked?)
5. **Set Next Week's Priorities** (10 min):
   - Pick 3-5 priorities for the coming week
   - Each priority should be specific and completable
   - At least one should directly drive revenue
6. **Document** (5 min):
   - Record the review in [YOUR TOOL]
   - Format: Date | Revenue | Expenses | Net | Key Wins | Key Issues | Next Week's Priorities

## Expected Outputs
- Weekly review document (stored in [YOUR TOOL])
- Updated priority list for the coming week
- Any red flags identified with action items

## Edge Cases & Learnings
- If you skip a week, the next review gets harder — don't skip
- If the same issue shows up 3 weeks in a row, it's not an issue — it's a systemic problem that needs a real fix
- If revenue is on track but profit isn't, look at expenses line by line
- [ADD YOUR OWN LEARNINGS HERE]
```

---

## Template 5: Deal Analysis Workflow (Real Estate)

**From listing to go/no-go decision — data-driven, every time.**

```markdown
# Deal Analysis Workflow

## Objective
Analyze a potential real estate deal systematically. Determine whether the numbers work, identify risks, and make a clear go/no-go recommendation. Remove emotion from the decision.

## Required Inputs
- Property address: [ADDRESS]
- Asking price: [PRICE]
- Property details: [BEDS, BATHS, SQ FT, YEAR BUILT, LOT SIZE]
- Strategy: [AIRBNB, LONG-TERM RENTAL, BRRRR, FLIP, HOUSE HACK]
- Financing assumptions: [DOWN PAYMENT %, INTEREST RATE, LOAN TERM]
- Market data: [COMPARABLE SALES, RENTAL COMPS, OCCUPANCY RATES FOR AREA]

## Tools Used
- [YOUR ANALYSIS TOOL — e.g., BiggerPockets Calculator, spreadsheet, DealCheck]
- [YOUR COMPS SOURCE — e.g., Zillow, Redfin, MLS, AirDNA]
- Claude (analysis, memo drafting)
- [YOUR LENDER CONTACT — for pre-approval or rate quotes]

## Process Steps
1. **Gather Property Data** (15 min):
   - Pull listing details, photos, and disclosure documents
   - Note condition issues visible in photos
   - Check days on market, price history, and any price reductions
2. **Run Comps** (15 min):
   - Find 3-5 comparable sales (within 1 mile, last 6 months, similar size/condition)
   - Find 3-5 rental comps (if rental strategy)
   - For Airbnb: check AirDNA or similar for nightly rate, occupancy, and revenue estimates
3. **Calculate the Numbers** (20 min):
   - Purchase: price + closing costs + rehab estimate
   - Monthly income: rent or Airbnb revenue estimate
   - Monthly expenses: mortgage, taxes, insurance, property management, maintenance reserve, vacancy reserve, HOA, utilities
   - Cash flow: income - expenses
   - Cash-on-cash return: (annual cash flow / total cash invested) x 100
   - For BRRRR: after-repair value (ARV) and refinance numbers
   - For flips: ARV - purchase - rehab - holding costs - selling costs = profit
4. **Assess Risk** (10 min):
   - What happens if rent/nightly rate drops 20%?
   - What happens if vacancy is 10% higher than projected?
   - What rehab surprises could increase costs?
   - What's the worst-case scenario — can you cover the mortgage if revenue goes to zero?
5. **Make the Decision** (5 min):
   - Does it meet your criteria?
     - Minimum cash-on-cash: [YOUR MINIMUM — e.g., 8%]
     - Minimum monthly cash flow: [YOUR MINIMUM — e.g., $300/month per unit]
     - Maximum purchase price: [YOUR MAX]
   - Go / No-Go / Negotiate (with target price)
6. **Document** (10 min):
   - Create a one-page deal memo with:
     - Property summary
     - Key numbers (purchase, income, expenses, cash flow, returns)
     - Risk factors
     - Recommendation
   - Store in [YOUR DEAL FILE — e.g., Google Drive, Notion]

## Expected Outputs
- Completed deal analysis with all numbers
- Risk assessment
- Go/No-Go recommendation with reasoning
- Deal memo (stored in [YOUR TOOL])

## Edge Cases & Learnings
- If comps are thin (fewer than 3), widen the search radius but note the reduced confidence
- If the deal only works with aggressive assumptions (high rent, low vacancy, no maintenance), it doesn't work — use conservative numbers
- If the seller won't negotiate, know your walk-away number before you start
- Always budget 10-15% above your rehab estimate for surprises
- [ADD YOUR OWN LEARNINGS HERE]
```

---

## Template 6: Automation Build Workflow (AI Track)

**From idea to deployed automation — the builder's SOP.**

```markdown
# Automation Build Workflow

## Objective
Build and deploy a working automation from scratch using the WAT framework. Go from "I do this manually every week" to "this runs itself" in a systematic way.

## Required Inputs
- Task to automate: [DESCRIBE THE MANUAL TASK — what you do, how often, how long it takes]
- Current tools involved: [WHAT PLATFORMS/TOOLS ARE USED NOW — e.g., Gmail, Sheets, Notion]
- Desired output: [WHAT THE AUTOMATION SHOULD PRODUCE AND WHERE]
- Technical level: [BEGINNER — use no-code tools / INTERMEDIATE — can modify code / ADVANCED — can write from scratch]
- Budget for tools: [MONTHLY BUDGET FOR APIs AND SERVICES]

## Tools Used
- Claude or Claude Code (development)
- [YOUR AUTOMATION PLATFORM — e.g., Python, n8n, Zapier, Make]
- [YOUR HOSTING — e.g., Railway, Render, Vercel, local machine]
- [YOUR APIS — list the services you'll connect to]

## Process Steps
1. **Write the SOP** (30 min):
   - Before you automate, document the manual process step by step
   - For each step ask: Is this a decision (AI) or an action (script)?
   - This SOP becomes your workflow file
2. **Identify the Tools** (15 min):
   - For each action step, identify what API or tool handles it
   - Check if tools already exist in your `tools/` directory
   - Note which APIs need keys and what they cost
3. **Build the MVP** (2-4 hours):
   - Start with the simplest version that works end-to-end
   - Skip edge cases, error handling, and polish for now
   - For no-code: build the basic flow in n8n/Zapier
   - For code: write the Python script with Claude Code
   - Test with real data — does it produce the expected output?
4. **Test** (30 min):
   - Run it 3 times with different inputs
   - Verify outputs are correct
   - Check for failures: What breaks? What's slow? What's wrong?
5. **Harden** (1-2 hours):
   - Add error handling for known failure points
   - Add logging so you can debug issues later
   - Handle edge cases identified during testing
   - Add rate limiting if calling external APIs
6. **Deploy** (30 min):
   - Move from local to hosted (Railway, Render, or cron job on your server)
   - Set up the trigger (schedule, webhook, or manual)
   - Verify it runs successfully in production
7. **Monitor & Improve** (ongoing):
   - Check outputs for the first week
   - Fix any issues that come up
   - Update the workflow SOP with learnings
   - Track time saved vs. time invested

## Expected Outputs
- Working automation (deployed and running)
- Workflow SOP (documented in `workflows/`)
- Tool scripts (saved in `tools/` if applicable)
- Updated CLAUDE.md with project context

## Edge Cases & Learnings
- If the manual process takes less than 15 minutes per week, it may not be worth automating — automate the high-impact tasks first
- If an API has rate limits, build in delays or use batch endpoints
- If the automation uses paid APIs, calculate the monthly cost before deploying — make sure the time saved justifies the cost
- Always build the MVP first. Don't over-engineer version 1.
- If it uses paid APIs, check with yourself before running tests repeatedly
- [ADD YOUR OWN LEARNINGS HERE]
```

---

## Building Your Own Workflows

You can create workflows for any repeatable process in your business. The format is always the same:

1. **Objective** — What does this accomplish?
2. **Required Inputs** — What do I need before I start?
3. **Tools Used** — What platforms, scripts, or services am I using?
4. **Process Steps** — What's the exact sequence?
5. **Expected Outputs** — What gets produced and where does it go?
6. **Edge Cases** — What could go wrong and how do I handle it?

The best workflows come from documenting what you already do manually, then turning each step into a clear instruction.

---

## What's Next

- **Grab prompts for each step:** [04-prompt-library.md](04-prompt-library.md) — ready-made prompts for content, proposals, analysis, and more
- **Level up your Claude skills:** [06-strategies-and-patterns.md](06-strategies-and-patterns.md) — advanced patterns for working with Claude
- **Go deeper on the framework:** Lesson 1.1.2 in the AI Systems Playbook — the full WAT Framework breakdown
