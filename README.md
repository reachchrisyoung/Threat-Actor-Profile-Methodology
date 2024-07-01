Topic: CTI Reporting Methodologies 2 <br />
Subject: Threat Actor Profile Methodology <br />
Source: T. W.  (2023).  [The threat actor profile guide for CTI analysts](https://drive.google.com/file/d/1aIPxUgIA_fC0aH78hN_CQRlMZa69fZ8K/view): Curated intelligence. <br />
NOTE: This is not an original idea; this work product was inspired by [see source above]. <br />
Objective 1: Recreate this methodology in my own words and understanding. <br />

<h1>Threat-Actor-Profile-Methodology</h1>

<h3> Table of Contents </h3>

+ Introduction
+ Part A) Executive Summary Introduction
+ Part B) About [ThreatActorA]
+ Part C) Targets of [ThreatActorA]
+ Part D) [ThreatActorA] Diamond Model
+ Part E) [ThreatActorA] Tactics, Techniques and Procedures (TTPs)
+ Part F) References

<h2>Introduction</h2>

One of the major reasons for Cyber Threat Intelligence (CTI) professionals essentializing some sort of background in communication revolves around the need to cater a report to a targeted audience.  

One of the key ingredients that continues to be advised in the CTI community is to keep the recipient of said intelligence work product interested; what better way than to simply cater the reporting of CTI products to that which is of greatest interest to the targeted recipient.  Only then might CTI programs have a clear and distinct chance of enrolling stakeholders into action-taking mode.  

Executive Summary - Description

Operating on the assumption that senior business leaders will not likely read past the Executive Summary, CTI practitioners must favor their ability to provide this key component of the report.

<h4> What to include in the Executive Summary? </h4>

+ The most significant findings and assessments; PUT THESE UP FRONT – think B.L.U.F. (Bottom Line Up Front)

<h4> How should the Executive Summary be tailored? </h4>

+ The stakeholder who requested the CTI product; in this case, the individual/team who requested the Threat Actor Profile.

<h4>Charting out what details each audience requires</h4>

Anyone working in the intelligence field for any amount of time – either on the production side or in a recipient capacity – likely recognizes that poor intelligence is easily identifiable by its lack of relatable content/context to those receiving the report.  

To overcome the risk of this therein, let us first chart the differences for which each audience would likely care about when it comes to CTI production and delivery:

<h2>Part A) Executive Summary Introduction</h2>

![table1forctithreatactorprofilemethodology](https://github.com/reachchrisyoung/Threat-Actor-Profile-Methodology/assets/104402775/a76353fd-ace7-4fe8-8103-e987f8bfaf6e)

Executive Summary – Tactics

<h4>Key Points to Remember:</h4>

+ Ideally, confine the Executive Summary to 10 to 15 lines (2 to 3 paragraphs).
+ Ensure the following 3 questions are answered:

   (a) “What?”
   (b) “So what?”
   (c) “What now?”

<h4>How to open an Executive Summary:</h4>

Example: “As of [Month, Year], the Cyber Threat Intelligence (CTI) team has researched [ThreatActorA]...”

<h4>What to include in the Executive Summary:</h4>

Explain the level of threat to the company, which may include (among the following):<br />

Highlight –

+ Whether [ThreatActorA] has targeted the company’s sector / country / region as early as 
   possible.

Create – 

+ A short assessment of why the company could be targeted (or have been targeted) by 
   [ThreatActorA].

+ A short evaluation of the company’s ability to defend against and mitigate the threat proposed 
   by [ThreatActorA].

<h2>Part B) About [ThreatActorA]</h2>

<h4>Step 1 – [ThreatActorA] Alias Housekeeping</h4>

Create a Threat Actor Alias (a.k.a. cryptonyms) table to:

(a) Help lay the foundation for profile analysis
(b) Help the reader quickly acknowledge that multiple organizations are tracking the same threat actor, even if under a different label.  Pro Tip: Circumstances pending, the CTI practitioner could discuss the attribution to said threat actor if it’s not clearly defined; diagrams may be considered for inclusion as needed.  View Curated Intelligence’s blog entry on [Threat Actor Naming Schemes](https://www.curatedintel.org/2022/05/threat-group-naming-schemes-in-cyber.html) for additional guidance.

![samplethreatactoranalysistable](https://github.com/reachchrisyoung/Threat-Actor-Profile-Methodology/assets/104402775/ee8059e2-fbcb-4f0f-9a34-b7445816da81)

<h4>Step 2 – Answer the following questions:</h4>

+ What type of threat actor is this (i.e., what group)? 
  NOTE: Consider common labels like cybercrime, espionage, hacktivist, etc.

+ What areas does [ThreatActorA] specialize in?

+ What type of campaign does [ThreatActorA] launch?

+ Assess how advanced [ThreatActorA] is, based on [insert reason(s)].  

+ Outline notable technical observations, such as software and TTPs.

<h2>Part C) Targets of [ThreatActorA]</h2>

+ Which sectors/verticals does [ThreatActorA] target?

  + Think: Proximity to company’s sector / region
  + Think: Recentness of attacks or timeliness applicability

+ What does [ThreatActorA] do once they’re inside a victim’s environment?

+ How long has [ThreatActorA] been known to persist inside a victim’s environment?

+ Are [ThreatActorA]’s targets related to each other?

  + Think: Cyber-enablement campaigns

<h2>Part D) [ThreatActorA] Diamond Model</h2>

Since the Diamond Model Attributes are key details that support rapid understanding of [ThreatActorA]...

<h4>Step 1 – Fill out the Diamond Model Attributes</h4>

![diamondmodelattributestable3](https://github.com/reachchrisyoung/Threat-Actor-Profile-Methodology/assets/104402775/a852f5d8-1eb6-4531-bb8f-2c45014ed5e8)

<h4>Step 2 – Add the attributes aforementioned to the Diamond Model Diagram</h4>
   
NOTE: For reference, the Diamond Model Diagram can be reviewed by [clicking here](https://www.activeresponse.org/wp-content/uploads/2013/07/diamond.pdf?adlt=strict)

![samplediamondmodelimage](https://github.com/reachchrisyoung/Threat-Actor-Profile-Methodology/assets/104402775/531975bf-27ff-4179-876e-eb1ca4adc1d1)

<h4>Step 3 – Leverage the completed Diamond Model Diagram to introduce [ThreatActorA] and address key points from threat data research & extraction.</h4>

<h2>Part E) [ThreatActorA] Tactics, Techniques and Procedures (TTPs)</h2>

The benefits of addressing this part include:

+ The point of this exercise: To demonstrate the CTI practitioner’s technical understanding of 
    [ThreatActorA].

+ TTPs enclosed can be further utilized for other activities by other stakeholders, such as:

  + Security Engineering – TTPs could be helpful in implementing detection for said activities.

  + Red Teamers – TTPs may be leveraged for adversary emulation during engagements.

  + SOC – TTPs can be helpful for situational awareness & supporting event triage.

<h4>Step 1 – Summarize the technical details of [ThreatActorA] at a high level.</h4>

+ Consider utilizing [Unified Kill Chain](https://www.unifiedkillchain.com/assets/The-Unified-Kill-Chain.pdf)’s 3 Stages: In, Through, & Out

<h4>Step 2 – Address [ThreatActorA]’s TTPs in detail</h4>

+ Recommendation: Utilize the [MITRE ATT&CK Framework](https://attack.mitre.org/)
+ Recommendation: Create a Table for TTPs (See Sample Table Below)

![tapmtable4](https://github.com/reachchrisyoung/Threat-Actor-Profile-Methodology/assets/104402775/ef8ef089-68a6-4ccb-9d18-0d47156d0b3a)

<h2>Part F) References</h2>

+ All external references desired for inclusion into the report.

+ Quality Check: Review report for in-line citations (to show the information source).

+ Consider highlighting any problematic sources (leading to performing source evaluation).

  + This can be a footnote on the page of the [ThreatActorA] card if there is concern regarding the technical aspects or attribution assessments.

  + Limt reference inclusion to only those important for the intelligence recipient to know about.












