# Features and specification

## Context
As chapter president, I depend on chairs and general members to keep initiatives moving without me present at every touchpoint. Still, time-sensitive information currently spreads unevenly: some of it lives only in casual chat or verbal exchanges rather than an official channel, and the person responsible for accuracy and records, the secretary, has no reliable way to know whether something has actually been seen or acted on. The job to be done, drawn from JOB-01 and JOB-02, is twofold: a general member needs to catch time-sensitive updates before they’re buried under newer messages, without relying on an individual reminder; the secretary and my other chairs need a clear, evidence-based signal of what’s actually been completed, rather than deciding on instinct.

## Users
See PROFILE-01 (general chapter member, commuter, single daily check window) and PROFILE-02 (Chapter Secretary, dual-role constraint on info-gathering).

## Scope

Included: centralized posting of time-sensitive chapter information to one persistent, official location; a defined trigger for reminders rather than instinct-based judgment; visibility into whether sent information has been seen or acted on by general members or chairs.

Non-goals: this does not replace the chapter’s existing group chats, does not automate dues payment or collection, does not pull from or manage the school-wide NPHC calendar automatically, does not track brother capacity or burnout, and does not eliminate the secretary’s role in compiling the newsletter; it reduces the manual chasing and guessing around that process.



### Kano hypotheses

| F-01 |Official single source-of-truth resource for time-sensitive info|Must-be |Both segments / INT-01, INT-02 |INT-01 missed Convocation timing because it lived only in casual chat; INT-02’s stepshow date error traced to the same pattern, info shared verbally rather than posted officially. |
| F-02 |Requirement that time-sensitive updates go through the official channel, not casual chat only |Must-be |General member / INT-01 |Directly named as the cause of a missed, convocation practice. |
| F-03 |Rule-based reminder trigger |Performance |Secretary / INT-02 |Secretary described his current method as an art rather than a science, with no defined trigger; more consistency here scales directly with reduced guesswork.|
| F-04 |Acknowledgement/seen tracking on sent info |Attractive |Secretary/ INT-02 |He currently has no way to see who’s acted on something until after the fact, but described this neutrally, not as an expected baseline. |
| F-05 |Digest or highlight view surfacing older,buried messages |Performance |General member / INT-01 |He reported only reading what’s fresh each day and missing anything posted earlier during high-volume periods; more visibility into older items scales with fewer missed updates. |
| F-06 |Must-be |Must-be |General member / INT-01 |Dues messaging went out without deadline or payment info in the first release, causing confusion. |
| F-07 |Performance |Performance |Both segments / INT-02 |Secretary described repeatedly chasing the community service chair; a visible status view would reduce, but not eliminate, this manual follow-up. |

## Behavior
When a chair has a time-sensitive update, they submit it to the central resource rather than only to casual chat. The system timestamps the entry and surfaces it in a highlighted, current-items view so it isn’t buried once newer messages arrive. If an item nears its deadline without a logged acknowledgment or action from the relevant brothers, the system flags it for a reminder rather than leaving that judgment to the secretary alone. Chairs update their own task status directly, so the secretary or president can check progress without messaging each one individually.

## Constraints
Must run on Notion as a live, continuously updated dashboard, not a static document distributed once and read passively. Must add near-zero extra reporting burden, consistent with the finding that shrinking brother capacity is part of the underlying problem. Must not disclose sensitive personal reasons behind a missed deadline or flag, only that something is outstanding. Must be usable primarily from a phone, since brothers reported checking chats during brief windows in their day, not at a desk.

## Acceptance

- WHEN a chair submits a time-sensitive update, THE SYSTEM SHALL log it to the central resource with a timestamp and surface it in the current-items view.

- IF a logged item nears its deadline without a recorded acknowledgment, THEN THE SYSTEM SHALL flag it for a reminder.

- IF a chair updates their task status, THEN THE SYSTEM SHALL reflect that status without requiring the secretary or president to follow up individually.

- WHEN a brother views the central resource, THE SYSTEM SHALL display items from the past two weeks, not only the most recent entry.

- WHERE acknowledgment tracking is enabled for an item, THE SYSTEM SHALL show who has and has not acknowledged it, without disclosing individual reasons for non-response.

## Handoff reflection
I gave FEATURES.md to a chapter member with no prior project context. Each feature and acceptance statement read clearly, with no notes or confusion. However, the document doesn’t state what the end product actually is or where it lives. The reader initially assumed it described a formatted Word document shared with the chapter, since the spec mentions Notion only briefly and doesn’t say the whole thing is meant to function as a live dashboard rather than a static handout. I revised the Constraints section to name Notion explicitly as the platform. I clarified in Constraints that this is a living, updated dashboard, not a document distributed once and read passively. 

## AI assistance
For this case I used Claude to compile some of my raw findings into summaries and draft some effective interview questions for a chair in the chapter and a general member. I used Grammarly to tighten my grammar and responses.