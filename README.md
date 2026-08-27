# Projects-Portfolio
AI projects portfolio of Amrutha Killada

1. Clinical triage engine — Concierge Psychiatry

Problem

A concierge psychiatry practice was routing every inbound message — refill requests, scheduling, clinical questions, billing, intake, records — through the same human queue. Staff time went to sorting rather than to the items that actually needed judgment. The obvious fix is automation, but the cost of a wrong routing decision in a clinical setting isn't symmetric: misfiling a billing question wastes a few minutes, misrouting a clinical escalation is a patient safety problem.

What I built

A multi-stage classification pipeline that categorizes inbound work across six clinical and administrative task types, with confidence-tiered automation: high confidence routes automatically, mid confidence routes with a flag, low confidence goes to a human untouched. Manual admin workload dropped by an estimated 60%.

How it works
Every inbound patient touchpoint — phone call, email, portal message — lands in a single queue. The engine reads it, classifies it into one of six clinical and administrative task types, resolves it against the patient's existing record, and assigns it to the right owner: front desk, billing, nursing, or the treating physician. What arrives as unstructured text or a transcribed call leaves as a routed task with context already attached.

Outcome

~60% reduction in manual admin workload across six task types. AI quality framework — thresholds, feedback loops, accuracy targets — built from zero and now the measurement backbone for ongoing model iteration.

Companion artifact

Due to contractual agreements and HIPAA regulations. Link attached is populated with synthetic-data version. Same architecture, fake intake text, public repo. 

https://mvpconciergepractice.lovable.app

2. Regulatory submission assistant — pharmaceutical client

Problem

Drug application submissions to the FDA and SFDA require assembling and cross-checking large volumes of documentation against shifting requirements. The bottleneck wasn't writing, it was verification — confirming that what had been assembled actually matched what each agency asked for.

What I built

An AI assistant that supports the compliance workflow for FDA and SFDA drug application processes, cutting time-to-submit by 36%. 

How it works
A regulatory affairs team uploads a completed manufacturing dossier — typically 500+ pages of CMC documentation — and the assistant reads it against FDA submission requirements. It returns a gap analysis: what's missing, what's underspecified, and what a reviewer is likely to flag. Every finding cites the specific regulation it derives from, so the team can verify against the source instead of taking the tool's word for it.

Companion artifact
Due to contractual agreements I cannot share the platform directly. 

Link to video and explanation: https://www.linkedin.com/posts/amruthakillada_sharing-two-transformative-projects-ive-activity-7403825736802783233-hyp6

3. Orbit — MIT Martin Trust Center

Problem

MIT had strong entrepreneurship curriculum and no scalable way to deliver it beyond the people physically in the building. The hard part was never the technology — it was that faculty already have working methods, and a new platform is a tax on them until it demonstrably isn't.

What I built

Orbit, MIT's GenAI-enabled entrepreneurship learning platform, from concept to 13,000+ active users globally. Ran on a $1M annual program and platform budget across four locations.

How it works
A student enters an idea, and Orbit runs it through all 24 steps of MIT's Disciplined Entrepreneurship framework — generating the artifacts each step calls for, from market segmentation through business plan, MVP scope, and pricing. The framework was already MIT's. What Orbit changed was how quickly a founder could get through a credible first pass of it, so their time went to pressure-testing decisions rather than producing them.

Outcome
13,000+ active users globally within a year of launch, AI-enabled learning embedded in formal MIT curricula and co-curricular programs.

Companion artifact
See a video demo - https://www.linkedin.com/posts/amruthakillada_kudos-to-the-team-at-stackai-doug-williams-activity-7195865511639810048-w2Qa
Login here to explore Orbit, note the platform is MIT-gated - https://orbit.mit.edu/

4. train4ai

Problem

Enterprises buying AI tools had no reliable read on whether their own workforce could use them. Procurement decisions were being made on vendor demos rather than on internal capability.

What I built

Co-founded and led product for an AI readiness and skills-intelligence platform. The assessment engine evaluates employee AI capability and recommends the tools and integration paths that fit the organization it's actually assessing. Launched to 358 active B2C users, 3 paying enterprise customers, and 5 B2B pilots within first 6 months. 

Companion artifact
Product Link: https://checkyouraiq.train4ai.app/



