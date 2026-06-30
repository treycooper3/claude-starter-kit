# Claude.ai Quickstart — Set Up Claude for Your Business

| Field | Value |
|-------|-------|
| **Difficulty** | Beginner |
| **Time** | 10-15 minutes |
| **What You Need** | A web browser and an email address |
| **Cost** | Free tier available — Pro is $20/month |

---

> **Key takeaway:** Claude is only as useful as the context you give it. Set up custom instructions once, and every conversation starts smarter.

---

## What Is Claude.ai?

Claude is an AI assistant made by Anthropic. You type a message, it responds. Think of it as a hyper-intelligent business partner that never sleeps, never forgets what you told it, and works at the speed of typing.

It can write content, analyze data, draft proposals, build strategies, answer questions, create SOPs, and handle just about any knowledge work you throw at it. But it's a tool — and like any tool, it's only as good as the person using it.

---

## Step 1: Create Your Account

1. Go to [claude.ai](https://claude.ai)
2. Click **Sign Up**
3. Enter your email and verify it (or sign in with Google)
4. You're in — you now have access to Claude's free tier

### Free vs Pro — When to Upgrade

| | Free | Pro ($20/month) |
|---|---|---|
| **Messages** | Limited per day | Significantly more |
| **Model access** | Claude Sonnet | Claude Opus + Sonnet + Haiku |
| **Projects** | Limited | Full access |
| **File uploads** | Basic | Extended |
| **Best for** | Trying it out, light use | Daily business use |

**Upgrade when:** You're hitting message limits, you want the most capable model (Opus), or you need Projects for custom instructions. For most Boardroom members running a business, Pro pays for itself on day one.

---

## Step 2: Set Up a Project with Custom Instructions

This is the single most important thing you'll do. Custom instructions tell Claude who you are, what your business does, and how you want it to work. Instead of explaining your business every conversation, you set it once and Claude remembers.

### How to Create a Project

1. On the left sidebar, click **Projects**
2. Click **Create Project**
3. Give it a name (e.g., "My Marketing Agency" or "Real Estate Deals")
4. Click into the project
5. Click **Set Custom Instructions** (or the gear icon)
6. Paste your custom instructions (see below)
7. Click **Save**

Now every conversation you start inside this project has your business context baked in.

### Example: Marketing Agency Custom Instructions

Here's what a simple set of custom instructions looks like for a marketing agency owner:

```
You are my AI business partner for [YOUR AGENCY NAME], a digital marketing
agency based in [CITY].

We serve small to mid-size businesses with:
- Social media management (Instagram, LinkedIn, Facebook)
- Email marketing campaigns
- Content creation (blog posts, ad copy, landing pages)

Our brand voice is professional but approachable. We avoid jargon.
Our target clients are local business owners with $500K-$5M revenue.

When I ask you to create content:
- Match our brand voice
- Include a clear call-to-action
- Keep it concise — our audience skims

When I ask for strategy:
- Ground recommendations in data and results
- Give me specific action steps, not vague advice
- Be direct about what's working and what isn't

Current priorities:
- Onboarding 3 new clients this month
- Building our content calendar for Q2
- Improving email open rates (currently at 18%)
```

That's it. 20 lines. Now every conversation in this project starts with Claude knowing your business.

**Want a template for YOUR business type?** See [03-custom-instruction-templates.md](03-custom-instruction-templates.md) for 8 ready-made templates you can copy and customize.

---

## Step 3: Upload Key Documents

Projects let you upload files that Claude can reference in every conversation. This is where things get powerful.

**What to upload:**
- Your brand guide or style guide
- SOPs or process documents
- Pricing sheets
- Client onboarding docs
- Past content examples (so Claude can match your style)
- Market research or competitor analysis

**How to upload:**
1. Open your project
2. Click the **+** button or drag files in
3. Claude can now reference these documents in any conversation

**Pro tip:** Upload 2-3 examples of content you've written that you're proud of. Tell Claude "match this style and tone." The output quality jumps immediately.

---

## Step 4: Your First Business Conversation

Let's do a real example. You run a contracting business and need a proposal.

**Open your project and type:**

```
I need a proposal for a kitchen renovation. Here are the details:

Client: Mike and Sarah Johnson
Property: 1,200 sq ft single-family home, built 1985
Scope: Full kitchen gut renovation - new cabinets, countertops, flooring,
lighting, plumbing fixtures, and appliances
Budget discussed: $45,000-$55,000
Timeline discussed: 6-8 weeks
Special requests: They want a large island with seating for 4

Draft a professional proposal I can send to them. Include:
- Scope of work with line items
- Estimated timeline with phases
- Payment schedule (30/30/30/10 structure)
- What's included and excluded
- Next steps to accept
```

Claude will generate a complete, professional proposal you can edit and send. What would have taken you an hour takes 3 minutes.

**The pattern:** Be specific about what you want, give Claude the details, tell it the format. Vague prompts get vague answers.

---

## Pro Tips

### Separate Your Business Areas with Projects

Don't dump everything into one project. Create separate ones:
- **"Marketing"** — content creation, social media, ad copy
- **"Operations"** — SOPs, client management, hiring
- **"Finance"** — analysis, projections, reports
- **"Sales"** — proposals, outreach, follow-ups

Each project gets its own custom instructions and uploaded documents. This keeps context clean and outputs relevant.

### Use Artifacts for Longer Content

When Claude generates something substantial — a blog post, a report, a proposal — it creates an "artifact" you can view, edit, and copy separately from the chat. Use this for any content you plan to use outside Claude.

### The "Be Specific" Principle

Compare these two prompts:

**Weak:** "Write me a social media post."

**Strong:** "Write an Instagram caption for my HVAC company promoting our spring AC tune-up special. $89 for a full inspection. Target audience: homeowners in Raleigh, NC. Tone: friendly, helpful, not salesy. Include a CTA to book through our website. Keep it under 150 words."

The strong prompt gives Claude everything it needs to produce something you can actually use. The weak prompt gives you something generic you'll have to rewrite anyway.

### Iterate, Don't Restart

If the first output isn't perfect, don't start a new conversation. Tell Claude what to fix:
- "Make the tone more casual"
- "Add specific numbers and data points"
- "Shorten this to half the length"
- "Rewrite the intro — it's too generic"

Claude gets better with each iteration because it has the full conversation context.

---

## What's Next

- **Grab your template:** [03-custom-instruction-templates.md](03-custom-instruction-templates.md) — 8 templates by business type
- **Browse ready-made prompts:** [04-prompt-library.md](04-prompt-library.md) — 30 prompts you can use today
- **Level up your approach:** [06-strategies-and-patterns.md](06-strategies-and-patterns.md) — advanced strategies
- **Want the power tool?** [02-claude-code-quickstart.md](02-claude-code-quickstart.md) — Claude Code for developers
