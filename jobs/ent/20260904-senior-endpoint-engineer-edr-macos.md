---
company: Ent
title: Senior Endpoint Engineer, EDR (macOS)
location: Remote
url: https://jobs.ashbyhq.com/ent-security/bbc336a1-3858-487e-a9a4-ab47be21d349
posted_at: 2026-09-04
---

**Senior Endpoint Engineer, EDR (macOS)**
=========================================

**About Ent**
-------------

Ent is the intent-aware workspace security platform for securing human and AI-driven work. Built to protect productivity, the new attack surface, Ent understands not just what users and agents do but why, and intervenes at the moment of risk before incidents occur. Where existing tools see events, Ent sees intent, so security teams can step in at the moment of risk instead of investigating days later. Founded by Lou Manousos and Brandon Dixon, co-founders of RiskIQ (acquired by Microsoft) and the team behind Microsoft Security Copilot, Ent is in production with Global 2000 customers across hospitality, financial services, and defense, and backed by Decibel, Sequoia, Crosspoint Capital, Craft Ventures, Shield Capital, Felicis, and In-Q-Tel. We’re now hiring the team that will define this category.

**How We Work**
---------------

***Customer first.*** The product and the business are built around problems we’ve watched real security teams struggle with — not the other way around. Every roadmap conversation starts with what a CISO told us last week.

***Humble.*** No drama. We hire people who share the mission and trust each other to deliver. Teamwork over showmanship. Accountability over politics. The work speaks louder than the person doing it.

***Urgency.*** The window to build a durable security company in the AI era is open right now and it will not stay open. The shot clock has started. We move at the speed of the people we want to protect.

**About the Role**
------------------

As an Endpoint Engineer, EDR (macOS), you'll design and ship the privileged daemon, per-user agents, and system extensions that observe process, file, network, device, and user-interaction activity and turn it into high-fidelity signals about what an actor is actually trying to do.

You'll own EDR-class detection and prevention end to end: instrumentation through the Endpoint Security framework, Network Extensions, FSEvents, and IOKit; event enrichment and on-box correlation; and the interception logic — ES AUTH decisions, network flow filtering — that stops malicious activity before it completes. The constraints are real. The sensor spans multiple processes joined by XPC, runs privileged on large customer fleets, handles thousands of events per second against hard deadlines, and has to resist tamper and evasion without degrading the machine.

You'll work closely with security research, AI, platform, and product to feed sensor signals into on-device classification, policy enforcement, and investigation timelines.

**What You’ll Achieve**
-----------------------

* Design, build, and ship the privileged daemon, per-user agents, and system extensions that make up the macOS agent: observing process, file, network, device, and user-interaction activity and turning it into intent signals.
* Own EDR-class detection and prevention capability end to end: sensor instrumentation, event enrichment, on-box correlation and rule evaluation, and interception logic (Endpoint Security AUTH decisions, network flow filtering) that stops malicious or policy-violating activity before it completes.
* Instrument telemetry at the OS boundary: Endpoint Security framework, Network Extensions (NEFilterDataProvider), FSEvents, IOKit, and event taps and capture data-movement signals.
* Design and maintain the multi-process architecture that ties it together: launchd-managed daemon and agents, XPC protocols between components, code-signing-based peer authentication, and safe handling of untrusted input inside a privileged process.
* Harden the agent against tamper, bypass, and evasion using self-protection, integrity validation, and update-chain security.
* Hold sensor CPU, memory, and I/O inside strict budgets while processing thousands of events per second including hard real-time constraints like ES auth deadlines, profile hot paths, and eliminate regressions before they ship.
* Build test harnesses and automated regression coverage, including VM-based end-to-end testing that exercises real OS mechanisms.
* Drive high-severity customer escalations to root cause crashes, hangs, performance regressions, missed detections, permission and deployment failures at the code and OS-internals level, and convert escalation patterns into permanent fixes.
* Partner with the security research, AI, platform, and product teams to feed sensor signals into on-device ML classification, intent-aware policy enforcement, just-in-time interventions, and investigation timelines.
* Review code, mentor engineers, document design decisions, and share ownership of agent release quality and on-call.

**What You’ll Bring**
---------------------

### **Must-haves**

* 10+ years designing, building, and delivering production native systems software (Swift, C, C++, or Objective-C), a substantial portion of it in endpoint security, OS internals, or comparable performance-critical code with strong, current Swift, including modern concurrency (actors, Sendable, structured concurrency).
* Deep working knowledge of macOS internals: process and thread lifecycle, memory management, file systems, code signing and entitlements, launchd, IPC (XPC and Mach primitives), and the TCC permission model.
* Hands-on production experience with the Endpoint Security framework and/or Network Extensions, and an understanding of the system extension lifecycle that replaced kernel extensions.
* Demonstrated experience building or operating an EDR, EPP, XDR, DLP, or insider-risk product, or equivalent detection-and-response engineering.
* Practical fluency in attacker TTPs; you can reason about what an attack looks like in raw telemetry, not just in a written report.
* Strong low-level debugging skills: lldb, crash-dump and hang analysis, performance tracing with Instruments or equivalent.
* Multi-threaded and concurrent programming under load: synchronization, lock contention, race conditions, actor isolation, and object lifetime management.
* A track record of code running on large fleets without degrading end-user experience; you treat stability and performance as product features, and you understand enterprise deployment realities (MDM profiles, notarization, staged rollout, auto-update).
* Scripting fluency for tooling and test automation (Python, shell, or equivalent).
* Clear written and verbal communication with distributed teams and, when escalations demand it, directly with customers.

### **Bonus**

* Reverse engineering, malware analysis, or exploit and vulnerability research background.
* Experience shipping on-device ML inference (Core ML, ONNX Runtime, llama.cpp-class runtimes) inside a resource-constrained agent.
* Experience with browser extension or native-messaging integrations for telemetry capture.
* Cross-platform endpoint agent experience (Windows or Linux sensors) alongside macOS.

**Our Benefits**
----------------

* **Distributed workplace.** While we have positions we hire for in our SF office, we also hire remotely across North America.
* **Own a piece of the journey.** Every teammate gets meaningful equity on top of their salary.
* **We’ve got you covered.** 90% of your medical, dental, and vision is paid by Ent. We also cover 75% for your dependents.
* **Take the time you need.** Our flexible PTO lets you recharge, travel, or just take a breather.
* **Family matters.** 12 weeks of fully paid maternity leave (birth, adoption, or foster) and 8 weeks fully paid paternity leave.
* **Live well.** A $100 monthly lifestyle account to spend on what keeps you healthy and happy — fitness, wellness, learning, and more.
* **Set up your space.** A $500 home office stipend when you join as a remote employee.

**Diversity & Accommodations**
------------------------------

We’re committed to building a diverse, inclusive, and equitable workplace where people of all backgrounds, identities, experiences, and abilities are welcomed, valued, and supported. We recognize there is no single path to success and value nontraditional career journeys and diverse perspectives as key to building stronger, more innovative teams.

We strive to ensure an inclusive experience at every stage of hiring and are happy to provide reasonable accommodations. If you require accommodations or accessible formats at any point during our process, please let your recruiter know. As an equal opportunity employer, our hiring process is designed to put you at ease and help you do your best work. If there’s anything we can do to improve your experience, we’re always open to feedback.
