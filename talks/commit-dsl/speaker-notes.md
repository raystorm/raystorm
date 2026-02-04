
## **1. Why I Care About Commits**

Everyone writes commit messages.  
Almost no one is taught how.

Most developers treat them as an afterthought — 
a chore, a speed bump between “I wrote the code” and “I want to push the code.”

But commit messages are history.  
They’re a timeline of what was done and when.  
They outlive engineers, teams, architectures, and sometimes entire companies.  
And they’re the only place where intent is captured — immutably —
at the exact moment of change.

So I want to begin with a simple truth:

> “I didn’t set out to design a system. I just wanted my future self to understand what I did.”

That’s it — that’s the heart.  
This whole talk starts with a very simple desire:  
**not to confuse myself six months later.**

From that simple goal — *keep it simple, keep it readable* — a system was born.  
Not because I planned it, but because **clarity demanded refinement.**

---

## **2. Era One — Pre‑Markdown: Instinct, Not Intention**

The early days.

Plain text was king. Stack Overflow didn’t exist yet.  
Answers were buried in blog posts, in forums, in IRC, or *gasp* — books.

Text formatting was simple.  
It was folklore.  
It was non‑standard.  
It was *netiquette*.  
This was before Markdown was born.

I was new to the industry.  
I did what I had to do to survive.  
I learned that commits are history —
and sometimes the commit record is all you have for a change.  
Not all commit messages help. Some hurt.

So I started writing plain‑text notes,
using the common internet formatting of the time to add readability and highlight what mattered.  
And I started enumerating key changes with bullets,
so I could quickly tell what changed in a commit without opening a full diff or patch.

This wasn’t a design.  
This wasn’t a system.  
It was just: **write a message future me will understand.**

---

Here it is, clean, complete, and with your chosen line integrated exactly as you shaped it.  
No extra commentary — just the section.

---

## **3. Era Two — Markdown: When Readability Found a Standard**

Then Markdown arrived.

Up to this point, formatting was folklore — whatever worked in plain text.  
But Markdown took all those scattered habits and turned them into a shared language.

Suddenly:

- `*`, `-`, and `+` weren’t just characters — they were bullets
- emphasis had rules
- structure had rules
- readability had rules

For the first time, text had a standard that matched what I was doing.

I didn’t adopt Markdown because it was new.  
I adopted it because it codified what I was already trying to do — make things legible.  
It made my habits shareable.  
And I don’t mean “shareable” like this talk today.  
I mean shareable so future me — or future you — could understand what I wrote and did.

Markdown gave names to patterns I’d been using for years without realizing it.

I had a moment of clarity — a moment where the future is obvious and inevitable.  
Long before GitHub, long before IDEs rendered commit messages nicely, I chose to prepare.

**“Someday commit messages will be rendered as Markdown.  
And I want to be ready when that happens.”**

Once I had that moment of clarity, I aligned my habits with Markdown early.  
Not because I was designing a system, but because Markdown gave me one.

---

## **4. Era Three — Semantics: When Formatting Became Meaning**

Era Three is when I noticed that Markdown alone wasn’t enough.

Formatting was nice. It was pretty. But it lacked meaning.  
Using `*` for every bullet looked good, but it didn’t add value.

And Markdown supported other bullets — `+` and `-`.  
If I used them intentionally, maybe I could encode meaning into the formatting.  
Maybe the list could *say* something instead of just *look* nice.

So I started experimenting.

`+` began to mean **added**.  
`-` began to mean **removed**.  
And `*` stayed behind to mean everything else —
the changes, the refinements, the adjustments.

This was also the period where I started distilling.  
Not just the bullets, but the bullet entries.  
Not every change — and not every file — belongs in a commit message.  
Commit messages are for important details, not *every* detail.

This is where the bullets stopped being pretty  
and started being *true*.


### **The Invariants — When Meaning Became Rules**

Once the bullets had meaning, the meaning needed boundaries.

If `+` meant **added**, then the entry had to describe what was added.  
If `-` meant **removed**, then the entry had to describe what was removed.  
And if a change didn’t fit either one, it belonged under `*`.

No exceptions. No clever workarounds.  
No “I’ll just put it here because it’s easier.”

Clarity demanded semantics.  
Semantics demanded consistency.  
Consistency demanded discipline.  
And discipline demanded invariants —
rules that held, even when I disagreed.

The bullets weren’t decoration anymore.  
They were commitments. They had meaning. They had truth.  
They were the reality of the change, written plainly, without embellishment.

**This is where the formatting era ended  
and the semantic era began.**

---
Here is **all of Era Four**, fully updated with the *plain‑language discovery* integrated exactly where it belongs.  
No commentary. No scaffolding. Just the section.

---

# **5. Era Four — Codifying the Style Guide: Writing It Down**

I knew I had a system. I’d known it for years.  
I realized it back in the semantic era —  
when the bullets stopped being pretty and started being true.  
I just never wrote it down.

To me, it felt like a personal quirk.  
Like my code formatting preferences.
It was just *my* way of writing commits, nothing more, nothing less. 

As the system grew, I realized something:  
I wish I’d had this when I was new —  
it would’ve spared me a lot of trouble.  
Maybe someone new today would want it too.

That was the moment.  
Not a grand revelation — just a quiet recognition that writing it down
might help someone else avoid the friction I lived through.

So I decided to try.

I opened a chat with Microsoft Copilot and pasted in a log of past commits —  
not to generate a guide, but to get an outside view of my own habits.

And that’s when I realized how deeply ingrained the rules were.  
My commits were consistent — **all** of them.  
I was excavating rules and patterns I had followed for years,  
but had never named or written down before.

I didn’t do this in one session.  
I spent weeks documenting — writing, refining, tightening.

As new edge cases came up, I’d ask the AI:

**“I know this is how I would commit this.  
Do the rules agree? Are they clear?”**

And every time, it showed me something important:

- how flexible the system already was
- how battle‑tested it had become
- how much of it I had internalized without naming

It helped me reorganize concepts I assumed were obvious —  
concepts that were *not* actually written down.  
It helped me “state the obvious,”  
which is always harder than it sounds.

Plain language was the biggest example.  
I thought it was self‑evident —  
of course commit messages should use simple, direct language.  
But it wasn’t written anywhere. It wasn’t named. It wasn’t even mentioned.  
It was *assumed*.
But once I wrote it down, and made it explicit, it reshaped the entire guide.

And it helped me test the edge cases —  
the places where a system either breaks or proves itself.

The documentation didn’t create the style.  
**It revealed it.**  
Line by line. Rule by rule. Commit by commit.

And for the first time, the style became something I could teach —  
because I finally wrote it down.

---

# **6. Era Five — The AI Experiment: Pressure‑Testing the System**

Once the style guide existed on paper, I wanted to know if it actually worked.  
Not in my head. Not in theory. In practice.

So I did something simple:  
**I asked Amazon Q to write a commit using my rules.**

Not to replace me. Not to automate anything.  
Just to see if the system held up when someone — or something — else used it.

And this is where things got interesting.

It followed the rules so literally that it exposed every place where my rules  
were vague, or implied, or assumed.

It showed me where I’d made writing assumptions I’d never stated.  
Where it followed the positive but missed the implied negative.  
Where it used the formatting but didn’t understand the Markdown behind the syntax —  
things I assumed were obvious, or things the early guide didn’t explain clearly.

And every time Q got confused, it wasn’t Q’s fault. It was mine.

But here’s the thing:  
it didn’t take dozens of commits to fix.  
It took maybe four.  
A few sharp misses, a few fast refinements, and the system snapped into place.

This wasn’t automation. This wasn’t outsourcing. This wasn't even teaching.
This was testing, checking to see if the system could survive outside my head.

Through this simple experiment,
the guide became something stronger than a personal preference.  
It became something teachable. 
Something repeatable.  
Something durable.  
Something referencable.

---

# **6. Era Six — When the System Became an Artifact**

Once the guide was tested, something changed.

The system became something I could point to —  
an artifact with edges, boundaries, and rules.

For the first time, the style was:

- documented
- explicit

That’s what “referencable” really meant.

AI didn’t make the system clearer.  
It made the system *visible* —  
a thing that could be referenced, edited, used.

---

# **7. What Developers Get From This System**

Once the system became an artifact — documented, explicit, visible —
something unexpected happened.

> **I don’t write my own commits anymore.  
> My AI in my IDE knows what changed and writes them for me.  
> All I do is copy/paste.**

And the only reason it works is because the system is:

- semantic
- structured
- intention‑revealing
- and referencable

Once the rules were clear, the AI could follow them.  
And once the AI could follow them, the workflow changed.

But this isn’t really about AI.  
It’s about what *you* get when your commit style becomes a system instead of a habit.

---

## **7.1 Immediate, personal benefits**

Developers get:

- **Faster skimming** — commits become a table of contents for the work
- **Cleaner diffs** — the bullets tell you what changed before the code does
- **Better reviews** — reviewers understand intent before they see implementation
- **Lower cognitive load** — no more guessing what happened or why
- **Clearer debugging** — history becomes a map, not a maze
- **Predictable structure** — every commit reads the same way, every time

---

## **7.2 Team‑level benefits**

Teams get:

- **A shared mental model** — everyone speaks the same change language
- **Less confusion** — no more “what does this commit even mean?”
- **Better onboarding** — new devs can skim history and understand the project
- **Consistent communication** — commits become a stable interface between people
- **A readable project history** — the repo tells a coherent story

Most teams already use **PR templates** or **issue templates** to create structure
at the review level — sections for context, changes, testing, screenshots.

This commit system does the same thing,  
but at the *commit* level, earlier in the workflow.

It gives every commit the same kind of predictable structure that PR templates give to pull requests:

- clear sections
- consistent semantics
- a shared language for change

So instead of trying to impose order *after* the work is done,  
this commit system builds that order *as the work is happening*.

Commits become the micro‑template.  
PRs become the macro‑template.  
And the two reinforce each other.

---

## **7.3 AI‑level benefits**

And then there’s the part no one expects:

- **A style guide that AI can follow**
- **Automatic commit generation that matches your voice**
- **A workflow upgrade with almost no overhead**

I didn’t design the system for AI.  
I designed it for clarity.  
AI just happens to thrive on clarity.

The system wasn’t built for machines —  
but machines are the first things that can use it perfectly.

---

## **Key idea:**
**A system built for humans becomes even more powerful when AI can follow it too.**

---

# **8. How to Build Your Own System**

The key isn’t adopting my system.  
The key is finding a system that **you already follow every time**.

A system that’s regular.  
Implicit.  
Something you do the same way whenever the situation appears —  
even if the rules aren’t written down,  
or they’re only partially documented,  
or they only exist in your head.

Preferably, it’s a system where the actions, the results, the artifacts  
are already present, either as a byproduct of the work, or intentionally created.

Because once something is written down,  
an AI can inspect it.  
It can infer the patterns you’re already following.  
It can excavate the hidden rules you’ve been following for years  
without ever naming them.

That’s the real trick:

**Writing creates clarity.  
AI thrives on explicit clarity.**

You don’t need to invent a new system.  
You just need to surface the one you already follow  
every time the work demands it.

**Once it becomes visible,  
you can refine it.  
You can improve it.  
You can share it.  
You can teach it.  
You can hand it to your future self.  
And yes — you can hand it to AI.**

The point isn’t to build a perfect system.  
The point is to build a visible one.

Because once your system becomes an artifact,  
you're ready for the next leap.

---

# **9. Stewardship - Your turn**

Systems aren’t built just to build systems.  
Systems, when built with care, can become acts of stewardship.

For the people who inherit the work.  
For the teams who depend on it.  
For the communities shaped by the outcomes.  
For the future maintainers who will never meet the original authors  
but will live with their decisions every day.

Once a system becomes visible,  
once its rules and patterns can be inspected,  
once the work becomes an artifact instead of a memory,  
the responsibility shifts.

Clarity becomes care.  
Legibility becomes longevity.  
Explicitness exemplifies transparency.

AI doesn’t change that responsibility.
AI amplifies responsibility.

Because visible systems can be  
extended, examined, refined, trusted,  
and carried forward.

It’s not about size.
It’s about durability.
It’s about transparency.
It’s about the humility to be understood
and the courage to be seen and be wrong.

The work is to make visible what already exists.
A system already used.
Now defined with purpose.
A system ready to be improved.

Once a system becomes an artifact,  
the next leap becomes possible.

That's what's next.
That next leap.  
Design your own system.  
It's out there, waiting to be found, to be documented.
Do it for you, for your team, for the future.

---
