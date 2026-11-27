---
permalink: /portfolio/icu-nurse-handover/case-study/
title: "Mixed Reality ICU Nurse Handover (Master's thesis, Monash, High Distinction)"
description: "Master's thesis at Monash University (High Distinction). A visionOS prototype for ICU nurse handover using Swift, SwiftUI, RealityKit and SharePlay."
author_profile: true
---

Master's thesis at Monash University, awarded High Distinction (83/100).

**Stack:** Swift, SwiftUI, RealityKit, visionOS, SharePlay / GroupActivities.

Demo
------

<figure>
  <video controls muted playsinline loop preload="metadata" width="1280" height="720" poster="{{ '/assets/thesis/thesis-demo-poster.jpg' | relative_url }}">
    <source src="{{ '/assets/thesis/thesis-demo.mp4' | relative_url }}" type="video/mp4">
    <a href="{{ '/assets/thesis/thesis-demo.mp4' | relative_url }}">Watch the Apple Vision Pro demo</a>.
  </video>
  <figcaption>Apple Vision Pro demo of the prototype. The recording has no audio.</figcaption>
</figure>

Problem
------

ICU handovers are complex and time-pressured, and prone to communication breakdowns and omitted information. The volume of critical patient data causes cognitive overload, so nurses need consolidated, easily accessible information.

Research questions
------

How mixed-reality interfaces can:

* support collaborative sense-making
* improve the incoming nurse's retention of critical data
* manage perceived cognitive load during shift change

Approach
------

The project followed a Design Science Research methodology. Two spatial interface configurations were designed:

* a centralised **Unified Dashboard**
* a **Spatially Anchored Space**, with situated visualisations

Both are structured on the ISBAR clinical communication framework (Identify, Situation, Background, Assessment, Recommendation). Outgoing and incoming nurses join the same spatial session with SharePlay.

<figure>
  <img src="{{ '/assets/thesis/shareplay-icu-room.png' | relative_url }}" alt="SharePlay collaboration in a simulated ICU room. A remote nurse appears as a spatial Persona beside the patient's bed, with floating ISBAR panels and vitals charts.">
  <figcaption>SharePlay collaboration inside the simulated ICU room. The other nurse appears as a spatial Persona next to the patient's bed, with floating ISBAR panels and vitals charts.</figcaption>
</figure>

<figure>
  <img src="{{ '/assets/thesis/shareplay-monash-lab.png' | relative_url }}" alt="The same SharePlay session in passthrough at Monash's Faculty of IT. A remote collaborator's Persona is in the lab with an ISBAR panel.">
  <figcaption>The same SharePlay session in passthrough at Monash's Faculty of IT, with a remote collaborator's Persona and an ISBAR panel.</figcaption>
</figure>

Evaluation
------

Exploratory user study with practising nurses and PhD nursing students.

Outcome
------

An early exploratory prototype, plus UX and spatial-design considerations for future mixed-reality handover systems. The findings are exploratory. A small sample and limited time mean they do not generalise.

Next steps
------

* Test with a larger, more diverse sample of nurses.
* Use more realistic ICU scenarios, with distractions such as equipment noise and alarms.

[Project summary](/portfolio/icu-nurse-handover/)
