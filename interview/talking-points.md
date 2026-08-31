# Interview Talking Points — Kill the Feature

## 30-Second Version

"A proposal came in for an AI feature that automatically summarizes every meeting. It sounded like an easy win — meetings are a universal complaint, the tech is mature. When I actually sized the opportunity and ran a risk assessment, the real need was narrower and already partially served, while the privacy and governance risk was high. I killed it, and redirected the same AI capability toward an enterprise knowledge retrieval feature with better evidence and lower risk."

## 2-Minute Version

**Problem →** A feature proposal that looked obviously good — universal pain point, mature technology, high visibility — but hadn't been evaluated past "would people probably like this."

**Evidence →** Research synthesis showed the underlying need was narrower than assumed: most of the value was already captured by existing note-taking habits and partially adopted transcription tools. The remaining gap was mostly about unclear action-item ownership, which an AI summary wouldn't actually fix.

**Decision →** Sized the real opportunity as medium, not high, once existing alternatives were accounted for. Weighed that against high implementation cost and high privacy/governance risk — the feature would turn previously ephemeral conversations into a persistent, discoverable record, including for sensitive meetings employees explicitly didn't want recorded.

**Implementation →** Wrote the decision memo not as "no," but as "no, and here's what to build instead" — redirecting the same summarization/retrieval capability toward an enterprise knowledge retrieval feature that serves a higher-frequency, lower-risk need.

**Result →** Avoided sinking engineering and governance capacity into a medium-value, high-risk feature, and gave the organization a concrete, better-evidenced alternative instead of just a veto.

## 5-Minute Version

Add to the 2-minute version:

- **Stakeholders:** Executives wanting a visible AI showcase feature, employees whose meetings would be recorded (including sensitive ones), Legal/HR concerned with discoverability and retention, and engineering whose capacity the feature would consume.
- **Constraints:** No real usage data existed yet on the scale of the actual problem — the analysis had to work from research synthesis and explicit assumptions rather than hard numbers, and I documented those assumptions rather than presenting them as certainty.
- **Alternatives considered:** Building a scoped-down version limited to non-sensitive meetings (possible future revisit, not rejected outright); doing nothing and leaving the AI-showcase goal unaddressed (rejected — wastes the opportunity to actually deliver executive-visible AI value through a better use case).
- **Tradeoffs:** Choosing to recommend a redirect instead of simply declining the request took more work — sizing a second opportunity, not just killing the first — but a bare "no" would have left the organization's underlying goal (visible AI value) unmet.
- **Risk reasoning:** The sharpest risk wasn't AI accuracy, it was category-level: turning spontaneous, previously unrecorded conversation into a persistent, potentially discoverable record. That risk exists even if the summarization itself is perfectly accurate.
- **Lessons / next steps:** This is a "not now, not like this" decision with an explicit revisit trigger — a team with a validated, narrow, opt-in use case could reopen it. The kill/build method itself should become a standing gate for future AI feature proposals, not a one-time exercise.

## Likely Interviewer Questions & Strong Answers

**"Isn't 'don't build it' just risk-aversion dressed up as analysis?"**
No — the memo doesn't stop at "too risky." It sizes the actual opportunity, compares it against existing alternatives, and recommends a specific redirect that uses the same capability with better evidence and lower risk. Risk-aversion stops at no; this stopped at "no, and here's what to do instead."

**"How did you push back on a feature executives were excited about?"**
By reframing the goal, not just the feature. Executives wanted visible AI value — I didn't argue against that goal, I showed that this particular feature was a weak way to get it, and offered a stronger way to get the same outcome. That's an easier conversation than telling leadership their instinct was simply wrong.

**"What if you're wrong about the value being only medium?"**
That's exactly what the revisit trigger is for. I named the specific evidence — a validated, high-frequency, narrowly scoped need — that would change the decision, rather than treating the kill as permanent or unfalsifiable.
