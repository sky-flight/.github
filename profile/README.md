# Sky Flight

**The immersive gateway to the Into The Blue Operating System.**

Sky Flight is the canonical immersive environment for the Into The Blue Operating System (ITB OS) — the spatial operating system in the Open Engineering Platform. It is not a demonstration of what spatial computing can do; it is the shell in which ITB OS is used. Where ITB OS provides the runtime, Sky Flight provides the world.

Engineers use Sky Flight to walk through architectures, inspect digital twins, collaborate on live systems, and investigate the state of software the same way pilots read a chart. It is the desktop of ITB OS, rendered as an airspace.

## Purpose

Sky Flight exists to make everyday engineering work — reviewing architectures, exploring systems of record, walking through digital twins, and reasoning about product models — a first-class immersive experience rather than a novelty.

It is engineering-first:

- Every destination corresponds to real engineering activity, not a showcase scene.
- Every journey maps to a task an engineer would actually perform: review, inspection, collaboration, incident response, learning, or investigation.
- Every artifact is anchored to a Systems of Record or Product Model entity, so what appears in Sky Flight reflects what the organization actually knows.

The result is an operating environment for engineers, delivered as flight through the systems they build.

## Position in the Open Engineering Platform

The Open Engineering Platform is layered:

- **Kernel** — shared primitives and interoperability contracts across the ecosystem.
- **Operating Systems** — domain-specific runtimes built on the Kernel. Into The Blue OS is the spatial and immersive operating system.
- **Applications** — the destinations, tools, and experiences that run on those operating systems.

Sky Flight is both the reference application of ITB OS and its immersive gateway:

- **ITB OS supplies the runtime** — rendering, networking, avatars, spatial interaction, device integration, and AI services.
- **Sky Flight supplies the world** — the airspace, navigation, destinations, and journeys through which engineers experience that runtime.
- **Other Open Engineering applications populate destinations inside Sky Flight** — see [Destinations](#destinations) below. Future operating systems can expose their own destinations the same way.

In this arrangement, Sky Flight is the place users enter the Open Engineering ecosystem, and ITB OS is what makes it habitable.

## Design Philosophy

Sky Flight uses aviation as a **navigation model**, not decoration. Every concept in the product answers one of three questions a traveler asks: *Where can I go?*, *How do I get there?*, and *Who am I flying with?* The vocabulary is deliberately small and consistent so that first-time visitors and returning engineers reach for the same words to describe the same actions.

Three principles keep the metaphor useful rather than ornamental:

1. **Every noun corresponds to a real surface.** Hangars, Cockpits, and Control Towers are places you can enter, not marketing labels.
2. **Every verb is a movement.** Users *take a Flight*, *file a Flight Plan*, *reach a Destination*, and *return to a Waypoint* — the language stays kinetic because the experience is immersive.
3. **The map is bigger than any single application.** Destinations are supplied by the wider Open Engineering ecosystem, so the metaphor extends naturally as new operating systems and applications join the sky.

## Core Concepts

The following terms form the working vocabulary of Sky Flight. Each is defined once and used consistently across the product surface.

| Concept | Role |
| --- | --- |
| Hangar | The launcher. Where users choose which Flight to take. |
| Flight | A user session in progress — an active journey through one or more Destinations. |
| Destination | An immersive application or environment users fly to (see below). |
| Waypoint | A saved location a user can return to inside or across Destinations. |
| Flight Plan | A guided or curated experience that sequences Destinations and Waypoints. |
| Cockpit | The user's personal workspace within the airspace — controls, instruments, and immediate context. |
| Control Tower | The collaboration and orchestration surface where teams coordinate a Flight. |
| Air Traffic Control | The multi-user synchronization and presence layer that keeps concurrent Flights aware of each other. |

Read together, these concepts describe a complete operating environment: users depart from the **Hangar**, pilot from the **Cockpit**, travel along a **Flight Plan** through one or more **Destinations**, mark **Waypoints** they will return to, and stay coordinated with others through the **Control Tower** and **Air Traffic Control**.

## Destinations

Destinations are how Sky Flight opens onto the rest of the Open Engineering ecosystem. Rather than bundling every capability into a single application, Sky Flight is the immersive gateway from which each engineering domain becomes a place engineers can visit.

Representative Destinations already aligned with the ecosystem:

- **Agility Games** — a **training destination** where teams rehearse delivery practices and team dynamics in an immersive setting.
- **Code Smell Detectives** — an **investigation destination** where engineers walk through codebases, inspect anti-patterns, and reason about design decisions in space.
- **PKIStars** — a **cybersecurity destination** where certificate hierarchies, trust relationships, and key material can be explored spatially.

The Destination model is intentionally open: future Open Engineering operating systems and applications can expose their own Destinations inside Sky Flight without changing the core vocabulary. This keeps Sky Flight positioned as the entry point to the ecosystem, not as one application competing alongside the others.
