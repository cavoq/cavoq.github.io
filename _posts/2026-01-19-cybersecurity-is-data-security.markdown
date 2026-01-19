---
layout: post
title: "Cybersecurity Is Data Security: A First-Principles View"
date: 2026-01-19 01:41:07 +0100
categories: cybersecurity
---

### CIA Triad: Confidentiality, Integrity, Availability

When we talk about cybersecurity, we often hear about the “CIA Triad” — Confidentiality, Integrity, and Availability. These three principles form the foundation of information security and are essential to understanding cybersecurity. In essence, cybersecurity is about protecting data in all its forms, ensuring that it remains confidential, unaltered, and accessible when needed.

From the perspective of a malicious actor, this framing becomes clearer. Without extracting data, manipulating it, or denying access to it, no harm can be caused in the digital realm. These actions map directly to the three principles of the CIA triad.

<figure style="margin:2em 0;">
  <img src="/assets/images/cia-triad.png"
       alt="CIA Triad"
       style="display:block; width:100%; max-width:500px;">

  <figcaption style="font-size:0.9em; color:#666; margin-top:0.4em;">
    Figure: Confidentiality, integrity, and availability.
  </figcaption>
</figure>

### Systems, Boundaries, and Attack Surfaces

In practice, cybersecurity evaluates enclosed systems rather than individuals. Institutions can be modeled as bounded entities containing internal state (data), separated from an external environment by a boundary. The attack surface of such a system is the set of points at which data crosses that boundary. Every cyber attack corresponds to an unauthorized extraction, injection, modification, or disruption of data flow across it. This framing allows confidentiality, integrity, and availability to be treated as constraints on boundary-crossing functions rather than as vague properties of systems.
 
<figure style="margin:2em 0;">
  <img src="/assets/images/system-boundary-interfaces.png"
       alt="A system modeled as a bounded entity with data, software interfaces, and human interfaces"
       style="display:block; width:100%; max-width:500px;">

  <figcaption style="font-size:0.9em; color:#666; margin-top:0.4em;">
    Figure: A system modeled as a bounded entity with internal data, interfaces, and an external environment.
  </figcaption>
</figure>

### Humans as Interfaces Within Systems

This abstraction also applies to humans within the system. From a security perspective, people function as interfaces that receive, process, and transmit information across the system boundary. This is not a claim about their value or agency, but about the role they occupy in information flow. Unlike software interfaces, human interfaces enforce rules probabilistically rather than deterministically, which is precisely why they constitute a significant portion of the attack surface.

### Conclusion

In summary, cybersecurity is fundamentally about data security. By understanding the CIA triad and modeling systems as bounded entities with defined attack surfaces, we can reason precisely about the nature of cyber threats and defenses. What matters is not whether data is processed by software or by humans, but how it crosses system boundaries. Awareness is emphasized so heavily because, unlike software, human interfaces do not enforce security policies deterministically. Improving awareness therefore does not eliminate human vulnerability, but reduces the effective attack surface by tightening the constraints under which human-mediated data flows occur.

Cybersecurity, in this sense, is less about building stronger walls than about understanding and constraining the interfaces through which systems interact with the world.