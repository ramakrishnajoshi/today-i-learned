# AI, Burnout, and Whether Junior Engineers Are Still Learning

**Source:** [Reddit - r/developersIndia](https://www.reddit.com/r/developersIndia/comments/1x6cnyr/burnt_out_i_dont_see_how_ai_will_ever_replace/)

A 2025 grad (u/Extension_System_775) posts while burnt out, arguing that AI can write code but can't supply human judgement about *how* it should be written or how it fits the wider product/system — and worries that, as a junior, he's barely learning anything because he isn't handwriting code. The thread is less about "will AI replace SWEs?" in the abstract and more about the day-to-day reality: workloads have gone *up*, not down.

> Full thread retrieved via the pasted Reddit JSON (post + 53 comments, sorted by score). Direct/API access was blocked, so this note is based on that export.

---

## ⭐ Memorable
> "I haven't seen a single person in my company who's workload has actually reduced because of AI, there's just constant and long term burnout"
> — **u/Bulging_Bicepss** (top comment, 167 upvotes)

---

## Big Picture

### Main Themes & Recurring Patterns
* **AI didn't reduce the workload — it raised the ceiling.** The highest-voted sentiment is that nobody's workload actually shrank; instead expectations rose and burnout got worse. Several named it **Jevons Paradox**: cheaper/faster code just creates demand for *more* code.
* **The job-security paradox.** Some find grim comfort in being overloaded — lots of work means lower layoff risk. The flip side: the day the work genuinely reduces is the day roles get cut. Multiple commenters pointed at **corporate greed / management decisions**, not AI itself, as the real threat.
* **The role is shifting from writing to reviewing.** "We're all project managers now." The OP notes reviewing AI-generated code has become the heftiest part of the job; others agree that reviewing AI code is painful unless you are hyper-specific in prompts.
* **The learning worry for juniors.** The OP's core anxiety: if you don't handwrite code, your learning is minimal. A practical counter-pattern offered: plan and brainstorm with AI, then handwrite some working code yourself to build real understanding (and make later review easier).
* **AI as a tool vs. AI as a replacement.** A recurring line: AI will replace "coding monkeys," not engineers; "AI won't replace you — a human using AI will."

### Important Disagreements & Caveats
* **The compiler/assembly analogy — and the pushback.** Optimists argued we'll stop reading AI output just like we stopped reading compiler-generated assembly, pointing to Spec-Driven Development and AI handling monitoring/debugging/fixing. Skeptics rejected the analogy sharply: compilers translate **deterministically** and are fully auditable, whereas an LLM "can go off the rails with one single misdirection" — so there is no reliable higher-level layer yet ("English?").
* **How optimistic to be.** Some commenters insist AI is improving by leaps and that one competent senior can already replace a team, citing people rewriting libraries or cloning large apps solo. Others counter that if LLMs truly replaced SWEs, companies like Anthropic wouldn't be paying seven figures for them.
* This is a thread of **working engineers venting and debating**, not a settled conclusion. The optimistic takes were often downvoted; the burnout takes were upvoted — but that reflects the room, not proof either side is right.

---

## What I Want to Remember
1. **"Faster" rarely means "less work."** When a tool makes output cheaper, expectations expand to fill the gap (Jevons Paradox). Budget for that instead of expecting AI to buy back your time automatically.
2. **Watch the real risk signal.** More work ≈ more short-term security; a sudden *drop* in workload can precede cuts. The threat is often management/economics, not the model.
3. **As a junior, protect your learning deliberately.** Brainstorm with AI, but handwrite enough code yourself to keep building understanding — speed shouldn't come at the cost of comprehension.
4. **Judge AI output; don't just accept it.** The job is moving toward review, specification, and holding responsibility — the determinism and auditability that compilers gave us aren't there yet.

---

## Original Responses Worth Preserving

> "I haven't seen a single person in my company who's workload has actually reduced because of AI, there's just constant and long term burnout"
> — **u/Bulging_Bicepss**

> "Same issue lot of work coming in / running out of team capacity / but they say use AI … but atleast I feel secured when there is lot of work to do even with using AI / most layoffs due to AI being more productive than in coming work / if there is lot of work then there is some job security"
> — **u/kimi_glm_deepseek**

> "Jevons Paradox"
> — **u/hardik-hi**

> "I dont think I felt this much fatigue and burnout pre AI. Now it is work and fighting stupid management decisions because they think AI is genie so everything is fast where as the other part of management is pushing more processes down the throat which eats up the gains of the speed we got from AI… Funnily there have been no profit because of AI"
> — **u/Evil_bitch_21**

> "Actually more than AI i am afraid of corporate greed. To increase profit they would do anything and everything"
> — **u/Capital_Rich_9362**

> "The day the work will reduce, they will fire."
> — **u/SuggestAnyName**

> "Yeah we're all project managers now."
> — **u/throwawayRaddit**

> "Fr tho, i feel even Claude ai goes around in circles unless you are hyper specific in the prompt to the point that you coding it up would be more enjoyable, reviewing ai written code is a pain in the a\*\*. What I mostly do, if there isn't deadline pressure, is to formulate a plan and brainstorm with AI and then atleast handwrite some working code. Feel it increases my understanding and also makes it easier to review any code ai adds to it"
> — **u/impunitiveCitizen**

> "Do you ever open the assembly language code a compiler generated? Do you ever care about how it should be written? The same will happen for AI writing our code. We will stop looking at it altogether."
> — **u/LogicalBeast26**

> "You don't open assembly because there's a higher level which translates DETERMINISTICALLY. Where is that layer now? English?"
> — **u/SmoothCCriminal**

> "Can you please stop using the compiler example. It's such a bad example that has been repeated to death. Compilers and assemblers and all the other deterministic and fully auditable pieces of software are not equivalent to a LLM. Very different things."
> — **u/Few-Philosopher-2677**

> "LLMs will replace coding monkeys. LLMs won't be able to replace software engineers."
> — **u/Plastic-Following867**

> "AI is not going to replace you. A human using AI would. It's your choice - you want to ride the tiger or let it chase you"
> — **u/shan23** *(downvoted in-thread, but a sharp framing worth keeping)*
