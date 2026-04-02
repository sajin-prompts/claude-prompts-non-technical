# Research & Synthesis Prompts

These prompts help you use Claude to do research faster, understand complex 
sources, and turn scattered information into clear thinking.

No coding required. No technical setup. Just copy, paste, and replace the 
parts in [brackets] with your own information.

---

## Prompt 1: The Literature Synthesizer

**What it does:** Takes multiple sources and finds the common threads, 
contradictions, and gaps — like having a research assistant read everything 
and brief you.

**Best for:** Researchers, students, analysts, journalists.

**When to use:** You have multiple articles, papers, or sources and need 
to understand what they collectively say.

**Copy this prompt:**
```
I'm going to share [NUMBER] sources on the topic of [YOUR TOPIC]. 
After I share them, please:

1. Identify the 3-5 main arguments or findings that appear across sources
2. Note where sources agree and where they contradict each other
3. Identify what questions remain unanswered across all sources
4. Give me a 3-sentence summary I could use to explain this topic to 
   someone unfamiliar with it

Here are my sources:
[PASTE YOUR SOURCES HERE]
```

**Tips:**
- Paste article text directly — you don't need links
- If you have too much text, paste the abstract or key sections
- After the response, ask Claude to "go deeper on point 2" for more detail

---

## Prompt 2: The Plain Language Explainer

**What it does:** Takes any complex concept and explains it at exactly 
the level you need — from complete beginner to advanced practitioner.

**Best for:** Anyone encountering unfamiliar terms, concepts, or fields.

**When to use:** You've hit a term or concept you don't understand and 
need it explained before continuing your work.

**Copy this prompt:**
```
Explain [CONCEPT OR TERM] to me as if I am [YOUR BACKGROUND — e.g., 
"a high school teacher", "a nurse", "a small business owner with no 
science background"].

Then:
- Give me one real-world example I can immediately relate to
- Tell me what misconceptions people commonly have about this
- Tell me what I would need to understand next if I wanted to go deeper
```

**Tips:**
- Be specific about your background — it dramatically improves the output
- If the explanation is still too complex, say: "Simpler. Assume I know nothing."
- If it's too basic, say: "I already understand X, go deeper from there."

---

## Prompt 3: The Source Evaluator

**What it does:** Helps you assess whether a source is credible, biased, 
or missing something — without needing a PhD in research methodology.

**Best for:** Students, researchers, journalists, anyone fact-checking.

**When to use:** You've found a study, article, or claim and want to know 
how much to trust it.

**Copy this prompt:**
```
I'm going to share a source with you. Please evaluate it by:

1. Identifying who wrote it and what their likely perspective or bias might be
2. Noting what evidence or methodology they use to support their claims
3. Pointing out what they don't address or what counter-evidence exists
4. Rating my confidence in this source on a scale of 1-5 with explanation
5. Suggesting what I should look for to verify or challenge the main claim

Here is the source:
[PASTE ARTICLE TEXT, ABSTRACT, OR QUOTE HERE]
```

**Tips:**
- Works on news articles, academic abstracts, blog posts, even social media claims
- Ask Claude to "find the strongest counter-argument to this source" after
- Always verify specific facts and statistics with primary sources
