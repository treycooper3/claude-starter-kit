# Claude Code Quickstart — Set Up the CLI for Your Projects

| Field | Value |
|-------|-------|
| **Difficulty** | Intermediate — Advanced |
| **Time** | 15-20 minutes |
| **What You Need** | Terminal access, Node.js installed |
| **Cost** | API usage (pay-per-token) or included with Claude Max ($100/month) |

---

> **Key takeaway:** Claude Code doesn't just answer questions — it reads your codebase, edits your files, runs your scripts, and works alongside you in the terminal. It's the Agent layer in the WAT framework.

---

## What Is Claude Code?

Claude Code is a command-line tool that lives in your terminal. Unlike Claude.ai (which is a chat in your browser), Claude Code sits inside your project and understands your entire codebase. It can:

- Read every file in your project
- Edit files directly (with your approval)
- Run terminal commands
- Search your codebase
- Follow instructions from a CLAUDE.md file you write

If Claude.ai is like texting a smart advisor, Claude Code is like having a developer sitting next to you who already read every file in your project.

---

## Who This Is For

- Developers building software or automations
- Technical founders managing their own codebase
- AI Systems track members building and selling AI tools
- Anyone writing Python scripts, building websites, or working with APIs

If you're not writing code, stick with [Claude.ai](01-claude-ai-quickstart.md). It's the right tool for non-technical work.

---

## Step 1: Install Node.js

Claude Code runs on Node.js. If you don't have it:

**Mac:**
```bash
brew install node
```

**Windows:**
Download from [nodejs.org](https://nodejs.org) and run the installer.

**Verify it's installed:**
```bash
node --version
```

You should see a version number (v18 or higher).

---

## Step 2: Install Claude Code

```bash
npm install -g @anthropic-ai/claude-code
```

That's it. Claude Code is now available globally on your machine.

---

## Step 3: Authenticate

You have two options:

**Option A: API Key (pay-per-use)**
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Create an API key
3. Set it in your terminal:
```bash
export ANTHROPIC_API_KEY="your-key-here"
```
Add this to your shell profile (`~/.zshrc` or `~/.bashrc`) so it persists.

**Option B: Claude Max ($100/month)**
If you have a Claude Max subscription, Claude Code is included. It will prompt you to log in on first run.

---

## Step 4: Run Claude Code

Navigate to any project directory and type:

```bash
cd your-project
claude
```

Claude Code starts, reads your project, and is ready to work.

---

## The CLAUDE.md File — This Is the Key

A `CLAUDE.md` file is a markdown file at the root of your project that Claude Code reads automatically every time you start a session. It's your project's instruction manual for Claude.

### Where It Goes

```
your-project/
├── CLAUDE.md          <-- Right here, at the root
├── src/
├── package.json
└── ...
```

### What to Put in It

Your CLAUDE.md should tell Claude:
- What this project is and what it does
- The tech stack and key dependencies
- How to run the project (build, test, deploy commands)
- File structure — where things live
- Coding standards and conventions
- What NOT to do

### Example: Minimal CLAUDE.md for a Business Website

```markdown
# Project Instructions

## What This Is
Marketing website for [Your Company]. Built with Next.js and Tailwind CSS.

## Tech Stack
- Next.js 14, React 18, TypeScript
- Tailwind CSS for styling
- Deployed on Vercel

## How to Run
- Dev server: `npm run dev`
- Build: `npm run build`
- Tests: `npm test`

## File Structure
- `src/app/` — Pages (Next.js App Router)
- `src/components/` — Reusable components
- `public/` — Static assets (images, fonts)

## Standards
- Use TypeScript strict mode
- Prefer const over let
- Components go in their own files
- Run `npm run build` before committing to verify no errors

## Do NOT
- Modify environment variables or .env files
- Push directly to main — always use a branch
- Add console.log to production code
```

20 lines. Now Claude Code knows your project and follows your rules every session.

**Want a template for YOUR project type?** See [03-custom-instruction-templates.md](03-custom-instruction-templates.md) — the templates work for both Claude.ai and Claude Code.

---

## Rules Files — Global Standards

Beyond CLAUDE.md (project-specific), you can set global rules that apply across all your projects.

### Where They Go

```
~/.claude/rules/
├── coding-style.md
├── git-workflow.md
├── security.md
└── testing.md
```

### When to Use What

| | CLAUDE.md | Rules Files |
|---|---|---|
| **Scope** | One project | All projects |
| **Location** | Project root | `~/.claude/rules/` |
| **Use for** | Project context, file structure, how to run | Universal standards, coding style, security |
| **Example** | "This is a Next.js app deployed on Vercel" | "Always use const over let" |

### Example Rules File: `~/.claude/rules/coding-style.md`

```markdown
# Coding Style

- Prefer immutability: use const over let, avoid mutations
- No console.log in production code
- Keep files under 300 lines — split when they grow beyond that
- Functions should do one thing well
- Descriptive variable names — no single-letter names except loop counters
- Prefer early returns over deep nesting
- Delete dead code immediately — don't comment it out
```

---

## Your First Session

Here's what a real session looks like:

```
$ cd my-project
$ claude

Claude: I've read your project. This is a Next.js marketing website with
12 pages and 8 components. What would you like to work on?

You: Add a contact form to the contact page that sends submissions to
our email via a Resend API integration.

Claude: I'll need to:
1. Create a ContactForm component
2. Add an API route for form submission
3. Install the Resend package
4. Wire it up on the contact page

Should I proceed?

You: Yes

Claude: [Creates the files, installs the package, shows you each change
for approval]
```

You review each change before it's applied. Nothing happens without your approval.

---

## Pro Tips

### Keep CLAUDE.md Concise
Under 100 lines for the main file. If you need more detail, put it in separate files that Claude can read when needed (like `docs/architecture.md`).

### Use `/compact` When Context Gets Heavy
Long sessions eat context. Type `/compact` to summarize the conversation and free up space. Do this before starting a new task in the same session.

### Build the WAT Framework Locally
If you're in the AI Systems track, structure your project like this:

```
your-project/
├── CLAUDE.md        # Agent instructions
├── workflows/       # Markdown SOPs
├── tools/           # Python/JS scripts
└── .env             # API keys (never commit)
```

Claude Code reads the CLAUDE.md, follows your workflows, and executes your tools. That's the WAT framework in action.

### Always Verify After Changes
After Claude Code makes changes, run your build and tests:
```bash
npm run build
npm test
```

Don't trust it blindly. Verify. This is the same principle from the testing rules: "Don't claim something works without running it."

### Stage Specific Files When Committing
```bash
git add src/components/ContactForm.tsx src/app/api/contact/route.ts
git commit -m "feat: add contact form with Resend integration"
```

Never `git add .` — you might accidentally commit sensitive files.

---

## Connecting to the WAT Framework

If you've done Lesson 1.1.2 (The WAT Framework), Claude Code is the **Agent layer** in action:

| WAT Layer | What It Is | In Claude Code |
|-----------|-----------|----------------|
| **Workflows** | Markdown instructions | Your CLAUDE.md + files in `workflows/` |
| **Agents** | AI decision-making | Claude Code itself — reads instructions, makes decisions |
| **Tools** | Deterministic scripts | Scripts in `tools/` that Claude Code can execute |

The separation is what makes it reliable. Claude Code handles the thinking. Your scripts handle the execution. Your CLAUDE.md keeps everything on track.

---

## What's Next

- **Grab a CLAUDE.md template:** [03-custom-instruction-templates.md](03-custom-instruction-templates.md) — 8 templates by business/project type
- **Build repeatable workflows:** [05-workflow-templates.md](05-workflow-templates.md) — SOP templates Claude Code can follow
- **Advanced patterns:** [06-strategies-and-patterns.md](06-strategies-and-patterns.md) — power moves for Claude Code users
- **Start the course:** Lesson 1.2.1 in the AI Systems Playbook — build your first AI agent
