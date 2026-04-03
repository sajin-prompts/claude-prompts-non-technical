# Research & Synthesis Prompts

These prompts help you use Claude to do research faster, understand complex 
sources, and turn scattered information into clear thinking.

No coding required. Copy, paste, and replace the parts in [brackets] with 
your own information.

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
You are an expert research analyst with deep experience synthesizing 
academic and professional literature across multiple disciplines.

I am a [YOUR ROLE — e.g., "graduate student", "journalist", "policy 
researcher"] working on [YOUR TOPIC]. I have [NUMBER] sources I need 
to synthesize into a coherent understanding. My goal is to [WHAT YOU 
NEED THIS FOR — e.g., "write a literature review", "brief my team", 
"understand the current state of research"].

Here are my sources:
[PASTE YOUR SOURCES HERE]

Please do the following:
1. Identify the 3-5 main arguments or findings that appear across sources
2. Note explicitly where sources agree and where they contradict each other
3. Identify what questions remain unanswered across all sources
4. Write a 3-sentence summary I could use to explain this topic to 
   someone unfamiliar with it

Rules:
- Use plain language — avoid academic jargon unless you explain it
- Be specific about which source supports which claim
- If sources are insufficient to draw conclusions, say so clearly
- Keep the synthesis objective — do not insert opinions not supported 
  by the sources
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
You are a world-class educator known for making complex ideas 
understandable to anyone, regardless of their background. You never 
talk down to people — you meet them exactly where they are.

I am [YOUR ROLE — e.g., "a primary school teacher", "a small business 
owner", "a nurse"] with no background in [FIELD OF THE CONCEPT]. I 
have encountered the concept of [CONCEPT OR TERM] and need to genuinely 
understand it — not just recognize the word, but actually understand 
what it means and why it matters.

Please do the following:
1. Explain [CONCEPT] in plain language as if I have no prior knowledge
2. Give me one concrete real-world example from my professional world
3. Tell me what misconceptions people commonly have about this concept
4. Tell me what I would need to understand next if I wanted to go deeper
5. Give me one question I can ask myself to test whether I truly 
   understand this

Rules:
- Never use technical jargon without immediately explaining it in 
  plain terms
- Use analogies from everyday life, not from the technical field itself
- If I say "simpler" at any point, drop one level further in complexity
- Prioritize understanding over completeness — it is better I truly 
  grasp the core than superficially know everything
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
You are a veteran investigative journalist and critical thinking coach 
with 20 years of experience evaluating sources, identifying bias, and 
teaching people to think clearly about evidence.

I am [YOUR ROLE] and I have found a source I want to use for 
[YOUR PURPOSE — e.g., "a report I am writing", "a decision I need 
to make", "an article I am researching"]. I need to know how much 
to trust it before I build on it.

Here is the source:
[PASTE ARTICLE TEXT, ABSTRACT, OR QUOTE HERE]

Please evaluate it as follows:
1. Identify who wrote it and what their likely perspective or bias is
2. Assess what evidence or methodology they use to support their claims
3. Point out what they do not address or what counter-evidence exists
4. Rate my confidence in this source from 1-5 with a clear explanation
5. Tell me exactly what I should look for to verify or challenge the 
   main claim

Rules:
- Be direct and honest — do not soften criticism of weak sources
- Separate facts from opinions clearly in your evaluation
- If the source is strong, say so — do not manufacture criticism
- Give me actionable next steps, not just abstract assessments
- Flag any red flags immediately, do not bury them at the end
```

**Tips:**
- Works on news articles, academic abstracts, blog posts, even social media claims
- Ask Claude to "find the strongest counter-argument to this source" after
- Always verify specific facts and statistics with primary sources
