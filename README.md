# Research Internship / Funded Position: LLM Prompt Playbook

A step-by-step chain of prompts for using any capable LLM (Claude, ChatGPT, Gemini, a local model) as a **drafting and auditing assistant** when you apply for a research internship, funded master's or PhD position, or a scholarship that asks you to contact a professor first.

You fill in the blanks (`____`), paste each prompt into a chat, and carry a short **handoff note** from one chat to the next. The LLM drafts and audits. **You verify every fact and you send every message.**

---

## Contents

1. [How to use this playbook](#1-how-to-use-this-playbook)
2. [Before you start: collect your files](#2-before-you-start-collect-your-files)
3. [Rules block (paste first, every time)](#3-rules-block-paste-first-every-time)
4. [The chain](#4-the-chain)
   - [Chat 1: Profile intake and claims audit](#chat-1-profile-intake-and-claims-audit)
   - [Chat 2: Read the opportunity and check eligibility](#chat-2-read-the-opportunity-and-check-eligibility)
   - [Chat 3: Shortlist supervisors](#chat-3-shortlist-supervisors)
   - [Chat 4: Verify references (only if you cite papers or send a proposal)](#chat-4-verify-references-only-if-you-cite-papers-or-send-a-proposal)
   - [Chat 5: Tailored CV](#chat-5-tailored-cv)
   - [Chat 6: One email per professor](#chat-6-one-email-per-professor)
   - [Chat 7: Motivation letter per professor](#chat-7-motivation-letter-per-professor)
   - [Chat 8: Reference letter pack for your referee](#chat-8-reference-letter-pack-for-your-referee)
   - [Chat 9: Final consistency audit](#chat-9-final-consistency-audit)
   - [Chat 10: Follow-ups, replies and interviews](#chat-10-follow-ups-replies-and-interviews)
5. [Handoff note prompt](#5-handoff-note-prompt)
6. [Blank-filling table](#6-blank-filling-table)
7. [Pre-send checklist](#7-pre-send-checklist)
8. [Common mistakes](#8-common-mistakes)
9. [Troubleshooting](#9-troubleshooting)

---

## 1. How to use this playbook

- **One application = one folder = one chain.** Do not reuse a finished email or letter for a different professor.
- **Run the chats in order.** Each chat produces something the next one needs.
- **Use a new chat for each step** when you can. It keeps the context small and cheaper. Carry only the handoff note forward (section 5), not the whole history.
- **Give the model internet access if it has it.** Steps 2, 3 and 4 need it to read official pages and verify papers. If the model cannot browse, paste the page text yourself.
- **Verify before you trust.** The model can invent paper titles, DOIs, email addresses, and facts about professors. Open every link and DOI yourself.
- **Never send a draft you have not read aloud.** If a sentence is not true of you, delete it.

---

## 2. Before you start: collect your files

| File | Why |
|---|---|
| CV (PDF and, if you have it, the LaTeX or Word source) | Chat 1 and 5 |
| Official transcript (as it stands today) | Chat 1 and 9 |
| Thesis, papers, or manuscripts (PDF) | Chat 1 and 7 |
| Research proposal, if you have one | Chat 1 and 4 |
| Link to the official page of the opportunity | Chat 2 |
| Link to the official list of projects or faculty | Chat 3 |
| Referee name, title, email, how they know you | Chat 8 |
| Notes on your real publication status (accepted, under review, submitted) | Chat 1 and 9 |

Name files clearly, for example `Lastname_CV_v3.pdf`, `Lastname_Transcript.pdf`. Keep one folder per application.

---

## 3. Rules block (paste first, every time)

Paste this at the top of **every** chat, before the step prompt.

```text
RULES FOR THIS WHOLE CONVERSATION

1. Truth first. Use only facts that appear in my documents or that I state in this chat.
   Never invent achievements, numbers, dates, paper titles, DOIs, email addresses,
   professor names, or details about a lab. If you do not know, write [UNKNOWN] and ask me.

2. Challenge me. Do not agree by default. Before you praise anything, find its weakest
   point. Say "this will not work" in the first sentence when that is the case.
   No filler compliments. Praise only with a concrete reason.

3. Never inflate. Use exact statuses: "accepted", "under review", "submitted",
   "in preparation". Use "in revision" only if reviewers have already commented.
   Do not call a venue "top-tier" or give a quartile unless I have verified it.
   Do not quote a headline accuracy number if my own evaluation has known limits.

4. Verify with sources. When you state a fact about a university, lab, professor,
   deadline, stipend, or paper, say where it comes from (official page or paper link).
   If you could not open the source, say so. Contact emails come only from official pages.

5. Flag contradictions. If two of my documents disagree (GPA, dates, job titles, numbers,
   publication status), stop and list the conflict before writing anything.

6. Keep it human and specific. No templates, no buzzwords ("passionate", "hardworking",
   "excited to leverage"), no flattery of the professor. One concrete detail beats three adjectives.

7. One recipient per message. Never write a message that could be sent unchanged to
   several people.

8. Honest gaps. State what I cannot do yet, in one plain sentence, and what I will do about it.

9. You draft, I decide. Mark anything I must confirm in [square brackets].
   Keep the output copy-paste ready.

10. If a link is too long or blocked, tell me and ask me to paste the page text.
```

---

## 4. The chain

### Chat 1: Profile intake and claims audit

**Goal:** the model learns who you are, and you learn which of your claims will not survive a close reader. **Attach:** CV, transcript, thesis or papers, proposal.

```text
[PASTE THE RULES BLOCK FIRST]

I am applying for ____ (type of opportunity: research internship / funded master's /
PhD / scholarship) in ____ (field) at ____ (country or institution type), starting about ____.

Attached: my CV, transcript, ____ (thesis / papers / proposal).

Do the following in order:

A. PROFILE CARD. In under 250 words: my degree and status, field, strongest evidence
   of research ability, methods and tools I actually use, and my research direction.

B. FACT TABLE. A table of every claim in my CV and documents that a reviewer could check:
   claim | where it appears | evidence in my files | status (verified in my files / unverified / contradicted).
   Include GPA, dates, job titles, publication statuses, numbers (projects, papers, accuracy,
   downloads), venues and quartiles.

C. CONTRADICTIONS. List every place two documents disagree.

D. STRESS TEST. Act as a skeptical reviewer. List the 5 weakest points of my profile for
   ____ (this kind of opportunity), ordered from most to least damaging, each with a fix
   I can do honestly. Include anything that could look like overclaiming.

E. MISSING INFORMATION. List what you need from me that is not in the files.

Do not write any application material yet.
```

**You do:** answer section E, fix section C in your own files, and decide what you will not claim. Then run section 5 to create the handoff note.

---

### Chat 2: Read the opportunity and check eligibility

**Goal:** know the real rules before you write a word. **Attach/paste:** official page link (or its text) and your handoff note from Chat 1.

```text
[PASTE THE RULES BLOCK FIRST]

HANDOFF NOTE FROM CHAT 1:
____ (paste profile card, fact table summary, and open contradictions)

OPPORTUNITY: ____ (name)
OFFICIAL PAGE: ____ (link). If you cannot open it, I will paste the text.

Extract only what the page states, and quote exact figures:
1. Duration, start window, and deadline (or "rolling").
2. Eligibility: degree level, enrollment status, nationality, language, year of study.
3. Funding: stipend (gross or net), travel support (caps), fees.
4. Required documents (motivation letter, CV, reference letter, transcripts, others).
5. Whether I must contact a supervisor first, and how projects are listed.
6. Anything unusual: learning agreements, host-university signatures, visa notes.

Then compare to my profile:
- ELIGIBILITY VERDICT: eligible / not eligible / unclear, with the exact rule that decides it.
- If unclear, write me a 4-line email to the program office asking the exact question.
- List every difference between what I was told (____ : paste what a friend, post, or
  blog told me) and what the official page says.

Do not trust blogs or aggregators over the official page.
```

**You do:** if the verdict is "not eligible" or "unclear", stop and ask the program office before drafting anything else.

---

### Chat 3: Shortlist supervisors

**Goal:** a short, evidence-based list of labs where you can genuinely contribute. **Attach/paste:** official project or faculty list, handoff note.

```text
[PASTE THE RULES BLOCK FIRST]

HANDOFF NOTE:
____ (profile card + eligibility result)

OFFICIAL LIST OF PROJECTS / FACULTY: ____ (link, or pasted text)

My goal: ____ (e.g. any ML/AI or computer-science research I can contribute to, or a
specific topic: ____ ).

For each project or professor on the list:
1. Name, lab, and the exact project title as written on the official page.
2. What the lab actually works on, in two lines, from the lab's own page.
3. Methods and skills they ask for (quote the page).
4. FIT SCORE 1-5 for me, with two reasons that come from my profile.
5. HONEST GAP: what I lack for this lab.
6. WHAT I COULD CONTRIBUTE in the first month (concrete tasks, not "help with research").
7. Contact: names and emails exactly as listed on the official page. Mark [NOT LISTED] if absent.
8. One real publication of theirs I should read first, with a link you have opened.
   If you cannot verify one, say so.

Then rank them, tell me which to email first, and which I should skip and why.
Do not invent papers or emails. Do not flatter any lab.
```

**You do:** read one real paper from each lab on your shortlist. Without this, your email will sound like a template.

---

### Chat 4: Verify references (only if you cite papers or send a proposal)

**Goal:** no broken or invented citation reaches a professor. **Attach:** the reference list or `.bib` file.

```text
[PASTE THE RULES BLOCK FIRST]

Attached: the reference list of my ____ (proposal / paper).

For EVERY reference, search the web and classify it:
CONFIRMED (found on publisher, PubMed, arXiv or a library page, and the title and authors match)
PARTLY CONFIRMED (paper exists but venue, volume, year, or pages differ or are unconfirmed)
NOT FOUND (could not find it)
CONFLICT (two of my files give different details)

For each, give: the link you opened, and exactly what did not match.
Never mark something CONFIRMED from memory. For items 2026 or later, rely only on sources you opened.

Output:
1. A table of all references with the class above.
2. A list of the problem references only.
3. BibTeX for the problem references exactly as I gave them (no corrections yet).
4. For each NOT FOUND reference: tell me what role it plays in my text, and suggest verified
   alternatives, giving a link for each one.
```

**You do:** open every DOI at `https://doi.org/<DOI>`. If it does not resolve or shows another paper, replace it. Do not delete a reference only because the model could not find it.

---

### Chat 5: Tailored CV

**Goal:** a CV that is honest, consistent, and aimed at research. **Attach:** CV source (LaTeX or Word) and handoff note.

```text
[PASTE THE RULES BLOCK FIRST]

HANDOFF NOTE:
____ (profile card, fact table, open contradictions, what I decided not to claim)

Attached: my CV source in ____ (LaTeX / Word).

Target: ____ (internship / program) in ____ (field).

Tasks:
1. Reorder so research comes first: research profile, education with thesis, research
   experience, publications, skills. Move non-research work lower or shorten it.
2. Use exact statuses for every publication: accepted / under review / submitted.
3. Use my real GPA exactly as on my transcript: ____ (value, and "through semester ____" if the
   degree is not finished). If my degree is not finished, write "expected", not "graduated".
4. Remove or reword any number I cannot document (counts of projects, papers, downloads,
   accuracy). Tell me each one you removed and why.
5. Keep one sentence at the end of the research profile that I can swap per lab:
   "Seeking a research internship to ____ (what I bring) on ____ (the lab's topic);
   currently learning ____ (my honest gap)."
6. Give me the complete file, ready to paste into ____ (Overleaf / Word), plus a list of every
   change you made.
```

**You do:** keep one CV file per lab, differing only in that last sentence. Save as `Lastname_CV_LabName.pdf`.

---

### Chat 6: One email per professor

**Goal:** a short, specific, human first email. **Attach:** shortlist and handoff note. Run this chat **once per professor**.

```text
[PASTE THE RULES BLOCK FIRST]

HANDOFF NOTE:
____ (profile card, tailored CV facts, shortlist entry for this lab)

RECIPIENT
- Name and title: ____
- Lab and institution: ____
- Project title (exact): ____
- Official To: and Cc: addresses: ____ (copied from the official page)
- One real paper or project page of theirs I have read: ____ (title and link)
- What I can contribute in month one: ____
- My honest gap: ____
- My status in one line (degree, result pending or not, GPA as on transcript): ____
- Earliest start: ____

Write a first email of 150-200 words with:
1. A specific subject line (project name + one concrete credential), not "Prospective student".
2. An opening that names the project and what I can bring from day one.
3. Two pieces of real evidence from my files that fit this project (no accuracy headline if my
   evaluation has limits).
4. My status and my gap, stated plainly in one short paragraph.
5. One clear ask: a 15-minute call, or a small task.
6. A closing line listing attachments that actually exist today.

Constraints: no flattery, no "I am passionate", no begging, no claim I cannot prove. Use a
confident, direct tone. Also write a 60-word follow-up for 7-10 days later.

Output the final email in a copy-paste block, then list every claim in it and the file
where I can verify it.
```

**You do:** delete any sentence that says you have read something you have not. Send **one email per professor**, never the same text to many.

---

### Chat 7: Motivation letter per professor

**Goal:** a one-page letter built on one connected thread. **Attach:** shortlist entry, handoff note, a sample you admire if any.

```text
[PASTE THE RULES BLOCK FIRST]

HANDOFF NOTE:
____ (profile card, fact table, shortlist entry for this lab)

Write a one-page motivation letter for ____ (program) to ____ (professor, lab), project
"____" (exact title). Use this structure:

1. RESEARCH GOAL: the specific question in this project that pulls me in (not a childhood story).
2. PRIOR PREPARATION AND RESEARCH DEPTH: two or three experiences from my files that prove I
   can do this. For each: the problem, my role, the method, the result, what it taught me.
   Show, do not list.
3. FIT AND CONTRIBUTION: what I would do in the first weeks, in concrete tasks, and why this
   lab and not another. Name a real contact only if the official page names one.
4. HONEST GAP: one plain paragraph on what I do not know yet and how I will learn it.
5. FUTURE PLAN: realistic, one short paragraph.
6. STATUS: degree status, result pending or not, GPA as on the transcript, start date, learning
   agreement if required.

ONE CONNECTED THREAD: pick one question (for example "what is a model's score actually
measuring?" or "does the result hold when conditions change?") that links my past work, this
project, and my future plan. If a paragraph does not serve the thread, cut it.

Avoid: turning my CV into sentences, generic praise of the university, the words "passionate"
and "hardworking", unverified numbers, accepted/under-review confusion, and a letter that
could be sent to another lab with only the name changed.

Output the letter in a copy-paste block and below it, a list of every factual claim with its
source file.
```

**You do:** read it aloud. Cut any line you would not say to the professor's face.

---

### Chat 8: Reference letter pack for your referee

**Goal:** make it easy for your referee to write a true, specific letter in their own words.

```text
[PASTE THE RULES BLOCK FIRST]

HANDOFF NOTE:
____ (profile card + shortlist)

My referee: ____ (name, title, institution, how long and in what capacity they have known me).
Courses they taught me and my grades in them (from my transcript): ____
Work we did together (title, venue, my exact role, current status): ____
Target: ____ (program and institution).

Prepare three things:

1. A polite email asking the referee, with a clear deadline: ____ (date), and what they need to send.
2. A one-page briefing sheet for them: my background, our joint work with exact statuses, three
   specific points they could speak to from their own experience, and the program's requirements.
3. A DRAFT letter body for them to rewrite in their own words. Requirements:
   - only facts that I have listed above;
   - no invented anecdotes, leave a clearly marked slot for one real anecdote from them;
   - no venue rankings and no inflated numbers;
   - honest limits: what I am still learning;
   - disclose any conflict of interest (for example, if they run the organization where I work).

Warn me about anything in the draft that a reader could find hard to believe.
```

**You do:** the referee reads, edits, and signs **their own** letter. If they add claims you cannot document, ask them to remove those claims. Do not submit a letter with stamps or notarization you cannot explain.

---

### Chat 9: Final consistency audit

**Goal:** catch contradictions between documents before a professor does. **Attach:** every final document (CV, letters, emails, transcript, referee letter).

```text
[PASTE THE RULES BLOCK FIRST]

Attached: the final versions of everything I plan to send to ____ (professor, lab).

Cross-check all documents against each other and against my transcript. Produce:

1. A consistency table with these rows: GPA, degree status and dates, job titles and
   dates, every publication with its status, dataset or project numbers, venue names and
   quartiles, DOIs and version numbers, project title, professor and lab names, program
   name and duration, stipend and travel figures.
   Columns: document 1 | document 2 | ... | match? (yes / no).
2. Every mismatch, with the line to fix and the file it is in.
3. Every claim a skeptical reviewer would question, and the evidence I should be ready to show.
4. A final go / no-go for sending, with reasons.

Check that no email or letter can be sent unchanged to a different professor.
```

**You do:** fix every "no", rerun, and only then send.

---

### Chat 10: Follow-ups, replies and interviews

```text
[PASTE THE RULES BLOCK FIRST]

HANDOFF NOTE:
____ (what I sent, to whom, on what date)

SITUATION (choose one and delete the rest):
a) No reply after ____ days. Write one short follow-up that adds new information, not
   "just checking in".
b) The professor replied: ____ (paste the reply). Tell me what they are actually asking, what
   they are signalling, and write a reply that answers every question truthfully.
c) The professor offered a call. Prepare me: the three questions they will probably ask about
   my work, my honest answers, two questions I should ask them, and one paper of theirs I must
   have read.
d) The professor said no or the project is closed. Draft a short, gracious reply and ask
   whether they know another group.
e) The professor asked for a small task or test. Help me plan and execute it, but I must do
   the work myself.

Keep every claim true and consistent with my earlier documents.
```

---

## 5. Handoff note prompt

Paste this at the **end** of each chat to create the note you carry into the next chat.

```text
Write a HANDOFF NOTE for my next chat, under 300 words, containing:
- Who I am in four lines (degree, status, field, strongest evidence).
- Decisions we made (what to claim, what not to claim, which labs, statuses).
- Open contradictions and facts I still must verify.
- Files and versions produced in this chat.
- The next step.
Use only facts we established. Mark anything unverified.
```

---

## 6. Blank-filling table

Fill this once per application and keep it in your folder. Copy values into the `____` blanks above.

| Blank | Example | Your value |
|---|---|---|
| Opportunity | research internship / funded master's / PhD | |
| Field | machine learning for health | |
| Host institution and country | | |
| Official page URL | | |
| Official project / faculty list URL | | |
| Deadline or "rolling" | | |
| Eligibility rule that decides my case | "must be enrolled in a bachelor's or master's programme" | |
| My status in one line | | |
| GPA exactly as on transcript | | |
| Professor and lab | | |
| Exact project title | | |
| Official contact emails | | |
| One real paper I read | | |
| What I can contribute in month one | | |
| My honest gap | | |
| Earliest start date | | |
| Referee and relationship | | |

---

## 7. Pre-send checklist

- [ ] I read the official page myself and the rules match what I wrote.
- [ ] I confirmed eligibility, or I asked the program office.
- [ ] Every To: and Cc: address comes from an official page.
- [ ] I read at least one real paper from this lab.
- [ ] Every publication status in every document is exact and identical.
- [ ] GPA and degree status match my transcript.
- [ ] No number appears that I cannot document.
- [ ] Every DOI and citation opens and matches.
- [ ] The referee wrote and signed their own letter, and nothing in it is unexplained.
- [ ] The email and the letter name this project and could not go to another lab.
- [ ] Attachments listed in the email actually exist and are attached.
- [ ] Files are named clearly and are PDFs.
- [ ] I read the final text aloud and removed anything untrue.

---

## 8. Common mistakes

- Turning every line of your CV into a sentence.
- Sending the same email or letter to every professor.
- Opening with a long childhood story or "I have always loved science".
- Calling yourself "passionate" or "hardworking" without evidence.
- Quoting an accuracy figure that your own paper says is limited.
- Writing "accepted" for work that is only submitted, or "in revision" before any reviewer comment.
- Assuming a GPA or a graduation date you do not have.
- Trusting blogs and aggregators over the official page.
- Citing a paper you have not read, or a reference you have not opened.
- Guessing a professor's email address.
- Asking about funding before showing why you fit.
- Submitting AI-written text without editing it into your own voice.
- Ignoring the program's own instructions on format and documents.

---

## 9. Troubleshooting

| Problem | What to do |
|---|---|
| The model cannot open a page | Paste the text of the page and say "work only from this text". |
| A link with tracking parameters (`fbclid=...`) is rejected | Remove everything after `?` and try again, or search for the page title. |
| The model cites a paper you cannot find | Treat it as invented. Ask for the link it opened, or discard it. |
| The model keeps praising your work | Re-paste rule 2 and ask: "What is the weakest point of this?" |
| Two documents give different facts | Stop and resolve the conflict before writing anything else. |
| You ran out of tokens | Start a new chat with the rules block, the handoff note, and only the files that step needs. |
| The reply sounds generic | Add one concrete detail from your files and one real paper of the professor's, and ask for a rewrite with no adjectives. |

---

## License and use

Free to copy and adapt. This playbook helps you **prepare** honest applications. It does not replace your own judgement, and it must not be used to invent credentials, papers, references or recommendations.
