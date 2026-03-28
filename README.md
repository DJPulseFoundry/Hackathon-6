# Healthcare Hackathon 2026

**Reimagining Cardiac Rehabilitation**

**Hackathon on Devpost:** [Pulse Foundry AI Healthcare Hackathon: Reimagining Cardiac Rehabilitation](https://pulse-foundry-ai-healthcare.devpost.com/)

---

## The Story: Maria’s Gap

Maria is 58. Three weeks ago, she had a stent placed after a sudden heart attack. Today, she is back home. The physical pain is gone, replaced by a quiet, heavy anxiety.

The clinical path forward is clear: **cardiac rehabilitation.** If Maria completes this 12-week program of supervised exercise and support, her risk of death or rehospitalization drops by **43%**. If 70% of patients like Maria participated, we would save 25,000 lives this year.

**But the reality is different.** Maria lives 40 minutes from the nearest clinic. She works part-time and can’t afford to miss the hours. She feels “fine” now, so she wonders if the effort is worth the commute. She’s afraid to push her body, but she doesn’t want to worry her daughter by asking for help.

Maria is one of two million Americans trapped in the **Participation Paradox**: the science is perfected, but the human connection is broken. Currently, **only 1 in 4** eligible patients ever attends a single session. For every day that passes after discharge, Maria’s chance of enrolling drops by 1%.

---

## The Challenge: Bridge the Gap

Your mission is to reimagine the cardiac rehabilitation journey. We are not looking for a digital textbook or a generic fitness tracker; we are looking for a **lifeline**.

In the next five hours, your team must design and prototype a solution that transforms a clinical mandate into a journey a patient *chooses* to complete. How do we bring the expertise of a care team into the living rooms of the rural, the busy, and the afraid?

**Your objective:** Build a working proof of concept that solves the Participation Paradox. Your solution must move beyond simple tracking and address the psychological and logistical walls that stop patients like Maria from recovering.

---

## Deliverables (3-Minute Demo)

At the end of Hour 5, your team will present a high-speed demonstration. No slide decks are required—only the work. You must show:

### 1. The Voice of Care (AI interaction)

A live demo of how your AI interacts with Maria. Show two moments:

- **The win:** Maria just finished a walk—how does the AI reinforce it?
- **The wall:** Maria is tired, anxious, and skipped a session—how does the AI intervene?

### 2. The “Hook” (engagement model)

A walkthrough of the specific mechanic (gamification, social connection, or behavioral nudge) that keeps Maria engaged at **Week 8**, long after the initial scare has faded.

### 3. The Blueprint (architecture diagram)

A single diagram showing how the pieces fit together: how wearable data (heart rate, steps) flows into the AI; where the “red flag” trigger alerts a human doctor if Maria is in danger.

---

## Submission checklist (Devpost)

Use this list before you submit. Paste-ready HTML for the hackathon page is in [`devpost/submission_requirements.html`](devpost/submission_requirements.html).

### Deployed application (required)

- [ ] Prototype is **deployed to the public internet** (no local-only install required to try it).
- [ ] Devpost project includes a **working link** (Website / Try it out / URL field—whatever this event uses).
- [ ] URL **loads and works** at submission time (no broken or placeholder links).
- [ ] If judges need a **demo login** or steps, that’s written on Devpost **and** in the README.

### Live demo (~3 minutes)

- [ ] Plan for a **~3 minute** live demo; **not** slides-only as a substitute for the product.
- [ ] Prefer demoing from your **deployed link** when possible.

### Voice of Care (AI interaction)

- [ ] Live demo covers **the win:** Maria finished a walk—how does the AI reinforce it?
- [ ] Live demo covers **the wall:** Maria is tired, anxious, skipped a session—how does the AI intervene?

### The “Hook” (engagement)

- [ ] Walkthrough explains the mechanic (**gamification**, **social connection**, or **behavioral nudge**) that keeps Maria engaged at **Week 8**.

### The Blueprint (architecture)

- [ ] **One diagram** shows how wearable/app data (e.g. heart rate, steps) flows into your AI or backend.
- [ ] Diagram shows where a **red-flag** path reaches a **human clinician** if Maria may be in danger.

### Demo video (Devpost)

- [ ] **Problem framing** in one or two sentences (Participation Paradox / Maria).
- [ ] **Walkthrough** of AI moments (win + wall), ideally using the **deployed app**.
- [ ] **Engagement hook** explained in under a minute.
- [ ] **Architecture** shown (diagram on screen is fine).
- [ ] **Public URL** mentioned in the video or Devpost description so judges can try it.
- [ ] README explains **setup** for cloners (env vars, API keys, etc.).

### Repository and documentation

- [ ] **README:** project name, one-paragraph summary, team members, **same public URL as Devpost**, run/deploy instructions.
- [ ] **License** included as required by the event.
- [ ] List of **third-party APIs, models, and datasets** used.
- [ ] Clear note on what is **mocked vs live** in the demo.

### Optional but helpful

- [ ] Short **data-flow** or **privacy** note (what is stored, where, why).
- [ ] **Screenshots or GIFs** in the Devpost gallery.

---

## Working Assumptions

To keep your focus on the solution rather than the clinical complexity, you may assume the following:

- Your target patient is a stable adult recovering from a heart attack or stent procedure, cleared for outpatient exercise by their cardiologist.
- The patient has a smartphone and basic internet access and is comfortable using simple apps, but may not be tech-savvy.
- A care team (cardiologist, nurse, exercise specialist) is in place and can receive alerts or summaries from your system. You do not need to build the clinical side.
- Regulatory and HIPAA compliance matters; for this hackathon, demonstrate awareness of privacy and data governance rather than implementing full compliance.
- Clinical protocols (exercise prescriptions, medication schedules) are provided by the care team. Your solution supports and reinforces those protocols; **it does not create them.**

---

## Evaluation: 75 Points

Each team will be scored on a 75-point scale across five dimensions:

| Criterion | What judges are looking for | Points |
|-----------|-----------------------------|:------:|
| **System design** | Architecture is coherent, integration points are well defined, and the solution is credible at scale. | 0–15 |
| **AI quality** | Conversational interactions feel natural, adaptive, and clinically appropriate. Prompt strategy and model choices are thoughtful. | 0–15 |
| **Data approach** | Clear plan for collection, structure, governance, and privacy. Data visibly powers personalization and improvement. | 0–15 |
| **Engagement design** | Motivation mechanics are creative, evidence-grounded, and oriented toward lasting behavior change. | 0–15 |
| **Presentation** | Pitch is clear, concise, and compelling. The demo works. | 0–15 |

---

## Safety: What Your Solution Must Respect

Cardiac rehab is extremely safe when supervised by professionals. Any technology that touches a recovering heart patient must be designed with caution.

- **Recognize warning signs.** If a patient reports chest pain, dizziness, severe shortness of breath, nausea, or a racing or irregular heartbeat, your system should tell them to stop activity immediately and contact their care team. This is non-negotiable.
- **Let the care team lead.** Every cardiac patient has an exercise plan created by their doctor. Your solution can remind patients of their goals, encourage them, and track progress, but targets (how fast, how far, how long) should always come from the care team. **Your app supports the plan; it doesn’t write it.**
- **Know what your solution can’t do.** AI is not a doctor. Your AI can answer general questions, provide encouragement, and flag concerns, but it must clearly communicate its limitations and direct patients to their care team for medical matters. Build the handoff into the experience, not as an afterthought.

---

## Metrics Worth Knowing

You don’t need to be a clinician to measure whether your solution is working. Consider these four questions:

- **Are patients showing up?** The program has 36 sessions. The simplest measure is how many a patient actually attends, and how quickly they start after leaving the hospital. Every day of delay makes them less likely to enroll at all.
- **Are they getting stronger?** Patients take a fitness test at the beginning and end of rehab. The care team uses the results to see whether the patient’s body is handling exercise better over time. Your solution doesn’t need to run these tests, but it should encourage the daily habits (walking, stretching, following prescribed routines) that lead to improvement.
- **Are their health numbers improving?** Blood pressure, cholesterol, weight, and smoking status are the big four. Rehab aims to move all of them in the right direction through exercise, diet changes, and education.
- **How do they feel?** Depression, anxiety, confidence, and overall quality of life matter as much as physical numbers. Many patients struggle emotionally after a cardiac event, and how they feel often determines whether they keep going.
