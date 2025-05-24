# BloodMesh – Real-time Donor–Recipient Matching Platform

This is the early sketch of something I believe needs to exist. It’s called **BloodMesh**—a real-time coordination system for blood, plasma, and organ donation in India. This isn’t just another healthtech app. It’s an attempt to rewrite how we think about critical care logistics, when time is thin and lives are literally on the clock.

---

## Problem
Right now, if your loved one needs a kidney or plasma in a city like Bangalore or Madurai, your best bet is word of mouth or frantic WhatsApp groups. The existing public systems (like NOTTO) are static, delayed, and blind to real-time possibility.

That’s what I want to change. BloodMesh would:
- Map **available donors** (opt-in + verified + tagged with unique IDs)
- Track **demand clusters** in real time (ICUs, ERs, transplant teams)
- Run a **matching engine** that calculates compatibility, urgency, and distance
- Allow **medical teams** to visualize and act, not hope and pray

---

## Scope (in phases)
**Phase 1:** Blood and plasma donation (live and postmortem opt-in)  
**Phase 2:** Organ match dashboard for transplant coordinators  
**Phase 3:** State and city-level demand/supply normalization maps

The goal is to eventually integrate with existing public systems and emergency teams. But the first version will run on **pure simulation**—matching synthetic donors to needs.

---

## Tech Direction (early-stage)
I'm still learning core Python and simulation. Nothing here is production-ready. That said, I plan to:

- Write donor-recipient matching logic (using dictionaries + weighted scores)
- Simulate urgent scenarios with random demand spikes
- Map demand clusters using placeholder ICU logs
- Eventually build a small Streamlit front-end for doctors to test

---

## To Do (for myself)
- [ ] Build a small donor-recipient dictionary structure and simulate matching logic
- [ ] Model emergency need generation (Gaussian spikes + triage weight)
- [ ] Try basic scoring logic (urgency × compatibility / distance)
- [ ] Create UID logic that links with preliminary blood test snapshots
- [ ] Build early CLI test loop (no web UI yet)

---

## Notes
This repo is personal. It’s not backed by an institution or a grant. I’m a doctor learning systems modeling from scratch—so I can build the systems I wish existed when I was in the ICU. BloodMesh is the clearest manifestation of that wish.

If you’re reading this and you build simulations, logistics systems, or health data apps—I’d love to talk.

---

Built by **Goutham**  
Doctor • Systems Learner • Trying to build something that matters
