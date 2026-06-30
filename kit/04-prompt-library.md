# Prompt Library -- The Boardroom

> The difference between generic AI output and a real business tool is the prompt you write. A good prompt gives Claude your context, your constraints, and your format -- and what comes back is work you can actually use. This library gives you 30 prompts you can copy, customize, and run today.

---

## How to Use

- Each prompt below is inside a code block. Copy the whole thing.
- Replace every `[VARIABLE]` with your specifics. The variable names tell you exactly what to fill in.
- These work in both **Claude.ai** (paste into the chat) and **Claude Code** (paste into the terminal or reference in a workflow).
- Save the prompts you use most. Build a personal shortlist so you are not hunting through this doc every time.

---

## Quick Reference

| #  | Prompt                              | Category              |
|----|-------------------------------------|-----------------------|
| 1  | Blog Post from Outline              | Marketing & Content   |
| 2  | 30-Day Social Media Calendar        | Marketing & Content   |
| 3  | Email Marketing Sequence            | Marketing & Content   |
| 4  | Ad Copy Variations                  | Marketing & Content   |
| 5  | Case Study from Results             | Marketing & Content   |
| 6  | Content Repurposing                 | Marketing & Content   |
| 7  | Page Titles and Meta Descriptions   | SEO                   |
| 8  | Content Brief for Target Keyword    | SEO                   |
| 9  | Competitor Content Gap Analysis     | SEO                   |
| 10 | SEO Product Descriptions            | SEO                   |
| 11 | Client Proposal from Notes          | Sales & Proposals     |
| 12 | Cold Outreach Email Sequence        | Sales & Proposals     |
| 13 | Scope of Work Document              | Sales & Proposals     |
| 14 | Follow-Up Emails                    | Sales & Proposals     |
| 15 | Task to SOP Converter               | Operations & SOPs     |
| 16 | New Client Onboarding Checklist     | Operations & SOPs     |
| 17 | FAQ Document                        | Operations & SOPs     |
| 18 | Service Agreement Draft             | Operations & SOPs     |
| 19 | P&L Analysis                        | Finance & Analysis    |
| 20 | Cash Flow Projection                | Finance & Analysis    |
| 21 | Investment Memo                     | Finance & Analysis    |
| 22 | Business Decision Comparison        | Finance & Analysis    |
| 23 | Airbnb Listing Description          | Real Estate           |
| 24 | Property Analysis Summary           | Real Estate           |
| 25 | Tenant/Guest Communication Templates| Real Estate           |
| 26 | Rehab Scope of Work                 | Real Estate           |
| 27 | Debug with Context                  | Code & Technical      |
| 28 | API Integration from Docs           | Code & Technical      |
| 29 | Script from Workflow Description    | Code & Technical      |
| 30 | Write Tests for Existing Code       | Code & Technical      |

---

## Marketing & Content

### 1. Blog Post from Outline
**Use case:** Turn a rough topic and bullet points into a publish-ready blog post.
**Works in:** Both

```
You are a content writer for [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS IN ONE SENTENCE].

Write a blog post based on the following:

Topic: [TOPIC]
Target audience: [TARGET AUDIENCE — e.g., first-time homebuyers, small business owners, freelance designers]
Primary keyword: [PRIMARY KEYWORD]
Secondary keywords: [KEYWORD 2], [KEYWORD 3], [KEYWORD 4]
Tone: [TONE — e.g., authoritative but approachable, casual and relatable, technical but clear]

Outline:
- [SECTION 1 HEADING]: [Brief note on what this section covers]
- [SECTION 2 HEADING]: [Brief note]
- [SECTION 3 HEADING]: [Brief note]
- [SECTION 4 HEADING]: [Brief note]

Requirements:
- 1,200-1,800 words
- Include a compelling introduction that hooks the reader with a specific problem or scenario
- Each section should have actionable advice, not just theory
- End with a clear call to action pointing to [YOUR CTA — e.g., schedule a consultation, download the guide, visit the service page]
- Use short paragraphs (2-3 sentences max) for readability
- Include 2-3 subheadings per section
- Write in second person ("you") throughout
```

**Pro tip:** Paste a competitor's blog post at the end and add "Cover everything they covered, but go deeper on practical application" to immediately level up the output.

---

### 2. 30-Day Social Media Calendar
**Use case:** Plan a full month of content across platforms instead of scrambling for ideas daily.
**Works in:** Both

```
You are a social media strategist for [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS].

Create a 30-day social media content calendar for [MONTH/YEAR].

Platforms: [PLATFORM 1 — e.g., Instagram], [PLATFORM 2 — e.g., LinkedIn], [PLATFORM 3 — e.g., TikTok]
Target audience: [TARGET AUDIENCE]
Business goals this month: [GOAL 1 — e.g., drive traffic to new service page], [GOAL 2 — e.g., build authority in the HVAC space]
Products/services to promote: [PRODUCT/SERVICE 1], [PRODUCT/SERVICE 2]
Brand voice: [VOICE — e.g., confident and direct, friendly and educational, bold and irreverent]

For each day, provide:
- Platform
- Content type (carousel, reel, story, text post, poll, behind-the-scenes, testimonial, etc.)
- Post topic/angle
- Full caption (ready to copy and paste)
- Relevant hashtags (5-10 per post)
- Best time to post

Content mix guidelines:
- 40% value/educational content
- 25% social proof (testimonials, results, case studies)
- 20% behind-the-scenes / personality
- 15% direct promotion / CTA

Format the calendar as a table with columns: Day | Platform | Type | Topic | Caption | Hashtags | Post Time
```

**Pro tip:** Add 3-5 examples of your best-performing past posts so Claude can match what already works for your audience.

---

### 3. Email Marketing Sequence
**Use case:** Build an automated email sequence that nurtures leads or drives sales without writing each email from scratch.
**Works in:** Both

```
You are an email marketing specialist writing for [YOUR BUSINESS NAME].

Create a [SEQUENCE TYPE — e.g., welcome sequence, nurture sequence, sales sequence, re-engagement sequence] of [NUMBER — e.g., 5] emails.

Business: [DESCRIBE YOUR BUSINESS]
Audience: [WHO RECEIVES THESE EMAILS — e.g., new subscribers who downloaded our free HVAC maintenance checklist]
Offer: [WHAT YOU ARE SELLING OR PROMOTING]
Audience pain points: [PAIN POINT 1], [PAIN POINT 2], [PAIN POINT 3]
Unique value proposition: [WHAT MAKES YOUR OFFER DIFFERENT]

For each email, provide:
- Subject line (plus one A/B test alternative)
- Preview text (the snippet that shows in the inbox)
- Full email body
- CTA button text
- Recommended send delay (e.g., "Day 0 — immediately after signup," "Day 3")

Guidelines:
- Keep each email under 300 words — people skim
- Open with a hook, not "Hi [NAME], I hope you're doing well"
- One CTA per email — do not split attention
- Use storytelling and specific examples over generic claims
- The sequence should build momentum — each email should raise the stakes slightly
- Final email should create urgency without being sleazy
```

**Pro tip:** Tell Claude the specific objection each email should overcome (e.g., "Email 3 should address the objection that they can do this themselves"). This gives the sequence strategic architecture, not just content.

---

### 4. Ad Copy Variations
**Use case:** Generate multiple ad angles so you can test different hooks and find what converts.
**Works in:** Both

```
You are a direct-response copywriter creating ad copy for [YOUR BUSINESS NAME].

Platform: [PLATFORM — e.g., Facebook/Instagram, Google Search, Google Display, LinkedIn, YouTube]
Offer: [WHAT YOU ARE PROMOTING — be specific about the offer, price point, and what they get]
Target audience: [DETAILED AUDIENCE — e.g., homeowners aged 30-55 in [CITY] who need a new roof but keep putting it off]
Landing page URL: [URL]
Goal: [GOAL — e.g., lead form submissions, purchases, booked calls]

Create 5 ad variations, each with a different hook strategy:
1. Pain point — lead with the problem they are experiencing
2. Social proof — lead with a result or testimonial
3. Curiosity — lead with an unexpected angle or question
4. Direct offer — lead with the deal itself
5. Story — lead with a mini-narrative (before/after, client story)

For each variation, provide:
- Headline (under [CHARACTER LIMIT — e.g., 40 chars for Facebook, 30 chars for Google])
- Primary text / description
- CTA text
- The psychological trigger it is using and why it should work for this audience

Keep the language conversational. No corporate jargon. Write the way the target audience actually talks about this problem.
```

**Pro tip:** Include a sentence about what has NOT worked in past ads. "We tried discounts and urgency — they attracted tire-kickers" gives Claude the constraint it needs to avoid generic tactics.

---

### 5. Case Study from Results
**Use case:** Turn raw client results into a polished case study that sells your service.
**Works in:** Both

```
You are a marketing writer for [YOUR BUSINESS NAME].

Write a client case study based on the following raw details:

Client/project name: [CLIENT NAME OR ANONYMIZED DESCRIPTION — e.g., "a 3-unit rental property owner in Columbus, OH"]
Industry/context: [CLIENT'S INDUSTRY OR SITUATION]
Problem they had before working with us: [DESCRIBE THE PROBLEM IN DETAIL]
What we did: [DESCRIBE YOUR SERVICE/SOLUTION — be specific about deliverables, timeline, approach]
Results: [LIST SPECIFIC, MEASURABLE RESULTS — e.g., "Went from 40% occupancy to 97% in 90 days," "$14K monthly revenue increase," "Reduced tenant turnover by 60%"]
Client quote (if available): "[PASTE ANY QUOTE OR FEEDBACK YOU HAVE]"
Timeline: [HOW LONG THE ENGAGEMENT LASTED]

Structure the case study as:
1. **The Challenge** — Set the scene. What was at stake?
2. **The Approach** — What did we do and why? Be specific enough that the reader sees the expertise.
3. **The Results** — Lead with the numbers. Make them impossible to ignore.
4. **Key Takeaway** — One sentence the reader walks away with.

Format for a website page (headers, short paragraphs, bold key metrics). Total length: 500-800 words.
Do not exaggerate or add results that are not in the data I provided.
```

**Pro tip:** Add "Write the challenge section from the client's perspective, as if you are narrating their frustration" to make the opening feel like the reader's own situation.

---

### 6. Content Repurposing
**Use case:** Take one piece of long-form content and break it into platform-specific content for maximum reach.
**Works in:** Both

```
You are a content strategist for [YOUR BUSINESS NAME].

I am going to give you a piece of long-form content. Your job is to repurpose it into 5 platform-specific formats.

Original content type: [TYPE — e.g., YouTube video transcript, blog post, podcast episode notes, webinar recording transcript]
Target audience: [TARGET AUDIENCE]
Brand voice: [VOICE — e.g., direct and knowledgeable, casual and encouraging]

Here is the content:
---
[PASTE YOUR LONG-FORM CONTENT HERE]
---

Repurpose this into:

1. **Twitter/X thread** — 8-12 tweets. Start with a hook tweet that stands alone. Each tweet should deliver one idea. End with a CTA.

2. **LinkedIn post** — 150-200 words. Professional but not stiff. Open with a bold statement or counterintuitive take. Use line breaks for readability.

3. **Email newsletter** — 200-300 words. Conversational tone. One key insight from the content, then link to the full piece.

4. **Instagram carousel** — 10 slides. Slide 1 is the hook (question or bold statement). Slides 2-9 are the key points (one idea per slide, under 30 words each). Slide 10 is the CTA. Write the text for each slide.

5. **Short-form video script** — 45-60 seconds. Written for [PLATFORM — e.g., TikTok, Instagram Reels, YouTube Shorts]. Include the hook (first 3 seconds), the body, and the CTA. Write it as a spoken script, not bullet points.

For each format, note what angle or insight from the original content you are leading with and why it works for that platform.
```

**Pro tip:** Paste the transcript even if it is messy. Claude handles raw transcripts well. The less you clean up beforehand, the more time you save.

---

## SEO

### 7. Page Titles and Meta Descriptions
**Use case:** Optimize your website pages for search without hiring an SEO agency.
**Works in:** Both

```
You are an SEO specialist optimizing [YOUR WEBSITE URL] for [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS].

Write optimized page titles and meta descriptions for the following pages:

[PAGE 1 NAME] — [PAGE URL] — Target keyword: [KEYWORD]
[PAGE 2 NAME] — [PAGE URL] — Target keyword: [KEYWORD]
[PAGE 3 NAME] — [PAGE URL] — Target keyword: [KEYWORD]
[PAGE 4 NAME] — [PAGE URL] — Target keyword: [KEYWORD]
[PAGE 5 NAME] — [PAGE URL] — Target keyword: [KEYWORD]

Location targeting: [CITY, STATE or "national"]
Business differentiator: [WHAT MAKES YOU DIFFERENT — e.g., "24/7 emergency service," "serving the area since 2005," "free estimates"]

For each page, provide:
- Page title (under 60 characters, keyword near the front)
- Meta description (under 155 characters, includes keyword naturally, has a clear value prop or CTA)
- Why this title/description works (one sentence explaining the SEO and click-through logic)

Guidelines:
- Do not keyword stuff. Every title should read naturally to a human.
- Include the business name in the title only for the homepage.
- Meta descriptions should make someone want to click, not just describe the page.
- Use action language in descriptions: "Get," "Learn," "See," "Compare," "Find out."
```

**Pro tip:** Run this once, implement the changes, then run it again in 30 days with your Google Search Console data (impressions, clicks, CTR) and ask Claude to optimize the underperformers.

---

### 8. Content Brief for Target Keyword
**Use case:** Create a detailed writing brief before producing content so the final piece ranks.
**Works in:** Both

```
You are an SEO content strategist. Create a comprehensive content brief for the following keyword.

Target keyword: [KEYWORD]
Business: [YOUR BUSINESS NAME] — [DESCRIBE YOUR BUSINESS]
Target audience: [WHO IS SEARCHING FOR THIS KEYWORD AND WHY]
Content type: [TYPE — e.g., blog post, landing page, pillar page, guide]

Provide the following:

1. **Search intent analysis** — What is the searcher actually trying to accomplish? Informational, commercial, transactional, or navigational? What questions are they trying to answer?

2. **Recommended title** — Under 60 characters, keyword near the front, compelling enough to earn the click.

3. **Recommended URL slug** — Short, keyword-rich, no stop words.

4. **Content outline** — Full heading structure (H2s and H3s) that covers the topic comprehensively. Include 6-10 H2 sections minimum.

5. **Questions to answer** — List 8-12 specific questions the content should address (think "People Also Ask" on Google).

6. **Recommended word count** — Based on the depth needed to cover this topic well.

7. **Internal linking opportunities** — Suggest 3-5 related topics I should link to (or create if they do not exist).

8. **Competitor notes** — Based on what you know about content that typically ranks for this type of keyword, what do the top results likely cover? What can we do better or differently?

9. **Featured snippet opportunity** — Is there a featured snippet to target? If yes, provide the exact format (paragraph, list, table) and draft the answer.

10. **Secondary keywords** — 10-15 related keywords to weave into the content naturally.
```

**Pro tip:** Stack this with prompt #1 (Blog Post from Outline). Run this brief first, then feed the outline into the blog post prompt for a two-step content pipeline.

---

### 9. Competitor Content Gap Analysis
**Use case:** Find topics your competitors rank for that you have not covered yet.
**Works in:** Both

```
You are an SEO strategist performing a content gap analysis for [YOUR BUSINESS NAME].

My business: [DESCRIBE YOUR BUSINESS, LOCATION, TARGET AUDIENCE]
My website covers these topics: [LIST YOUR MAIN CONTENT TOPICS / BLOG CATEGORIES — e.g., HVAC maintenance tips, energy efficiency guides, seasonal checklists, equipment reviews]

Competitor: [COMPETITOR NAME AND WEBSITE]
Their content covers: [LIST THEIR MAIN CONTENT TOPICS — spend 5 minutes browsing their blog/resources section and list what you see]

Based on this comparison:

1. **Content gaps** — Topics they cover that I do not. Rank these by estimated business value (high, medium, low) based on how likely the topic is to attract my target customer.

2. **Depth gaps** — Topics we both cover, but they go deeper. Identify where I could expand existing content.

3. **Angle gaps** — Topics we both cover, but there is an underserved angle neither of us addresses well.

4. **Priority action plan** — Give me a ranked list of the top 10 content pieces I should create, with:
   - Recommended title
   - Target keyword
   - Content type (blog post, guide, landing page, tool, video)
   - Estimated difficulty (easy, medium, hard based on topic complexity)
   - Why this piece matters for my business

Focus on topics that drive revenue, not just traffic. I would rather rank for "emergency HVAC repair [CITY]" than "how does an air conditioner work."
```

**Pro tip:** Do this for 3 different competitors in separate prompts, then paste all three outputs into a new conversation and ask Claude to find the overlapping opportunities -- those are your highest-priority targets.

---

### 10. SEO Product Descriptions
**Use case:** Write product or service descriptions that rank in search and convert visitors.
**Works in:** Both

```
You are an SEO copywriter for [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS].

Write optimized product/service descriptions for the following:

Product/Service 1: [NAME]
- Target keyword: [KEYWORD]
- Key features: [FEATURE 1], [FEATURE 2], [FEATURE 3]
- Price point: [PRICE OR PRICE RANGE]
- Who it is for: [IDEAL CUSTOMER]
- What problem it solves: [PROBLEM]

Product/Service 2: [NAME]
- Target keyword: [KEYWORD]
- Key features: [FEATURE 1], [FEATURE 2], [FEATURE 3]
- Price point: [PRICE OR PRICE RANGE]
- Who it is for: [IDEAL CUSTOMER]
- What problem it solves: [PROBLEM]

[Add more as needed]

For each, provide:
- SEO-optimized description (150-250 words)
- A short version (50 words) for category pages or cards
- 3 bullet points highlighting key benefits (not features)
- A suggested H1 heading with the target keyword

Guidelines:
- Lead with the benefit, not the feature. "Stay comfortable year-round" beats "Variable-speed compressor technology."
- Include the target keyword in the first 50 words naturally.
- Write for the buyer, not the search engine. If it sounds robotic, rewrite it.
- End each description with a clear next step (call, book, buy, learn more).
```

**Pro tip:** Include one competitor's product description and say "Match or exceed this level of specificity, but with a different angle." This gives Claude a quality benchmark.

---

## Sales & Proposals

### 11. Client Proposal from Notes
**Use case:** Turn messy discovery call notes into a professional proposal you can send within the hour.
**Works in:** Both

```
You are a business development specialist at [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS].

Create a client proposal based on the following discovery call notes:

Client name: [CLIENT NAME]
Client business: [CLIENT'S BUSINESS AND WHAT THEY DO]
Date of call: [DATE]

Their situation:
[PASTE YOUR RAW NOTES — bullet points, sentence fragments, whatever you wrote down. Do not worry about formatting.]

Their goals:
[WHAT THEY WANT TO ACHIEVE]

Their budget range (if discussed): [BUDGET OR "not discussed"]
Their timeline: [WHEN THEY NEED THIS DONE]

Our proposed solution: [WHAT YOU PLAN TO DELIVER]
Our pricing: [YOUR PRICING FOR THIS PROJECT]

Structure the proposal as:
1. **Executive Summary** — 2-3 sentences showing you understand their problem and have a clear solution.
2. **Understanding Your Needs** — Reflect back what they told you. This proves you listened.
3. **Proposed Solution** — What you will deliver, broken into clear phases or deliverables.
4. **Scope of Work** — Specific line items of what is included (and what is not included).
5. **Timeline** — Milestones with estimated dates.
6. **Investment** — Pricing with payment terms. Frame it as an investment, not a cost.
7. **Why [YOUR BUSINESS NAME]** — 3-4 sentences on why you are the right choice. Specific, not generic.
8. **Next Steps** — Exactly what they need to do to move forward.

Tone: Professional but warm. This is a relationship, not a transaction.
Format: Clean enough to paste into a Google Doc or PDF template.
```

**Pro tip:** Paste your actual raw notes, typos and all. Claude will extract the important details. The messier your notes, the more time this prompt saves you.

---

### 12. Cold Outreach Email Sequence
**Use case:** Build a cold email sequence that gets responses without sounding like every other pitch in their inbox.
**Works in:** Both

```
You are a sales copywriter specializing in B2B outreach for [YOUR BUSINESS NAME].

Create a 3-email cold outreach sequence.

My service: [WHAT YOU OFFER — be specific about the deliverable and result]
Target persona: [JOB TITLE / ROLE — e.g., property managers at mid-size firms, marketing directors at e-commerce brands, restaurant owners in [CITY]]
Their likely pain point: [THE PROBLEM THEY FACE THAT YOUR SERVICE SOLVES]
My unique angle: [WHY THEY SHOULD PICK YOU OVER ALTERNATIVES — e.g., "We only work with contractors, so our marketing actually speaks the trade language"]
Social proof: [ONE RESULT OR CREDENTIAL — e.g., "Helped a 12-unit property manager cut vacancy from 22% to 4%"]

Email 1 — The Opener (Day 1):
- Subject line that earns the open (no clickbait, no "Quick question")
- 4-6 sentences max
- Acknowledge their world, reference the pain point, hint at the solution, soft CTA (reply or quick call)

Email 2 — The Value Add (Day 4):
- Subject line that references Email 1 or adds a new angle
- Share a specific insight, resource, or result that demonstrates expertise
- Do not just "follow up" — give them something useful
- CTA: slightly more direct

Email 3 — The Breakup (Day 8):
- Subject line that signals this is the last email
- Brief, respectful, low-pressure
- Leave the door open
- CTA: reply if timing is better later

Rules:
- No buzzwords ("synergy," "leverage," "touch base")
- No fake personalization ("I love what you are doing at [COMPANY]" without specifics)
- Write like a real person sending a real email, not a sales automation
- Every email should be under 100 words
```

**Pro tip:** After Claude generates the sequence, paste in a real recipient's LinkedIn profile or company About page and say "Personalize Email 1 for this specific person." That is how you get replies.

---

### 13. Scope of Work Document
**Use case:** Create a clear SOW that prevents scope creep and sets expectations before the project starts.
**Works in:** Both

```
You are a project manager at [YOUR BUSINESS NAME].

Create a formal Scope of Work document for the following project:

Client: [CLIENT NAME]
Project name: [PROJECT NAME — e.g., "Kitchen Renovation — 123 Oak Street," "Website Redesign," "Social Media Management Q2 2026"]
Project description: [2-3 SENTENCES DESCRIBING THE PROJECT]

Deliverables:
- [DELIVERABLE 1 — be specific: "Install 30 linear feet of quartz countertop" not "countertops"]
- [DELIVERABLE 2]
- [DELIVERABLE 3]
- [DELIVERABLE 4]
[Add more as needed]

What is NOT included (exclusions):
- [EXCLUSION 1 — e.g., "Electrical work beyond existing circuits"]
- [EXCLUSION 2]

Timeline:
- Start date: [DATE]
- Target completion: [DATE]
- Key milestones: [LIST ANY MILESTONES — e.g., "Demo complete by Week 2," "First draft by March 15"]

Pricing:
- Total project cost: [AMOUNT]
- Payment structure: [STRUCTURE — e.g., "50% upfront, 25% at midpoint, 25% on completion"]
- What triggers additional charges: [CHANGE ORDER POLICY — e.g., "Changes beyond original scope require written approval and are billed at $X/hour"]

Structure the SOW with:
1. Project Overview
2. Scope of Work (detailed deliverables)
3. Exclusions
4. Timeline and Milestones
5. Pricing and Payment Terms
6. Change Order Process
7. Client Responsibilities (what you need from them to stay on schedule)
8. Acceptance and Signatures

Format: Professional document ready to paste into a template. Include placeholder signature lines at the bottom.
```

**Pro tip:** Always fill in the "Exclusions" section thoroughly. The things you explicitly exclude prevent more disputes than the things you include.

---

### 14. Follow-Up Emails
**Use case:** Send the right follow-up at the right time instead of defaulting to "Just checking in."
**Works in:** Both

```
You are writing follow-up emails for [YOUR BUSINESS NAME].

Context: [CONTEXT — e.g., "I sent a proposal for a $15K bathroom renovation 5 days ago and have not heard back," "We had a discovery call last Tuesday and they seemed interested but asked for time to think," "This is a past client I have not spoken to in 6 months"]

My name: [YOUR NAME]
Recipient: [THEIR NAME AND ROLE]
Relationship so far: [BRIEF HISTORY — e.g., "Met at a networking event, had one call," "Completed a project for them last year," "They filled out our contact form"]
What I want to happen: [GOAL — e.g., "Get them to sign the proposal," "Book a follow-up call," "Rekindle the relationship for repeat business"]

Write 3 follow-up emails with different approaches:

1. **The Helpful Follow-Up** — Add value. Share a relevant insight, resource, or idea that shows you are thinking about their project, not just your sale.

2. **The Direct Follow-Up** — Straightforward and respectful. Acknowledge the silence, ask a direct question, make it easy to respond (even if the answer is no).

3. **The Soft Close** — Low pressure. Give them an easy out while keeping the door open. Works well when you sense hesitation.

For each email:
- Subject line
- Full email body (under 150 words each)
- Recommended timing (when to send relative to last contact)

Rules:
- Never guilt trip ("I have not heard from you...")
- Never fake urgency ("This offer expires...")
- Always make it about them, not you
- Make every email easy to respond to — yes/no questions beat open-ended ones
```

**Pro tip:** Tell Claude exactly what you think their objection is. "I think they are hesitant because of price" versus "I think they are comparing us to another vendor" will produce very different and more targeted follow-ups.

---

## Operations & SOPs

### 15. Task to SOP Converter
**Use case:** Turn the process in your head into a written procedure anyone on your team can follow.
**Works in:** Both

```
You are an operations specialist creating SOPs for [YOUR BUSINESS NAME].

I am going to describe a task I do regularly. Convert it into a clean, reusable Standard Operating Procedure.

Task name: [TASK NAME — e.g., "Processing a New Client Inquiry," "Preparing a Job Site for Work," "Publishing a Blog Post"]
How often this is done: [FREQUENCY — e.g., daily, weekly, per project]
Who does this: [ROLE — e.g., office manager, project lead, me personally but I want to delegate it]

Here is how I do it (in my own words):
---
[DESCRIBE THE TASK STEP BY STEP. Be messy. Include the little things you do automatically — the login steps, the double-checks, the "oh and I also" details. The messier and more detailed, the better the SOP.]
---

Tools/software used: [LIST ANY TOOLS — e.g., Google Sheets, QuickBooks, Jobber, our CRM, email]

Convert this into an SOP with:
1. **Purpose** — One sentence on why this task matters.
2. **Trigger** — What event or condition kicks off this task.
3. **Prerequisites** — What needs to be in place before starting (access, information, tools).
4. **Step-by-Step Procedure** — Numbered steps. Each step should be one action. Include where to click, what to check, and what to do if something goes wrong.
5. **Quality Checks** — How to verify the task was done correctly.
6. **Common Mistakes** — What goes wrong when this is done poorly.
7. **Time Estimate** — How long this should take when done efficiently.

Write it so someone with no context could follow it on their first day.
```

**Pro tip:** Record yourself doing the task (screen recording or voice memo) and paste the transcript instead of writing from memory. You will capture the small steps you do unconsciously that make or break the process.

---

### 16. New Client Onboarding Checklist
**Use case:** Ensure every new client has a consistent, professional first experience with your business.
**Works in:** Both

```
You are an operations manager at [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS].

Create a comprehensive new client onboarding checklist for the following service:

Service: [SERVICE — e.g., "HVAC maintenance contract," "website design project," "property management," "monthly social media management"]
Typical client: [CLIENT TYPE — e.g., "homeowner," "small business owner with 5-20 employees," "real estate investor with 3-10 units"]
Onboarding timeline: [HOW LONG FROM SIGNED CONTRACT TO FULLY ONBOARDED — e.g., "same day," "1 week," "2 weeks"]

Information I need to collect from the client:
[LIST WHAT YOU KNOW YOU NEED — e.g., "property address, access codes, emergency contact, insurance info"]

Tools we use:
[LIST YOUR TOOLS — e.g., "Jobber for scheduling, QuickBooks for invoicing, Google Drive for documents, Slack for communication"]

Create the checklist in three phases:

**Phase 1: Immediate (Day 1)**
- Administrative tasks (contract, payment, account setup)
- Welcome communication
- Access and credentials

**Phase 2: Setup (Days 2-5)**
- System configuration
- Information gathering
- Team introductions or assignments
- Initial assessment or kickoff

**Phase 3: Confirmation (Days 5-14)**
- Verify everything is working
- First deliverable or touchpoint
- Feedback check-in
- Handoff from sales to delivery (if applicable)

For each item, include:
- The task (specific and actionable)
- Who is responsible (you, the client, or a team member by role)
- How to do it (brief instruction or link to SOP if applicable)
- Done criteria (how you know this step is complete)

End with a "Client Welcome Email" template I can customize and send on Day 1.
```

**Pro tip:** After running this, test the checklist on your next real client. Come back and tell Claude what was missing or unnecessary -- iterating with real experience produces a checklist that actually holds up.

---

### 17. FAQ Document
**Use case:** Build an FAQ page for your website or a reference doc for your team that handles the same questions you answer every week.
**Works in:** Both

```
You are a customer communications specialist for [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS] serving [TARGET AUDIENCE] in [LOCATION OR "nationally"].

Create a professional FAQ document based on the following:

Common questions I get asked (list as many as you have):
1. [QUESTION 1 — e.g., "How much does a new AC unit cost?"]
2. [QUESTION 2 — e.g., "Do you offer financing?"]
3. [QUESTION 3]
4. [QUESTION 4]
5. [QUESTION 5]
[Add up to 20]

Additional context for answers:
- [CONTEXT — e.g., "We serve the greater Columbus, OH area," "Our pricing starts at $X," "We require a 50% deposit," "Our turnaround is typically 2-3 weeks"]

For each question, write:
- The question (reworded for clarity if needed)
- A clear, helpful answer (3-5 sentences)
- A soft CTA where appropriate (e.g., "Contact us for a free estimate" or "See our pricing page for current rates")

Also generate 5-10 additional questions I probably get asked but forgot to list, based on what is common in the [YOUR INDUSTRY] industry. Answer those too.

Group all questions into logical categories (e.g., Pricing, Process, Scheduling, Guarantees, General).

Format: Ready to paste into a website FAQ page or a Google Doc for internal reference.
Tone: Helpful and confident. Answer like an expert who respects the customer's time.
```

**Pro tip:** Paste in your actual answers to a few of the questions (even if rough) so Claude matches your voice rather than generating generic corporate answers.

---

### 18. Service Agreement Draft
**Use case:** Generate terms of service or service agreement language for a new offering.
**Works in:** Both

```
You are a business operations specialist drafting a service agreement for [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS] based in [STATE].

Draft a service agreement for the following:

Service: [SERVICE — e.g., "residential HVAC maintenance plan," "monthly social media management," "general contracting for home renovations"]
Client type: [CLIENT TYPE — e.g., "homeowner," "small business," "property management company"]

Key terms to include:
- Scope of services: [DESCRIBE WHAT IS INCLUDED]
- Exclusions: [WHAT IS NOT INCLUDED]
- Pricing: [PRICING STRUCTURE — e.g., "$199/month," "$5,000 per project," "hourly at $85/hr"]
- Payment terms: [TERMS — e.g., "Net 30," "50% upfront, 50% on completion," "auto-pay monthly"]
- Duration: [CONTRACT LENGTH — e.g., "12 months," "project-based," "month-to-month"]
- Cancellation policy: [POLICY — e.g., "30 days written notice," "no penalty after minimum term"]
- Liability limitations: [ANY LIMITS — e.g., "liability limited to contract value," "no liability for pre-existing conditions"]
- Warranty/guarantee: [IF ANY — e.g., "1-year workmanship warranty," "satisfaction guarantee with revision rounds"]

Structure the agreement with:
1. Parties and Effective Date
2. Scope of Services
3. Exclusions
4. Term and Renewal
5. Fees and Payment
6. Client Responsibilities
7. Cancellation and Termination
8. Limitation of Liability
9. Warranty (if applicable)
10. Dispute Resolution
11. General Provisions
12. Signatures

Write in clear, plain language -- not dense legalese. This should be understandable to the client without a law degree.

**IMPORTANT: This is a starting draft, not legal advice. I will have this reviewed by an attorney before using it with clients.**
```

**Pro tip:** After Claude drafts this, paste it back into a new conversation and say "Review this agreement from the client's perspective. What would make you hesitant to sign? What is unclear?" That second pass catches blind spots.

---

## Finance & Analysis

### 19. P&L Analysis
**Use case:** Get quick insights from your profit and loss statement without waiting for your accountant.
**Works in:** Both

```
You are a financial analyst reviewing the P&L for [YOUR BUSINESS NAME], a [DESCRIBE YOUR BUSINESS].

Here are my numbers for [TIME PERIOD — e.g., "January 2026," "Q4 2025," "Full Year 2025"]:

Revenue:
- [REVENUE LINE 1 — e.g., "Service revenue: $45,000"]
- [REVENUE LINE 2 — e.g., "Product sales: $12,000"]
- [REVENUE LINE 3]
Total Revenue: [TOTAL]

Cost of Goods Sold / Direct Costs:
- [COGS LINE 1 — e.g., "Materials: $8,500"]
- [COGS LINE 2 — e.g., "Subcontractor labor: $12,000"]
- [COGS LINE 3]
Total COGS: [TOTAL]

Operating Expenses:
- [EXPENSE 1 — e.g., "Rent: $2,200"]
- [EXPENSE 2 — e.g., "Software/subscriptions: $850"]
- [EXPENSE 3 — e.g., "Marketing: $1,500"]
- [EXPENSE 4 — e.g., "Insurance: $400"]
- [EXPENSE 5 — e.g., "Vehicle: $600"]
[Add all expense lines]
Total Operating Expenses: [TOTAL]

Previous period for comparison (if available):
[PASTE PREVIOUS PERIOD NUMBERS OR "no previous data"]

Provide:
1. **Key Metrics** — Gross margin, net margin, operating margin. Are these healthy for my industry?
2. **Trends** — What changed from last period and why it matters.
3. **Red Flags** — Any expenses that look too high, margins that are too thin, or revenue concentration risks.
4. **Opportunities** — Where could I improve profitability? Be specific.
5. **Action Items** — 3-5 concrete things I should do based on this analysis.
6. **Benchmarks** — How do my margins compare to typical businesses in [YOUR INDUSTRY]?

Talk to me like a business partner, not a textbook. I want actionable analysis, not definitions of what gross margin means.
```

**Pro tip:** Run this monthly with consistent formatting. After 3 months, paste all three analyses into one conversation and ask Claude to identify the trend across months -- that is where the real insights live.

---

### 20. Cash Flow Projection
**Use case:** See where your cash position is headed so you can plan for shortfalls or investments.
**Works in:** Both

```
You are a financial planner creating a cash flow projection for [YOUR BUSINESS NAME].

Current cash position: $[AMOUNT] (as of [DATE])

Monthly recurring income:
- [INCOME SOURCE 1]: $[AMOUNT] — [NOTES — e.g., "steady," "seasonal — drops in winter," "new client starting in March"]
- [INCOME SOURCE 2]: $[AMOUNT] — [NOTES]
- [INCOME SOURCE 3]: $[AMOUNT] — [NOTES]

Monthly recurring expenses:
- [EXPENSE 1]: $[AMOUNT]
- [EXPENSE 2]: $[AMOUNT]
- [EXPENSE 3]: $[AMOUNT]
- [EXPENSE 4]: $[AMOUNT]
- [EXPENSE 5]: $[AMOUNT]
[Add all fixed monthly expenses]

Known upcoming one-time items:
- [ITEM — e.g., "Equipment purchase: $3,500 in April"]
- [ITEM — e.g., "Quarterly tax payment: $4,200 in April"]
- [ITEM — e.g., "New contract starting May: +$2,500/month"]
- [ITEM — e.g., "Hiring a part-time employee in June: +$2,000/month expense"]

Expected changes:
- [CHANGE — e.g., "Revenue expected to increase 10% in summer months," "Losing one client in March: -$1,500/month"]

Create a [6 OR 12]-month cash flow projection in table format:

| Month | Starting Cash | Income | Expenses | Net Cash Flow | Ending Cash |
|-------|--------------|--------|----------|---------------|-------------|

Then provide:
1. **Months where cash gets tight** — Flag any month where ending cash drops below $[YOUR MINIMUM COMFORT LEVEL — e.g., $3,000].
2. **Recommendations** — What to do now to avoid those tight months.
3. **Best case / worst case** — Show a range if certain expected income does not materialize.
4. **Decision points** — When is it safe to make that hire, purchase that equipment, or take on that debt?
```

**Pro tip:** Be pessimistic with income estimates and generous with expense estimates. A projection that shows you are fine even in a bad month is more useful than one that only works if everything goes perfectly.

---

### 21. Investment Memo
**Use case:** Organize your thinking on a deal before committing capital.
**Works in:** Both

```
You are an investment analyst writing a memo for [YOUR NAME / YOUR BUSINESS NAME].

Create a structured investment memo for the following opportunity:

Investment type: [TYPE — e.g., "rental property," "business acquisition," "equipment purchase," "stock/crypto position," "partnership opportunity"]

Deal details:
- What: [DESCRIBE THE INVESTMENT]
- Cost: $[TOTAL INVESTMENT REQUIRED]
- Expected return: [EXPECTED RETURNS — e.g., "$1,200/month cash flow," "25% ROI over 3 years," "2x revenue within 18 months"]
- Timeline: [INVESTMENT HORIZON — e.g., "hold for 5 years," "12-month payback period"]
- Financing: [HOW YOU PLAN TO FUND IT — e.g., "cash," "SBA loan at 7.5%," "$50K cash + $150K mortgage"]

Additional context:
[PASTE ANY RELEVANT DETAILS — property listing, business financials, market data, comparable deals you have seen]

Structure the memo as:

1. **Executive Summary** — The deal in 3 sentences.
2. **Investment Thesis** — Why this is a good opportunity. What is the core bet?
3. **Financial Analysis** — Break down the numbers. Cash-on-cash return, cap rate (if real estate), payback period, IRR if applicable. Show the math.
4. **Risk Assessment** — What could go wrong? List 5-7 specific risks, not generic ones. Rate each as high/medium/low probability and high/medium/low impact.
5. **Mitigants** — For each major risk, what is the plan to reduce or manage it?
6. **Comparable Analysis** — What have similar investments returned? What is the market context?
7. **Exit Strategy** — How do you get out if you need to? What is the expected exit timeline and return?
8. **Recommendation** — Go or no-go, with conditions (e.g., "Go if you can negotiate the price below $X").

Be rigorous. I want this memo to challenge the deal, not just confirm what I want to hear.
```

**Pro tip:** After the first output, say "Now argue against this investment. What am I missing? Play devil's advocate." The second pass often surfaces the risk that kills the deal or the concern you need to address before committing.

---

### 22. Business Decision Comparison
**Use case:** Structure your thinking when you are choosing between two paths.
**Works in:** Both

```
You are a business strategist advising [YOUR NAME] at [YOUR BUSINESS NAME].

I am deciding between two options and need a structured analysis.

**Option A:** [DESCRIBE OPTION A IN DETAIL — e.g., "Hire a full-time marketing employee at $55K/year + benefits"]
**Option B:** [DESCRIBE OPTION B IN DETAIL — e.g., "Hire a marketing agency at $3,500/month for a 6-month contract"]

Context:
- My business: [DESCRIBE CURRENT STATE — revenue, team size, stage]
- Why this decision matters now: [WHAT TRIGGERED THIS — e.g., "We are growing and I cannot handle marketing myself anymore"]
- Budget: [WHAT I CAN AFFORD]
- Timeline pressure: [HOW QUICKLY DO I NEED RESULTS]
- My priorities: [WHAT MATTERS MOST — e.g., "cost efficiency," "speed to results," "long-term capability building," "flexibility"]

Analyze both options across:
1. **Total cost** — Full cost over 6 months and 12 months, including hidden costs (training, management time, tools, onboarding).
2. **Speed to impact** — How quickly will each option start producing results?
3. **Quality of output** — What level of work can I expect from each?
4. **Flexibility** — How easy is it to scale up, scale down, or reverse this decision?
5. **Risk** — What is the downside if this does not work out?
6. **Opportunity cost** — What am I giving up by choosing one over the other?
7. **Long-term implications** — Where does each option put me in 1-2 years?

Format the comparison as a side-by-side table, then give me:
- Your recommendation
- The conditions under which you would change your recommendation
- The one question I should answer before deciding
```

**Pro tip:** Add a third option: "Option C: Do nothing for 90 days." Sometimes the best decision is the one you do not rush.

---

## Real Estate

### 23. Airbnb Listing Description
**Use case:** Write a listing that stands out in search results and convinces guests to book.
**Works in:** Both

```
You are a short-term rental marketing specialist writing an Airbnb listing for [YOUR NAME / YOUR BUSINESS NAME].

Property details:
- Property type: [TYPE — e.g., "2BR/1BA duplex unit," "entire 3BR house," "private room in shared home," "studio apartment"]
- Location: [CITY, NEIGHBORHOOD — e.g., "Short North, Columbus, OH"]
- Sleeps: [NUMBER OF GUESTS]
- Beds: [BED CONFIGURATION — e.g., "1 king, 1 queen, 1 sofa bed"]
- Bathrooms: [NUMBER AND DETAILS]

Key amenities:
- [AMENITY 1 — e.g., "Fast WiFi (150+ Mbps) with dedicated workspace"]
- [AMENITY 2 — e.g., "Free parking in private driveway"]
- [AMENITY 3 — e.g., "Fully stocked kitchen with coffee maker and spices"]
- [AMENITY 4 — e.g., "55-inch smart TV with Netflix, Hulu, Disney+"]
- [AMENITY 5]
[Add all notable amenities]

Location highlights:
- [NEARBY ATTRACTION 1 — e.g., "5-minute walk to downtown restaurants and bars"]
- [NEARBY ATTRACTION 2 — e.g., "10 minutes from the convention center"]
- [NEARBY ATTRACTION 3 — e.g., "Right off I-71, easy highway access"]

Target guests: [WHO YOU WANT TO ATTRACT — e.g., "business travelers," "couples on weekend getaways," "families visiting OSU," "traveling nurses on 13-week contracts"]

What makes this place special: [YOUR DIFFERENTIATOR — e.g., "Recently renovated with all-new furniture," "The only listing in the area with a hot tub," "Walking distance to everything"]

Write:
1. **Listing title** — 5 options, each under 50 characters, optimized for Airbnb search. Include the most searched amenity or location keyword.
2. **Listing description** — 200-300 words. Hook them in the first sentence. Paint a picture of their experience, not just a list of features. Break into short paragraphs.
3. **Space description** — Room-by-room breakdown.
4. **Guest access description** — What they have access to and any limitations.
5. **Neighborhood description** — What is nearby and why the location matters for their trip.
6. **Check-in instructions** — Clear, step-by-step (leave placeholders for codes and specific details).
7. **House rules** — Professional, clear, covers the essentials without being hostile.

Tone: Warm and inviting but not over-the-top. Describe the experience, not just the stuff.
```

**Pro tip:** Check the top 5 listings in your area before running this. Add "Competitors mention [X, Y, Z]. Differentiate from those listings by emphasizing [YOUR UNIQUE FEATURES]" at the end.

---

### 24. Property Analysis Summary
**Use case:** Run a quick deal analysis before going deeper on due diligence.
**Works in:** Both

```
You are a real estate investment analyst.

Analyze the following property for [YOUR NAME]:

Property address: [ADDRESS]
Asking price: $[PRICE]
Property type: [TYPE — e.g., "single-family rental," "duplex," "4-unit multifamily," "Airbnb potential"]

Income details:
- Current rent (or estimated rent): $[AMOUNT]/month per unit
- Number of units: [NUMBER]
- Current occupancy: [OCCUPANCY — e.g., "100%," "1 of 2 units vacant," "not currently rented"]
- Other income: $[AMOUNT] (e.g., laundry, parking, storage)

Expense estimates:
- Property taxes: $[AMOUNT]/year
- Insurance: $[AMOUNT]/year
- Property management (if applicable): [PERCENTAGE]% of gross rent
- Estimated maintenance: $[AMOUNT]/year (or I will use standard estimates)
- Utilities paid by owner: $[AMOUNT]/month
- HOA (if applicable): $[AMOUNT]/month
- Other expenses: [LIST ANY]

Financing:
- Down payment: $[AMOUNT] ([PERCENTAGE]%)
- Loan amount: $[AMOUNT]
- Interest rate: [RATE]%
- Loan term: [YEARS] years

Provide:
1. **Monthly Cash Flow** — Gross rent minus all expenses and debt service. Show the full breakdown.
2. **Key Metrics** — Cash-on-cash return, cap rate, gross rent multiplier, DSCR (debt service coverage ratio), price per unit.
3. **Break-Even Analysis** — What occupancy rate do I need to break even?
4. **Comparison to Benchmarks** — Are these numbers good for [CITY/MARKET]?
5. **Red Flags** — Anything in these numbers that concerns you.
6. **Sensitivity Analysis** — What happens if rent is 10% lower? If vacancy is 10%? If rates rise 1%?
7. **Verdict** — Is this a deal worth pursuing? Under what conditions?

Show your math. I want to verify the numbers, not just trust a summary.
```

**Pro tip:** Run this prompt with three different financing scenarios (e.g., 20% down conventional, 25% down DSCR loan, and cash purchase) to see which structure maximizes your returns.

---

### 25. Tenant/Guest Communication Templates
**Use case:** Handle common landlord or host communications professionally and consistently.
**Works in:** Both

```
You are a property management communications specialist.

Create professional templates for [YOUR NAME / YOUR BUSINESS NAME] for the following scenarios:

Property type: [TYPE — e.g., "long-term rental," "Airbnb short-term rental," "mixed portfolio"]
Management style: [STYLE — e.g., "I self-manage," "I have a property manager but want templates for direct communication," "I manage through Airbnb messaging"]
Tone: [TONE — e.g., "professional and firm," "friendly but clear," "warm and hospitality-focused"]

Create templates for these scenarios:

1. **Late rent/payment notice** — First reminder (friendly), second notice (firm), final notice (formal with consequences outlined)

2. **Maintenance request response** — Acknowledgment of request, scheduling the repair, follow-up after repair is complete

3. **Lease renewal offer** — Notify tenant of renewal terms, including any rent adjustment, with deadline to respond

4. **Check-in instructions** (for short-term rentals) — Day-before message, check-in day message with access details, mid-stay check-in, check-out instructions

5. **Review request** (for short-term rentals) — Post-stay message asking for a review, with a natural and non-pushy tone

6. **Move-in / move-out instructions** — What to expect, what is required, documentation process

7. **Noise or rule violation notice** — Professional but firm, documents the issue, states the expectation going forward

For each template:
- Use [PLACEHOLDERS] for names, dates, amounts, and property details
- Keep each under 200 words
- Include a subject line where applicable (email/message subject)
- Note the recommended timing (when to send relative to the event)
```

**Pro tip:** Add "Also write a response template for when the tenant/guest pushes back or disputes the issue" for the late payment and violation templates. Having the second response ready prevents emotional replies.

---

### 26. Rehab Scope of Work
**Use case:** Turn inspection findings or your renovation vision into a detailed scope a contractor can bid on.
**Works in:** Both

```
You are a construction project manager creating a rehab scope of work.

Property: [ADDRESS]
Property type: [TYPE — e.g., "3BR/2BA single-family, built 1985, 1,400 sq ft"]
Purpose of rehab: [PURPOSE — e.g., "Prepare for long-term rental," "Flip for resale," "Airbnb conversion," "Owner-occupied renovation"]
Budget range: $[LOW] - $[HIGH]

Inspection findings or project vision:
---
[PASTE INSPECTION REPORT NOTES, YOUR WALKTHROUGH NOTES, OR DESCRIBE WHAT YOU WANT DONE — be as detailed or rough as you have. Examples: "Roof is 20 years old, some missing shingles. Kitchen is original — laminate counters, old appliances. Both bathrooms need updating. Hardwood floors under carpet in living room. HVAC unit is 15 years old, still runs. Electrical panel is 100 amp."]
---

Create a detailed scope of work organized by trade/area:

1. **Exterior** — Roof, siding, gutters, landscaping, driveway, paint
2. **Kitchen** — Cabinets, countertops, appliances, backsplash, flooring, lighting, plumbing fixtures
3. **Bathrooms** — Vanity, toilet, tub/shower, tile, fixtures, lighting
4. **Flooring** — By room, material specification
5. **Paint** — Interior and exterior, prep work, number of coats, finish type
6. **Electrical** — Panel, outlets, fixtures, code updates
7. **Plumbing** — Fixtures, water heater, supply/drain lines
8. **HVAC** — Unit replacement, ductwork, thermostat
9. **General** — Doors, trim, hardware, windows, drywall repair, cleaning

For each line item, provide:
- Description of work (specific enough to get an accurate bid)
- Material specification (e.g., "LVP flooring, mid-grade" not just "new flooring")
- Priority: Must-do / Should-do / Nice-to-have
- Estimated cost range

End with:
- **Total estimated cost range** (low/mid/high)
- **Recommended project sequence** (what order to do the work)
- **Items to get multiple bids on** (highest-cost items where pricing varies most)
- **Permits likely needed**

This scope needs to be detailed enough that a contractor can give me an accurate bid without a follow-up conversation.
```

**Pro tip:** Take 20 photos during your walkthrough and describe what you see in each. "Photo 1: kitchen — oak cabinets, laminate counters, electric stove from the 90s, vinyl floor peeling in corner" gives Claude the raw material to write a comprehensive scope.

---

## Code & Technical

### 27. Debug with Context
**Use case:** Get an actual fix instead of a vague suggestion by giving Claude the full picture.
**Works in:** Both

```
I need help debugging an issue.

Language/framework: [LANGUAGE AND FRAMEWORK — e.g., "Python 3.11 with FastAPI," "Next.js 14 with TypeScript," "Python with pandas"]
What I am building: [ONE SENTENCE — e.g., "An API endpoint that processes uploaded CSV files and returns aggregated data"]

The error:
---
[PASTE THE FULL ERROR MESSAGE AND STACK TRACE]
---

The relevant code:
---
[PASTE THE CODE THAT IS FAILING — include the full function/file, not just the line that errors. Include imports.]
---

What I expected to happen:
[DESCRIBE EXPECTED BEHAVIOR]

What actually happened:
[DESCRIBE ACTUAL BEHAVIOR]

What I have already tried:
- [ATTEMPT 1 — e.g., "Checked that the file path exists — it does"]
- [ATTEMPT 2 — e.g., "Tried wrapping in try/except — the error is in the pandas read_csv call"]
- [ATTEMPT 3]

Environment details:
- OS: [OS]
- Package versions that might matter: [LIST — e.g., "pandas 2.1.0, numpy 1.25"]
- Any recent changes: [WHAT CHANGED BEFORE THE ERROR STARTED — e.g., "Upgraded pandas from 1.5 to 2.1"]

Give me:
1. The root cause of the error
2. The fix (show me the corrected code, not just a description)
3. Why this happened (so I understand it, not just copy-paste the fix)
4. How to prevent this type of error in the future
```

**Pro tip:** Always include what you already tried. It prevents Claude from suggesting things you have already ruled out, and it narrows the solution space dramatically.

---

### 28. API Integration from Docs
**Use case:** Skip hours of reading API documentation and get working integration code.
**Works in:** Both

```
I need to integrate with an API.

API: [API NAME — e.g., "Stripe Payments API," "Google Sheets API," "Plaid Transactions API," "OpenAI API"]
Documentation URL: [URL — if available]
Language: [LANGUAGE — e.g., "Python," "TypeScript/Node.js"]

What I want to accomplish:
[DESCRIBE THE SPECIFIC TASK — e.g., "Create a customer, charge their card $50, and store the transaction ID in my database," "Read data from a Google Sheet, process it, and write results back to a new tab," "Pull the last 30 days of transactions from a connected bank account"]

Authentication method: [METHOD — e.g., "API key in header," "OAuth 2.0," "Bearer token," "I do not know yet"]
API key / credentials: [DO NOT PASTE REAL KEYS — just say "stored in .env as [VARIABLE_NAME]" or "I have them ready"]

My existing setup:
- [RELEVANT CONTEXT — e.g., "I already have a FastAPI app running," "This is a standalone script," "I am using the official SDK already installed"]
- [DATABASE IF RELEVANT — e.g., "PostgreSQL with SQLAlchemy," "MongoDB," "just JSON files for now"]

Provide:
1. **Complete working code** — Not pseudocode. Working code I can run after adding my API key.
2. **Environment setup** — What packages to install, what environment variables to set.
3. **Error handling** — Handle common API errors (rate limits, auth failures, network errors) gracefully.
4. **Testing approach** — How to verify this works without making real charges or irreversible API calls (sandbox mode, test keys, dry runs).
5. **Rate limiting / best practices** — Any gotchas specific to this API I should know about.

Store credentials in environment variables, not in the code.
```

**Pro tip:** If the API has an official SDK, mention it. "Use the official [API] Python SDK" produces cleaner, more maintainable code than raw HTTP requests.

---

### 29. Script from Workflow Description
**Use case:** Automate a manual workflow by describing it in plain English.
**Works in:** Claude Code (best) / Claude.ai

```
I want to automate a workflow. Here is what I currently do manually:

1. [STEP 1 — e.g., "Every Monday, I open our CRM and export all new leads from the past week as a CSV"]
2. [STEP 2 — e.g., "I open the CSV and filter for leads in Ohio and Pennsylvania"]
3. [STEP 3 — e.g., "For each filtered lead, I look up their company on LinkedIn to see company size"]
4. [STEP 4 — e.g., "I score each lead based on company size and industry: 10+ employees in construction = hot, everything else = warm"]
5. [STEP 5 — e.g., "I update a Google Sheet with the scored leads"]
6. [STEP 6 — e.g., "I send myself a Slack message with the count of hot leads"]
[Add as many steps as your workflow has]

Tools and services involved:
- [TOOL 1 — e.g., "HubSpot CRM (API available)"]
- [TOOL 2 — e.g., "Google Sheets"]
- [TOOL 3 — e.g., "Slack"]

How often this runs: [FREQUENCY — e.g., "Every Monday at 8 AM," "Daily," "Whenever a new file appears in a folder"]
Language preference: [LANGUAGE — e.g., "Python"]
Where this will run: [ENVIRONMENT — e.g., "My local machine," "A server," "GitHub Actions," "I do not know yet — recommend something"]

Create:
1. **A Python script** that automates this entire workflow
2. **A requirements.txt** with all dependencies
3. **A .env.example** file showing what credentials I need to set up
4. **Instructions** for how to run it (and how to schedule it if applicable)
5. **Logging** — The script should log what it did so I can verify it worked

Keep the code modular. Each step should be its own function so I can modify individual steps without touching the rest.
```

**Pro tip:** Record yourself doing the workflow once and note every micro-decision you make (e.g., "If the company name has 'LLC' I search without it"). These edge cases are what make the automation actually work.

---

### 30. Write Tests for Existing Code
**Use case:** Add test coverage to code that does not have it yet.
**Works in:** Claude Code (best) / Claude.ai

```
Write tests for the following code.

Language/framework: [LANGUAGE AND TEST FRAMEWORK — e.g., "Python with pytest," "TypeScript with Jest," "Python with unittest"]

Here is the code to test:
---
[PASTE THE FUNCTION, CLASS, OR MODULE]
---

What this code does (in plain English):
[DESCRIBE THE PURPOSE — e.g., "This function takes a list of transactions, groups them by category, and returns a summary with totals and averages per category"]

Known inputs and expected outputs:
- Input: [EXAMPLE INPUT] -> Expected output: [EXPECTED OUTPUT]
- Input: [EXAMPLE INPUT 2] -> Expected output: [EXPECTED OUTPUT 2]
[Add any examples you have]

Write comprehensive tests covering:
1. **Happy path** — Normal inputs that should work correctly
2. **Edge cases** — Empty inputs, single items, boundary values, maximum sizes
3. **Error cases** — Invalid inputs, missing fields, wrong types, null/None values
4. **Business logic** — Specific scenarios that matter for how this code is used (e.g., "What happens when a transaction has a negative amount?")

For each test:
- Use a descriptive test name that explains the scenario (e.g., `test_returns_empty_dict_when_no_transactions`)
- Include a brief comment explaining what the test verifies and why it matters
- Use arrange-act-assert structure

Also flag:
- Any parts of the code that are hard to test and why
- Any dependencies that should be mocked
- Suggested refactors that would make the code more testable
```

**Pro tip:** Paste the code that calls this function too. Knowing how the code is used in context lets Claude write tests that cover real scenarios, not just theoretical ones.

---

## Building Your Own Prompts

The prompts above cover common scenarios, but you will have needs that are specific to your business. When you write your own, use this formula:

**Role + Context + Task + Format = Good Prompt**

- **Role:** Tell Claude who it is. "You are a financial analyst" produces different output than "You are a marketing copywriter."
- **Context:** Give Claude your business details, constraints, and the background it needs. The more specific, the better.
- **Task:** Be explicit about what you want. "Write a proposal" is weak. "Write a 5-section proposal with scope, timeline, and pricing for a bathroom renovation" is strong.
- **Format:** Specify headers, bullet points, tables, word counts, tone. Claude follows formatting instructions precisely when you provide them.

A prompt that takes 5 minutes to write well saves you hours of rewriting a mediocre output.

---

## What's Next

- **[05-workflow-templates.md](05-workflow-templates.md)** -- Workflow SOPs that chain multiple prompts together into repeatable systems
- **[06-strategies-and-patterns.md](06-strategies-and-patterns.md)** -- Advanced patterns for getting more out of Claude: multi-pass prompting, chain-of-thought, iterative refinement, and more
