# Building Your First AI Workflow

A workflow is a repeatable sequence of steps you use Claude for — 
so instead of starting from scratch every time, you have a system.

This guide shows you how to build one, even if you have never done 
anything like this before.

---

## What a workflow actually is

A workflow is just: a trigger + a prompt + what you do with the output.

**Example — Weekly Report Workflow:**
- Trigger: Every Friday afternoon
- Prompt: Paste your week's notes into Claude with a fixed prompt 
  that turns them into a summary
- Output: A formatted weekly report ready to send to your manager

That's it. No automation. No code. Just a repeatable process that 
saves you time every single week.

---

## The three types of workflows for non-technical users

**Type 1: The Repeating Task**
Something you do regularly that always follows the same pattern.
Examples: weekly reports, client emails, meeting summaries, content drafts.

**Type 2: The Processing Pipeline**
You receive raw input (notes, articles, data) and need it transformed 
into something useful.
Examples: turning research into summaries, converting meeting notes 
into action plans, transforming rough ideas into structured documents.

**Type 3: The Thinking Partner**
You face the same type of decision or problem repeatedly and want a 
consistent way to think it through.
Examples: evaluating opportunities, reviewing plans, stress-testing ideas.

---

## How to build your first workflow in 4 steps

**Step 1: Identify a repeating pain point**

Ask yourself: what do I do regularly that takes longer than it should 
or that I dread doing?

Pick one thing. Just one. The goal is to build one working workflow, 
not to automate your entire job in a day.

**Step 2: Write a base prompt**

A base prompt is a template with [brackets] where the variable 
information goes. The fixed parts are your instructions. The bracketed 
parts change each time.

Example base prompt for meeting summaries:
```
I attended a meeting about [TOPIC]. Here are my raw notes:

[PASTE NOTES]

Please produce: a 1-sentence purpose statement, bullet-point decisions 
made, action items with owners and deadlines, and open questions 
that need follow-up.
```

**Step 3: Test and refine**

Run the prompt with real input 3 times. After each run, note what was 
off and adjust the prompt. By the third run, you will have a prompt 
that consistently produces what you need.

**Step 4: Save and systematize**

Save your finished prompt somewhere you can find it easily — a notes 
app, a document, a bookmark. Create a simple habit around using it: 
same time, same trigger, same process.

---

## Your first workflow assignment

Pick one of these — whichever fits your work best:

**Option A:** Every time you finish a meeting, paste your notes into 
the Meeting Summarizer prompt from this library. Send the output to 
attendees within 30 minutes.

**Option B:** Every time you need to write a professional email you 
feel uncertain about, use the Email Writer prompt first. Edit the 
output, then send.

**Option C:** Once a week, paste everything you learned that week into 
Claude and ask it to identify the 3 most important insights and what 
you should do differently as a result.

Do one of these consistently for two weeks. At that point, you will 
understand workflows better than most people who have been using AI 
for months.

---

## Where to go from here

Once your first workflow is running, look for the next repeating pain 
point. Build a workflow for that. Repeat.

Within a few months, you will have a personal system of AI workflows 
that handles the most tedious and cognitively draining parts of your 
work — and you will have built it entirely without code.
