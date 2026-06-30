# Strategies and Patterns — The Boardroom

> **Key takeaway:** The difference between people who get mediocre AI output and people who get business-changing results isn't intelligence — it's approach. These patterns are what separate the two.

---

## The 80/20 of Working with Claude

Most of the value comes from a few simple habits. Master these before anything else.

### 1. Be Specific About What You Want

The number one reason people get bad output from Claude is vague prompts.

**Weak:** "Write me some content about my business."

**Strong:** "Write a 1,200-word blog post about how small business owners can automate their invoicing. Target audience: service-based businesses doing $200K-$1M in revenue. Tone: practical and direct, no fluff. Include 3 specific tools they can use today. End with a CTA to book a call with us."

The strong version tells Claude the format, length, topic, audience, tone, specifics to include, and what to do at the end. Claude delivers exactly what you need because you told it exactly what you need.

### 2. Give Context Before Asking for Output

Claude doesn't know your business unless you tell it. Before asking for a deliverable, front-load the context:

```
Context: I run a residential HVAC company in Raleigh, NC. We serve
homeowners within a 30-mile radius. Our average job is $3,000-$8,000.
Peak season is June-September. We're trying to book more maintenance
contracts because they provide predictable recurring revenue.

Task: Write 3 Facebook ad variations promoting our $89 AC tune-up
special. Target homeowners. Tone is friendly and helpful, not pushy.
```

The context paragraph takes 30 seconds to write. The output quality jumps dramatically.

### 3. Show Examples of What "Good" Looks Like

If you have a blog post, email, or proposal you've written that you're proud of, show it to Claude:

```
Here's an example of a proposal I wrote that won the client.
Match this tone and structure for the new proposal:

[paste your example]
```

Claude picks up on your voice, formatting, and approach. This works better than trying to describe your style in words.

### 4. Iterate Instead of Hoping for Perfection

Nobody gets perfect output on the first try. The workflow is:

1. Give Claude a clear prompt
2. Review the output
3. Tell Claude what to fix ("make it shorter," "more specific numbers," "less formal tone")
4. Repeat until it's right

Each iteration gets closer because Claude has the conversation context. Don't restart — refine.

---

## The Systems Thinking Approach

Stop using Claude for one-off questions. Start building reusable systems.

### Build Reusable Prompts

When you write a prompt that produces great results, save it. Don't write it from scratch next time. Keep a file (or use the [Prompt Library](04-prompt-library.md)) with your best prompts, customized for your business.

### Create Prompt Chains

Complex tasks work better as a series of prompts where each output feeds the next:

**Example — Writing a case study:**
1. **Prompt 1:** "Here are the raw results from our client project. Extract the key metrics, the before/after comparison, and the timeline."
2. **Prompt 2:** "Using those metrics, write a case study following this structure: Challenge, Approach, Results, Client Quote placeholder."
3. **Prompt 3:** "Now write a LinkedIn post summarizing this case study. Keep it under 200 words with a hook in the first line."

Each step is focused and clear. The output of step 1 becomes the input for step 2. This is how you get consistently great results — not by asking Claude to do everything in one shot.

### Document What Works

When a prompt or workflow produces great results, write it down. When something doesn't work, note what you changed to fix it. Over time, you build a library of proven approaches specific to your business.

---

## Context Loading Strategies

The more relevant context Claude has, the better the output. Here are your options, from simplest to most powerful.

### Custom Instructions (Persistent Context)

Set up once, applies to every conversation in that Project (Claude.ai) or project (Claude Code). This is your baseline — business overview, brand voice, standards.

See [03-custom-instruction-templates.md](03-custom-instruction-templates.md) for templates.

### Document Uploads (Reference Material)

Upload files Claude can reference: brand guides, SOPs, past work, pricing sheets, market research. Claude reads these and pulls relevant information into its responses.

**What to upload:**
- Your best work (so Claude can match the style)
- Process documents (so Claude follows your standards)
- Data files (so Claude can analyze your actual numbers)

### The Role + Context + Task + Format Structure

For individual prompts, this four-part structure consistently produces the best results:

```
Role: You are a [ROLE — e.g., "senior copywriter specializing in B2B SaaS"].

Context: [BACKGROUND — what the project is, who the audience is,
what's happened so far, any constraints].

Task: [SPECIFIC ACTION — what you want Claude to produce].

Format: [OUTPUT SPECS — length, structure, tone, what to include/exclude].
```

You don't need to label the sections. But including all four elements — even naturally in a paragraph — dramatically improves output quality.

---

## Multi-Step Workflows with Claude

For complex deliverables, break the work into steps instead of asking for everything at once.

### The Research-Draft-Refine Pattern

1. **Research:** "Research [topic]. Give me the key findings, data points, and insights organized by theme."
2. **Draft:** "Using that research, draft a [deliverable] following this structure: [outline]."
3. **Refine:** "Review the draft. Tighten the language, strengthen the weakest section, and make sure the CTA is clear."

Each step produces better output than trying to do all three in one prompt.

### The Self-QA Pattern

After Claude produces a deliverable, ask it to review its own work:

```
Now review what you just wrote. Check for:
- Factual claims that aren't supported
- Sections that are too vague or generic
- Anything that doesn't match the brand voice I described
- Missing CTAs or next steps

Flag any issues and suggest specific fixes.
```

This catches problems before you do. It's not perfect — you still need to review — but it catches 80% of the obvious issues.

### The Devil's Advocate Pattern

Open a separate conversation and paste Claude's output:

```
I'm considering publishing this [blog post / proposal / email sequence].
Play devil's advocate. What's weak? What would a skeptical reader
push back on? What's missing? Be direct — I need honest feedback,
not encouragement.
```

Fresh context means Claude approaches it without the bias of having written it.

---

## Delegation Patterns

Claude is a tool, not a replacement for your judgment. Know what to delegate and what to keep.

### Give to Claude
- First drafts (content, proposals, emails, SOPs)
- Data analysis and pattern recognition
- Research and summarization
- Formatting and restructuring
- Brainstorming and generating options
- Repetitive tasks with clear rules

### Keep for Yourself
- Final editorial decisions
- Strategy and priorities
- Relationship management (what to say to a specific client)
- Creative direction (what your brand stands for)
- Quality control (the final review before anything goes out)
- Anything involving money, contracts, or legal commitments

### The 90% Principle

Claude gets you to 90% in 10% of the time. You do the last 10% — the polish, the judgment calls, the personal touches. That's the sweet spot. You're not trying to remove yourself from the process. You're trying to remove the grind.

---

## Common Mistakes That Kill Your Results

### Vague Prompts
"Write me some content" → generic output. Always specify: what, for whom, in what format, what tone, how long, and what to include.

### No Context
"You should already know this" — Claude doesn't. It knows nothing about your business unless you tell it. That's what custom instructions and context loading are for.

### Not Iterating
"That's not what I wanted" → end conversation → start over. Don't restart. Tell Claude what to fix. It gets better with each round because it has the full conversation.

### Treating Claude Like a Search Engine
Asking questions ("What are the best marketing strategies?") instead of giving tasks ("Write a marketing plan for my HVAC company targeting homeowners in Raleigh who need AC replacements"). Tasks produce usable output. Questions produce generic information.

### Not Using Custom Instructions
Starting from scratch every conversation. You explain your business, your voice, your standards — every single time. Set up custom instructions once and every conversation starts from a foundation. This is the single highest-ROI thing you can do.

---

## Claude Code Power Moves

For members using Claude Code (the CLI), these patterns unlock another level.

### The CLAUDE.md + Rules Architecture

```
~/.claude/rules/           # Global — applies to all projects
├── coding-style.md        # How you write code
├── git-workflow.md        # How you handle version control
├── security.md            # What never goes in code
└── testing.md             # How you verify things work

your-project/
├── CLAUDE.md              # Project-specific context and instructions
├── workflows/             # SOPs Claude Code can follow
├── tools/                 # Scripts Claude Code can execute
└── .env                   # Secrets (never committed)
```

Global rules handle universal standards. CLAUDE.md handles project-specific context. Together, Claude Code operates within your constraints every session.

### Workflow Files as Instructions

Save your workflow SOPs (from [05-workflow-templates.md](05-workflow-templates.md)) in your project. Claude Code reads them and can follow the steps when you say "run the content creation workflow for [topic]."

### MCP Servers for Extended Capabilities

MCP (Model Context Protocol) servers extend what Claude Code can do — connect to databases, APIs, services, and more. If you're building tools for clients, MCP servers let Claude Code interact with their systems directly.

### The /compact Habit

Long sessions eat context window. When you notice Claude Code repeating itself, missing details, or losing track of what it already did, type `/compact`. It summarizes the conversation and frees up space. Do this before starting a new task in the same session.

---

## Building Your Personal AI Operating System

Don't try to build everything at once. Start small, prove it works, then add.

### Step 1: One Workflow
Pick the task you do most often that you hate most. Write the workflow. Run it with Claude 5 times. Refine it until it's solid.

### Step 2: Track the Time Saved
Before: "This task took me 2 hours every week."
After: "This task takes me 15 minutes with Claude."
That's 7+ hours a month. Real numbers. This is how you justify upgrading tools and investing more time in building systems.

### Step 3: Add the Next One
Now pick the second most impactful task. Write the workflow. Run it. Refine it.

### Step 4: Share Your Wins
Post in The Boardroom. "I automated my weekly reporting — went from 2 hours to 15 minutes." Other members learn from your approach. You build credibility. The community gets stronger.

### The Compounding Effect

Each automation frees time to build the next one. The first one takes the longest. The second is faster because you understand the pattern. By the fifth, you're building systems in an afternoon that save hours every week.

This is what Lesson 1.1.1 calls the compounding effect — and it's real. The members who build one system, then the next, then the next, are the ones who break through. The ones who learn about it and don't build anything stay stuck.

Build the first one. The rest follows.

---

## What's Next

- **Start with the basics:** [01-claude-ai-quickstart.md](01-claude-ai-quickstart.md) — get set up in 15 minutes
- **Grab your template:** [03-custom-instruction-templates.md](03-custom-instruction-templates.md) — personalize Claude for your business
- **Use ready-made prompts:** [04-prompt-library.md](04-prompt-library.md) — 30 prompts you can run today
- **Build your first workflow:** [05-workflow-templates.md](05-workflow-templates.md) — repeatable SOPs
- **Go deeper:** AI Systems Playbook (Track 1) — the full curriculum
