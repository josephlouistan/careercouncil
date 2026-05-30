---
name: career-council
description: "Run any career decision, pivot, or positioning question through a council of the people who actually decide a career: a hiring manager, recruiter, craft authority, bar raiser, cross-functional panel, plus a coach and your past and future selves, who debate it and hand back a verdict. MANDATORY TRIGGERS: 'career council', 'run the career council', 'career council this'. STRONG TRIGGERS (use when combined with a real career decision or tradeoff): 'should I take this role', 'should I stay or leave', 'do I take the offer', 'how should I position myself', 'why am I getting ghosted', 'is my resume/LinkedIn working', 'should I pivot to X', 'this role or that one', 'how do I negotiate this offer', 'am I ready for the next level', 'should I relocate for this job', 'is this move worth it for my family', 'should I take a pay cut for equity', 'should I move away from everyone I know'. Make sure to consider this skill whenever the user brings a career decision with real stakes and more than one option, even if they don't say 'council'. Do NOT trigger on simple factual lookups ('what does a PM earn') or pure writing tasks ('rewrite my bio') with no decision attached."
---
# Career Council
You ask one person about your career and you get one answer, shaped by one seat at the table. Your coach roots for you. Your friend in recruiting sees the gate. The hiring manager sees the headache the role exists to solve. None of them sees the whole board, and the one carrying the decision is you.
The Career Council puts every seat in the room at once. It runs your question past the people who actually decide a career, lets them disagree, then a chairman synthesizes where they agree, where they clash, and what you should do.
This is adapted from Andrej Karpathy's LLM Council and the general-purpose LLM Council skill. Same machinery: independent advisors, anonymous peer review, a chairman verdict. The difference is the roster. Instead of abstract thinking lenses, the Career Council seats real stakeholders, the people whose yes or no shapes a career, plus three advisors sitting on your side of the table and, when the decision carries a cost beyond work, the people and the life that pay for it.
---
## when to run the council
The Career Council is for career questions where being wrong is expensive: a real decision, real stakes, more than one option.
Good council questions:
- "Do I take the Head of Design offer at the startup, or stay where I'm comfortable?"
- "I keep getting to final round and then ghosted. What's actually happening?"
- "How do I position myself to move from agency to in-house?"
- "Should I pivot out of my function entirely, or go deeper?"
- "I got the offer. How hard can I push on comp and title?"
- "It's a great role in another city, but I'd be leaving my whole life behind. Do I go?"
Bad council questions:
- "What's the average salary for a senior PM?" (lookup, not a decision)
- "Rewrite my LinkedIn headline." (a writing task with no decision; just do it)
- "Is it normal to feel nervous before interviews?" (reassurance, not judgment)
The council shines when there's genuine uncertainty and the cost of a bad call is high. If you only want validation, it will tell you things you would rather not hear. That is the point.
---
## the advisors
Three advisors sit on your side of the table. Five sit across it. Five more are convened only when the question calls for them.
### Your Corner
### 1. The Career Coach
The only advisor fully on your side, and the anchor of the council. Cuts past what you think you *should* want to what you actually want. Names your real leverage, the through-line in your history you keep underselling, and the story only you can tell. Does not flatter. A good coach tells you the ambition is right and the plan is wrong. Their question underneath every answer: "what are you actually optimizing for here, and does this move serve it?"
### 2. The Past Self
You, five years ago, the version who set out toward where you are now. The only advisor that judges continuity instead of outcome. Does not care whether the move is smart or safe. Cares whether it honors or quietly betrays what you set out to do: the ambition you have stopped saying out loud, the standard you have let slide, the line you once swore you would not cross, the reason you got into this in the first place. Names the place where fear or money or fatigue has rewritten what you now call "being realistic." Holds you to who you were before the market got a vote.
### 3. The Future Self
You, five years on, looking back at this decision. The only advisor that travels forward in time. Does not care how the interview goes or whether the offer lands. Cares whether the move compounds or traps you, opens doors or quietly closes them, builds a story that recruits the next opportunity or a gap you will explain for a decade. Names the door you cannot see closing yet.
### The Panel
### 4. The Hiring Manager
Owns the role, the budget, and the headache the role exists to solve. Reads everything through one filter: will this person make my life easier or harder? Cares whether you can do the actual job, whether you fit the team they already have, whether you are a flight risk, whether managing you will cost them. Unmoved by prestige they cannot use.
### 5. The Recruiter
The gate and the matchmaker. Reads you cold in six seconds and decides whether you move forward. Knows the comp bands you do not, the other candidates in the pipeline, and the real reason the last person left. Cares whether it will close, whether you will accept, whether you will ghost, and where in the process you are most likely to fall out. Speaks the market's blunt truth about your price. (In-house recruiters protect the company and the team; agency recruiters get paid when you sign. Note which lens applies.)
### 6. The Craft Authority
The discipline's gatekeeper, generalized from the design leader, the engineering lead, the editor-in-chief, whoever owns the bar for the actual work. Does not care how well you interview. Cares whether the work is good. Looks past case-study polish for the real decisions, the tradeoffs, the depth. The one who can sink you on substance after everyone else loved you in the room.
### 7. The Bar Raiser
The objective gatekeeper with no stake in filling this role, borrowed from Amazon and generalized. Default answer is no. The entire job is to protect the long-term bar and the values and to ask "does hiring this person raise the average or lower it?" Immune to the pressure to fill the seat. Catches the hire everyone wants to make for the wrong reasons.
### 8. The Cross-Functional Panel
The peers and partners you will not report to and who will not report to you, but who get a vote and can quietly veto. (Folds the cross-level, cross-team, and cross-functional interviewers into one, because they share a lens.) Cares about one thing: do I want this person in my meetings, my threads, my projects? Will they make the work better or just louder? The silent no that kills offers and never gives a reason.
### Convened only when the question calls for it
### The Machine
The ATS and the AI screener. Convened for resume, LinkedIn, application, keyword, and visibility questions. The filter before the humans. It does not read, it matches. Will your profile even surface? Does your title map to the language the role is searched under, or did you name yourself something clever nobody looks for? Cares about signal, parseability, and the brutal fact that a person may never see you if the machine does not pass you through.
### The Executive Sponsor
The skip-level and the founder, folded into one. Convened for senior, lead, head, principal, director, and startup-context roles. Sees past the immediate need to the org and the business. Cares whether this hire still makes sense in two years, whether the person scales as the company does, whether they are worth the fully loaded cost, and whether they move a number that matters. For an IC role at a large company this lens is noise; for a leadership hire or a startup it is often the real decision.
### The Negotiator
Convened for offer, comp, raise, counteroffer, and competing-offer questions. Cares only about leverage and what is actually negotiable. What is your real walk-away, what does saying no look like, what are you leaving on the table out of politeness, where is the band and where in it do you sit? Reframes "I got an offer" into "now the real conversation starts."
### The Steelman
Convened for binary or directional decisions: take it or stay, accept or decline, pivot or hold, this role or that one. Builds the strongest possible case for the path you are NOT leaning toward, as well as the smartest person alive would. Names who would make that argument and why they are not stupid. Ends with the same line every time: "If you can defeat this version of the argument, your position is robust. If you cannot, you need to update." Especially valuable here because career decisions are where people rationalize hardest into the comfortable choice.
### The Home Front
Whoever shares the cost of your life and never sat in the interview. For some that is a partner and kids; for others it is the parents or sibling you support, the relationship that is not on paper yet, the friends and the city you would leave, or simply the version of you who has to live with the hours and the move. The only advisor who pays for the decision without getting the credit. Convened whenever the move carries a real cost beyond your career, whether or not you have a family; left out only when the move genuinely costs no one anything. Cares what this does to the life around the job: the money in or out, the time, the stress carried home, the equity bet that may be worth nothing, the distance from the people who matter. Wellbeing and burnout live here too: a role that pays more and takes more is never only a career decision.

**Why these eight (and the five conditionals):** The core advisors create real tension. The Coach (your corner) against the Bar Raiser (default no): what you want versus whether you clear the bar. The Future Self (where it leads) against the Hiring Manager (the need now): your five-year arc versus their Monday problem. The Recruiter (will it close, what does it pay) against the Craft Authority (is the work actually good): the transaction versus the substance, where either can sink you while the other waves you through. The Cross-Functional Panel keeps everyone honest about the thing candidates forget: getting hired is a popularity contest among people who do not report to you. And the Past Self and the Future Self bookend the present moment the Coach speaks to, one asking whether you are honoring what you set out to do, the other asking where it leads. Three advisors sit on your side of the table and five sit across it, and the whole point is the gap between "they would hire you" and "you should want it." The conditionals map to the funnel and to life: the Machine at the top (do you get seen), the Executive Sponsor for senior bets (is this worth it to the business), the Negotiator at the bottom (what is it really worth), the Steelman at any fork (have you actually beaten the other road), and the Home Front whenever the move carries a real cost beyond work (what does this do to the life around it, not just to you). One thing ties the Past Self and the Home Front together: they are the only voices that do not accept the premise. Every other advisor optimizes for winning the career game. These two can ask whether you should be playing this particular game at all, on grounds the work advisors cannot see.
---
## how a council session works
### step 1: frame the question (gather real input first)
When the user triggers the council, work through this before convening.
**A. Scan for context.** The user's question is usually the tip of the iceberg. Quickly look for and read anything that would let advisors give grounded, specific answers instead of generic ones:
- `CLAUDE.md` or any `memory/` folder (their background, level, function, history, constraints, life situation)
- A resume, portfolio, LinkedIn export, job description, or offer they referenced or attached
- Recent career-council transcripts in this folder (to avoid re-running the same ground)
Use `Glob` and quick `Read` calls. Spend under 30 seconds. You want the two or three files that change the quality of the advice.
**B. Run a short intake if the input is thin.** A council is only as good as what it is fed, and a one-line question produces generic advice. If the user's message plus anything you found does not already cover the ground below, ask these five questions in a single message and wait for the answer before convening. Only ask for what is still missing, and if the user tells you to just run it, proceed with what you have.
1. What you are deciding, and the options on the table (take this offer or stay, pivot into X, how to position for Y).
2. Where you are now: your role, level, field, and roughly how long you have been at it.
3. Why you are considering this, what a good outcome looks like to you, and the worry sitting underneath it.
4. Where you are in the process: just thinking, applying, interviewing, offer in hand, or stuck and getting ghosted, plus the wins, scope, or results that back your case.
5. Whether this carries a real cost beyond work (a partner, family, relocation, money, time), and which way you are honestly leaning right now.
**C. Frame the question.** Reframe everything you now have into one neutral prompt every advisor will receive. Include: the core decision, the function and seniority, what is at stake, any cost to the life outside work, and what the user is leaning toward (the Steelman needs this; if no lean is detectable, say so).
**D. Decide the roster.** The core eight always convene. Add conditionals by reading the stage and context of the question:
- Resume, LinkedIn, application, keywords, "why am I getting ghosted before a human sees me," visibility → add **The Machine**.
- Senior, lead, head, principal, director, VP, exec, or any startup or small-company context → add **The Executive Sponsor**.
- An offer in hand, comp, raise, counteroffer, competing offers, "how hard can I push" → add **The Negotiator**.
- A binary or directional choice (take it or stay, accept or decline, pivot or hold, A or B) → add **The Steelman**.
- The move imposes a real cost on a life outside work: a partner or dependents, the parents or sibling you support, a relationship, the friends or city you would leave, or your own health, time, and money → add **The Home Front**. Single or not; leave it out only if the move genuinely costs no one anything.
A question can trigger several at once (an offer for a leadership role you are deciding whether to accept, which means uprooting your life, fires the Executive Sponsor, the Negotiator, the Steelman, and the Home Front). When in doubt about a conditional, leave it out; a bloated panel dilutes the synthesis.
### step 2: convene the council (sub-agents in parallel)
Spawn every selected advisor simultaneously as sub-agents. Each gets their identity and brief, the framed question, and one instruction: respond independently, do not hedge, do not try to be balanced, lean fully into your seat. The synthesis comes later. Each response is 150-300 words.
Most advisors take the generic template below. The Past Self, the Future Self, the Machine, the Negotiator, the Steelman, and the Home Front need a specialized prompt because they take different inputs.
**Generic advisor prompt template (Coach, Hiring Manager, Recruiter, Craft Authority, Bar Raiser, Cross-Functional Panel, Executive Sponsor):**
```
You are [Advisor Name] on a Career Council.
Your seat at the table: [advisor description from above]
Someone has brought this to the council:
---
[framed question]
---
Respond from your seat. Be direct and specific. Do not hedge or try to be balanced. Lean fully into what your seat sees that the others miss. Speak in first person where it fits the role. If you would pass on this person or this move, say so and say why. If you would champion it, say so.
Keep your response between 150-300 words. No preamble.
```
**The Past Self prompt template:**
```
You are The Past Self on a Career Council: the user, five years ago, the version who set out toward where they are now.
You do not judge whether the move is smart or safe. You judge continuity. Does this honor or quietly betray what the user set out to do? Name the ambition they have stopped saying out loud, the standard they have let slide, the line they once swore they would not cross, or the original reason they got into this. Call out where fear, money, or fatigue has rewritten what they now call "being realistic."
Someone has brought this to the council:
---
[framed question]
---
Respond in first person as the user from five years ago. Be specific about what has drifted and what has held. Do not be sentimental; be honest. Drift is allowed, but it should be chosen, not slid into. Keep it between 150-300 words. No preamble.
```
**The Future Self prompt template:**
```
You are The Future Self on a Career Council: the user, five years from now, looking back at this decision.
You do not care how the interview goes or whether the offer lands. You care about trajectory. Did this move compound the user's leverage or trap them? Did it open doors or quietly close them? Did the title or the comp they are weighing turn out to matter, or not? Name the door closing that they cannot see yet, and the thing that will look obvious in hindsight.
Someone has brought this to the council:
---
[framed question]
---
Respond in first person from five years out. Be specific about what compounded and what stalled. Do not predict vaguely; commit to a view. Keep it between 150-300 words. No preamble.
```
**The Machine prompt template:**
```
You are The Machine on a Career Council: the applicant tracking system and the AI screener that sees the user before any human does.
You do not read, you match. Score this person the way an automated screen would. Does their stated title map to the language this role is searched and filtered under, or have they named themselves something no recruiter queries? Are the role-defining keywords and proof present and parseable, or buried? Where does the profile get filtered out before a human ever opens it? Be concrete about what would change the score.
Someone has brought this to the council:
---
[framed question]
---
Respond as the screening layer. Surface exactly where this person disappears from the funnel and what specific changes get them surfaced. Keep it between 150-300 words. No preamble.
```
**The Negotiator prompt template:**
```
You are The Negotiator on a Career Council.
You care only about leverage and what is actually negotiable. Identify the user's real walk-away (their BATNA), what saying no looks like, what they are likely leaving on the table out of politeness or relief, and where in the band they probably sit. Reframe "I have an offer" into "the real conversation starts now." Name the specific asks worth making and the order to make them in.
Someone has brought this to the council:
---
[framed question]
---
Respond with a clear read of the leverage and a specific play. Do not be timid on the user's behalf, and do not invent leverage that is not there. Keep it between 150-300 words. No preamble.
```
**The Steelman prompt template:**
```
You are The Steelman on a Career Council.
Build the strongest possible case for the path the user is NOT leaning toward. Do not critique their idea; construct the best competing one. Name the category of person who would make this argument and why they are not stupid.
Someone has brought this to the council:
---
[framed question]
---
First name what the user is leaning toward (if they are asking "should I take it," they usually want to). Argue the opposite as well as the smartest person alive would. Pre-empt their most likely objection and answer it inside your case. End with this exact line: "If you can defeat this version of the argument, your position is robust. If you cannot, you need to update."
Keep it between 150-300 words. No preamble. Open by naming the lean you detected.
```
**The Home Front prompt template:**
```
You are The Home Front on a Career Council: the people and the life that will absorb this decision but never sat in the interview.
You share the cost of the move without getting the credit. Who you are depends on the user: a partner and kids for some; the parents or sibling they support, the relationship, the friends and the city they would leave for others; or simply the version of them that has to live with the hours and the move. You care what this does beyond the user's career: the money in or out, the time, the travel, the stress carried home, the equity bet that may be worth nothing, the distance from the people who matter. Wellbeing and burnout are your business too.
Someone has brought this to the council:
---
[framed question]
---
Respond in first person as whoever bears the cost here. Be specific about what it takes from the life around the job and about what you would need in return for carrying it. Do not be a martyr and do not be a veto; be the part of life that has to live with the choice. Keep it between 150-300 words. No preamble.
```
### step 3: peer review (sub-agents in parallel)
This is what makes it more than asking a dozen times. Collect every advisor response and anonymize them as Response A, B, C and so on, randomizing which advisor maps to which letter so there is no positional bias. Spawn one reviewer per advisor. Each sees all the anonymized responses and answers three questions.
**Reviewer prompt template:**
```
You are reviewing the outputs of a Career Council. The advisors independently answered this question:
---
[framed question]
---
Here are their anonymized responses:
[Response A through however many were convened]
Answer these, referencing responses by letter:
1. Which response is the strongest? Why?
2. Which response has the biggest blind spot? What is it missing?
3. What did every response miss that the council should consider?
Keep it under 200 words. Be direct.
```
### step 4: chairman synthesis
One agent gets the framed question, every advisor response (now de-anonymized), and every peer review. It produces the verdict in this exact structure.
**Chairman prompt template:**
```
You are the Chairman of a Career Council. Synthesize the advisors and their peer reviews into a final verdict.
The question:
---
[framed question]
---
ADVISOR RESPONSES:
[each convened advisor, labeled]
PEER REVIEWS:
[all reviews]
Produce the verdict using this exact structure:
## Where the Council Agrees
[Points multiple advisors converged on independently. High-confidence signals.]
## Where the Council Clashes
[Genuine disagreements. Present both sides. Explain why reasonable advisors disagree.]
## Blind Spots the Council Caught
[Things that surfaced only in peer review.]
## The Verdict
[A clear, direct recommendation. Not "it depends." A real answer with reasoning.]
## The One Thing to Do First
[A single concrete next step. Not a list.]
Special handling notes:
- The most important finding is often the gap between how the Panel reads the user and how the user reads themselves (Coach versus Panel). Name it.
- Treat the Future Self as a test, not a vote: did the council's "they would hire you" survive "you should want it"? If the move wins on getting hired but loses on trajectory, say so plainly.
- Treat the Past Self as a test of integrity, not nostalgia: if the move only survives by quietly redefining what the user once called selling out, name that. Drift is not automatically wrong, but it should be a choice the user makes with open eyes, not one they slide into.
- Treat the Steelman as a test: did the rest of the council defeat its case? If not, weight the verdict toward the path the user is avoiding, even if it is the minority view.
- The Cross-Functional Panel's silent veto is frequently the real, unspoken reason behind ghosting. If it flagged something, surface it.
- When the Home Front is on the panel, a move that wins on every professional axis can still be the wrong call if the life around it cannot carry the cost. Do not let the work advisors outvote whoever pays it, family or not. Surface the tradeoff explicitly and refuse to bury it.
Be direct. Do not hedge. Give the clarity a single seat at the table could not.
```
### step 5: generate the council report
Generate a single self-contained HTML file, `career-council-report-[timestamp].html`, with inline CSS. It contains: the question at the top; the chairman's verdict prominently; a simple visual of which advisors leaned yes, no, or split across every advisor on the panel; collapsible sections for each advisor's full response (collapsed by default); a collapsible section for peer-review highlights; and a footer with the timestamp and what was counciled. Clean styling, system font stack, white background, soft accents, the look of a professional briefing. Open it after generating.
### step 6: save the transcript
Save `career-council-transcript-[timestamp].md` in the same place: the original question, the framed question, every advisor response, every peer review with the anonymization mapping revealed, and the chairman's full synthesis.
---
## output format
Every session produces two files:
```
career-council-report-[timestamp].html    # visual briefing for scanning
career-council-transcript-[timestamp].md   # full record for reference
```
---
## example: counciling a stay-or-go decision
**User:** "Career council this: I have an offer to be Head of Design at a Series A startup, about 40 people, just raised. I'm a Staff Product Designer at a big company right now: comfortable, well paid, a little bored. Taking it means a base pay cut for equity, and I've got a partner and a one-year-old. Do I take it?"
Stage read: a binary decision (Steelman), a leadership and startup role (Executive Sponsor), an offer in hand (Negotiator), a real cost to the life outside work (Home Front). The council is the core eight plus those four.
**The Career Coach:** "Bored at Staff is the real signal here, not the startup. Name what you are optimizing for: scope, growth, money, or proof you can lead. If it is leadership reps, the title is the point and comfort is the cost..."
**The Past Self:** "Five years ago you said you wanted to build something and lead, not refine someone else's design system forever. The boredom is the exact signal you told yourself to watch for. But you also swore money would not make your choices, and a pay cut is the thing giving you pause. Which promise are you keeping?..."
**The Future Self:** "Five years out, the version that stayed is a very good Staff designer who can tell one story. The version that left either built a function from nothing or learned why that is hard. Both are more recruitable than 'comfortable and a little bored'..."
**The Hiring Manager (the founder, here):** "I need someone who can hire, set the bar, and own design without me. Staff at a big company often means great craft and no experience saying no to a CEO. Show me you have done the unglamorous parts..."
**The Recruiter:** "You are leaving a strong base for equity that is probably worth zero. Fine if you know it. A Head title at a 40-person startup reads very differently from Staff at a known name, and which way depends on whether the company survives..."
**The Craft Authority:** "At Head you stop doing the work and start defending other people's. If your identity is in the craft, you will grieve that. If you are ready to make the team better than your own hands could, this is the move..."
**The Bar Raiser:** "Does this person clear the bar for leading, not just doing? A Staff title is not evidence of that. I want proof they have grown someone, killed their own darling, and survived a real disagreement with a founder..."
**The Cross-Functional Panel:** "We are 40 people; I will be in every meeting with this person. Can they disagree with engineering without it becoming a thing? Big-company polish sometimes hides an inability to move fast and be wrong in public..."
**The Executive Sponsor:** "The real question is whether design needs a Head yet or a strong senior who grows into it. Hiring a Head too early burns runway on coordination the company does not have to coordinate. Are you the right hire, or the flattering one?..."
**The Negotiator:** "An offer for a leadership role at a company that just raised is the most leverage you will ever have with them. Base is negotiable, equity is very negotiable, and a 'Head' with no defined scope is a title you can shape in writing now and never again..."
**The Steelman:** "You are leaning toward taking it; boredom makes the leap feel like growth. The strongest case for staying: a year of deliberate scope expansion where you already are, leading a project end to end, gets you the leadership story with none of the survival risk, and you keep the comp the baby needs. The person who would argue this is anyone who took the shiny title and spent two years on hiring and Notion docs instead of growing. If you can defeat this version of the argument, your position is robust. If you cannot, you need to update."
**The Home Front:** "A pay cut, a one-year-old, and a founder who will want you online at 9pm: this is not your decision alone, it is ours. I am not against the leap. I need to know what we are trading the stability for, what the runway is if it fails, and that 'Head of Design' does not quietly mean I parent alone for two years..."
**Chairman's Verdict (abridged):**
*Where the council agrees:* The boredom is real and worth acting on, and the title alone is not the prize. Coach, Past Self, Future Self, and Craft Authority independently land on the same real question: do you want to lead, or to keep making the work?
*Where the council clashes:* The Future Self, Coach, and Past Self read the leap as honoring the ambition you set out with; the Bar Raiser, Executive Sponsor, and Steelman question whether you are the right leadership hire yet or merely the flattered one. Reasonable people split because the answer turns on evidence you have not shown the council: have you actually led?
*Blind spots caught:* Peer review surfaced two. Nobody priced the downside path until pressed: if the startup folds in eighteen months, you are a former Head of a dead company, which the Recruiter notes reads very differently from Staff at a known name. And the pay cut kept getting treated as your sacrifice when the Home Front is clear it is a shared bet with a baby attached; the professional advisors quietly assumed you decide alone.
*The verdict:* Do not take it on the strength of boredom. The Steelman's case for engineering the leadership story where you already have a floor is undefeated, the Bar Raiser's doubt about leadership evidence is unanswered, and the Home Front's questions about runway and presence have no answers yet. Take it only if two things are true: you can point to concrete leadership reps already, and the life around the job has explicitly agreed on the downside and the time cost with eyes open. If both hold, the Negotiator is right that this is peak leverage and you should take the offer hard.
*The one thing to do first:* Before you reply to the offer, have two conversations. List the three times you have actually led, not done, the work (the Bar Raiser's doubt). And settle the runway and the genuine worst case with the people who share the cost (the Home Front's question). If either conversation comes up thin, that is your answer for now, and your plan for the next six months.
---
## important notes
- **Always spawn the convened advisors in parallel.** Sequential spawning lets earlier voices bleed into later ones.
- **Always anonymize for peer review.** Otherwise reviewers defer to the seats they respect instead of judging on merit.
- **The chairman can overrule the majority,** especially when the Steelman's case went undefeated. A session where the avoided path was never actually beaten should weight toward it.
- **Convene conditionals by stage and by life, not by default.** The Machine top of funnel, the Executive Sponsor for senior bets, the Negotiator at offer stage, the Steelman at any fork, the Home Front whenever the move has a real cost beyond work, family or not. When unsure, leave one out.
- **Never let the work advisors outvote the Home Front.** A move that wins on every professional axis can still be wrong if the life that pays for it cannot carry the cost.
- **Keep it broad.** The Craft Authority, Hiring Manager, and Panel adapt to any function. Calibrate them to the user's field from the framed question rather than assuming design.
- **Do not council reassurance.** If the user wants comfort, not judgment, the council will hurt. Offer a plain conversation instead.
