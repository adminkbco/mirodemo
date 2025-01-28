<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Miro-Style Flowchart</title>
  <style>
    body {
      font-family: Consolas, "Courier New", monospace; 
      margin: 20px;
    }
    pre {
      background-color: #f9f9f9;
      padding: 20px;
      border: 1px solid #ddd;
      overflow: auto;
    }
  </style>
</head>
<body>

<h1>Miro-Style Flowchart</h1>
<pre>
 ┌────────────────────────────────────┐
 │        Stage 1: Awareness         │  (Green shape)
 │  (Lead Capture & Initial Content) │
 └────────────────────────────────────┘
                    |
                    v
         ┌──────────────────────┐
         │ Decision: Does the   │  (Yellow diamond)
         │ visitor engage with  │
         │ our free resource?   │
         └──────────────────────┘
                 /   \
                /Yes  \ No
               /       \
              v         v
 ┌──────────────────────┐       ┌────────────────────────────────────────────────────┐
 │ Nurture Lead via     │ (Purple)  (e.g., retarget with ads, show more content,   │
 │ Email Sequence/CRM   │       │ keep them in audience for further awareness)      │
 └──────────────────────┘       └────────────────────────────────────────────────────┘

 ------------------------------------------------------
 (Move to Stage 2 once they book a call or show deeper interest)
 ------------------------------------------------------

 ┌──────────────────────────────────────────────┐
 │   Stage 2: Discovery & Qualification        │  (Green shape)
 │ (Discovery Call, Survey, or Questionnaire)  │
 └──────────────────────────────────────────────┘
                    |
                    v
         ┌───────────────────────────┐
         │ Decision: Are they a good │ (Yellow diamond)
         │ fit (budget, timeline,    │
         │ scope)?                   │
         └───────────────────────────┘
                 /    \
                /Yes   \ No
               /        \
              v          v
   ┌─────────────────────────┐    ┌─────────────────────────────────────────┐
   │ Move to Stage 3:        │ (Purple) │ Politely decline / refer out or keep in  │
   │ Proposal & Negotiation  │         │ long-term nurture if budget/timing isn’t  │
   └─────────────────────────┘         │ right                                      │
                                       └─────────────────────────────────────────┘

 ------------------------------------------------------
 (Stage 3: Present proposal, define scope, handle objections)
 ------------------------------------------------------

 ┌──────────────────────────────────────────────┐
 │  Stage 3: Proposal & Negotiation           │ (Green shape)
 │ (Detail the scope, timeline, pricing)      │
 └──────────────────────────────────────────────┘
                    |
                    v
         ┌─────────────────────────┐
         │ Decision: Does client   │ (Yellow diamond)
         │ agree on scope & terms? │
         └─────────────────────────┘
                 /    \
                /Yes   \ No
               /        \
              v          v
   ┌───────────────────────────┐   ┌─────────────────────────────────────────┐
   │ Move to Stage 4:          │(Purple) │ Revisit or Adjust Terms / Follow Up  │
   │ Onboarding & Planning     │         │ Later (if potential remains)         │
   └───────────────────────────┘         └─────────────────────────────────────────┘

 ------------------------------------------------------
 (Stage 4: Kickoff meeting, gather requirements, set timeline)
 ------------------------------------------------------

 ┌─────────────────────────────────────┐
 │ Stage 4: Onboarding & Planning    │ (Green shape)
 │ (Kickoff, project schedule, etc.) │
 └─────────────────────────────────────┘
                    |
                    v
   ┌───────────────────────────────────────────────────┐
   │ Move to Stage 5: Implementation & Integration    │ (Purple shape)
   └───────────────────────────────────────────────────┘

 ------------------------------------------------------
 (Stage 5: Configure bots/AI, set up processes)
 ------------------------------------------------------

 ┌────────────────────────────────────────────┐
 │  Stage 5: Implementation & Integration    │ (Green shape)
 │ (System setup, pilot tests, feedback)     │
 └────────────────────────────────────────────┘
                    |
                    v
   ┌────────────────────────────────────────────────────┐
   │ Decision: Are the pilot tests successful/stable?  │ (Yellow diamond)
   └────────────────────────────────────────────────────┘
                 /    \
                /Yes   \ No
               /        \
              v          v
   ┌─────────────────────────┐   ┌───────────────────────────────────────────────────┐
   │ Move to Stage 6:        │(Purple)  │ Troubleshoot/refine; revert to pilot stage    │
   │ Training & Adoption     │          │ until issues are resolved                     │
   └─────────────────────────┘          └───────────────────────────────────────────────────┘

 ------------------------------------------------------
 (Stage 6: Educate & enable the client’s team)
 ------------------------------------------------------

 ┌─────────────────────────────────────────┐
 │ Stage 6: Training & Adoption          │ (Green shape)
 │ (Workshops, Q&A, support resources)   │
 └─────────────────────────────────────────┘
                    |
                    v
   ┌─────────────────────────────────────┐
   │ Move to Stage 7: Completion &      │ (Purple shape)
   │ Review (Assess ROI, sign-off)      │
   └─────────────────────────────────────┘

 ------------------------------------------------------
 (Stage 7: Evaluate final metrics, gather feedback)
 ------------------------------------------------------

 ┌─────────────────────────────────────────────────────┐
 │  Stage 7: Project Completion & Review             │ (Green shape)
 │ (Measure outcomes, confirm satisfaction, gather    │
 │ testimonials if relevant)                          │
 └─────────────────────────────────────────────────────┘
                    |
                    v
         ┌─────────────────────────────┐
         │ Decision: Are they happy    │ (Yellow diamond)
         │ with the outcome?           │
         └─────────────────────────────┘
                 /    \
                /Yes   \ No
               /        \
              v          v
   ┌────────────────────────────────────────────────┐   ┌────────────────────────────────────────────────────┐
   │ Move to Stage 8: Ongoing Support & Partnership│(Purple)  │ Address concerns / fix issues, re-evaluate scope   │
   └────────────────────────────────────────────────┘         └────────────────────────────────────────────────────┘

 ------------------------------------------------------
 (Stage 8: Provide maintenance/retainers, expansions, referrals)
 ------------------------------------------------------

 ┌─────────────────────────────────────────────────────┐
 │  Stage 8: Ongoing Support & Long-Term Partnership  │ (Green shape)
 │ (Maintenance, new AI features, scaling, referrals) │
 └─────────────────────────────────────────────────────┘
                    |
                    v
   ┌─────────────────────────────────────────────────────┐
   │ Continual Updates / Relationship Management         │ (Purple shape)
   │ (Stay in contact, schedule reviews, propose new     │
   │ optimizations or expansions)                        │
   └─────────────────────────────────────────────────────┘
</pre>

</body>
</html>
