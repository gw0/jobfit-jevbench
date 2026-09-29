---
company: Huntress
title: Staff Software Engineer - Detection Platform (GoLang)
location: United States of America
url: https://job-boards.greenhouse.io/huntress/jobs/7977228003
posted_at: 2026-09-17
---

**Reports to: Engineering Manager**

**Location: Remote US**

**Compensation Range: $200,000 - $220,000 base plus bonus and equity**

**What We Do:**

Cybercrime is growing, and more businesses are getting hit by threats that used to target only the biggest organizations. That pushes defenders like us to operate at the highest level, and it deepens our need for good people who want to make a meaningful impact.

Founded in 2015 by former NSA cyber operators, Huntress is a remote-first team working to make enterprise-grade cybersecurity accessible to businesses of all sizes. We work closely with security teams and service providers protecting complex environments, often without the time or headcount to handle it all. That’s why we build our technology in-house and back it with a 24/7 human-led Security Operations Center (SOC). As a result, our platform is never disconnected from the experts who manage it, ensuring our customers' protection.

Huntress now secures more than 5M endpoints and 14M identities worldwide. Those numbers keep growing because more businesses rely on us to help carry the load and operate with more confidence. Every day, you can see that commitment in how we stand with our customers and how we show up for each other.

**About the Team**

Huntress protects the small and mid-sized businesses that attackers assume can't afford a security team. The Detection Platform team builds the engines and pipelines that turn billions of raw telemetry events into the signals our 24/7 SOC acts on. Every detection Huntress ships, across endpoint, identity, SIEM, and third-party EDR, runs through systems this team owns. We measure ourselves on two things: time to detection and detection engine uptime.

**About the Role**

We're hiring a Staff Software Engineer to help build and rebuild these systems without disrupting the SOC that depends on them, and to make their behavior predictable under load. This is a hands-on technical leadership role: you'll lead major workstreams, set direction that other engineering teams build against, and write and review production code every week.

**What You'll Own**

* **Detection engine and pipeline modernization.** We're rewriting our detection engine to support the full Sigma v2 specification, including stateful correlation of patterns across many events over time. In parallel, we're reworking several existing detection pipelines and building new ones, moving off the bespoke per-product detectors we've accumulated and onto a common platform. You'll lead major workstreams across both and own the validation approach that proves a reworked pipeline still behaves like the one it replaces, so we can turn old paths off knowing we haven't lost anything.
* **Reliability and behavior under load.** A detection pipeline that quietly stops producing signals is worse than one that crashes loudly, and detection volume spikes for reasons we don't always control. You'll build the guarantees that make quiet failure impossible: end-to-end latency measurement, liveness coverage, and alerting that fires when expected work stops arriving. You'll also build the mechanisms that keep a spike bounded and recoverable.
* **Event schemas and data contracts.** Our schema and transformer layer are what several other engineering teams build their detections against. You'll help drive toward a coherent internal standard and build the validation and drift-detection tooling that catches upstream changes before they break detections.

**What We're Looking For**

**Required**

* Deep experience designing, building, and operating production distributed systems at scale, primarily in Go, with the range to work across several layers of the stack.
* You have replaced or substantially re-architected a live, high-throughput system without breaking its consumers, and you can walk us through how you proved the new path was equivalent, staged the cut-over, and decided it was safe to retire the old one.
* Experience with high-volume event or data pipelines, and a good feel for how they behave under load: where things queue, where they fall behind, and what happens to correctness when they do.
* Strong operability instincts. You design observability in rather than retrofitting it, and you've built alerting that catches the absence of expected work, not just errors.
* Demonstrated technical leadership across team boundaries. You've set a direction that other teams had to build against and raised the engineering bar around you, without needing positional authority.
* Judgment about production quality: when a system is good enough to ship, when it needs more evaluation, and when it shouldn't ship at all.
* Hands-on experience with AI coding tools, and a point of view on using them well, where correctness is a security outcome.

**Strongly Preferred**

* A background in security operations or security engineering: time spent writing or tuning detections, or working in a SOC. You know what makes a detection maintainable, how fast noise erodes a SOC's trust in its tooling, and why a missed detection is a different class of failure than a noisy one.
* Experience with detection-as-code or other rule- and DSL-driven systems, including the parsing and evaluation work that supporting a specification properly entails.
* Experience building platform tooling for non-engineer authors such as rule writers, analysts, and researchers, where the product surface is a language, an API, and a feedback loop.
* Ruby on Rails experience. Some of our pipeline and application code is Rails, and you'll occasionally read and review Ruby. It's a nice-to-have, not a requirement; we'll help you ramp.

**Our Stack**

You'll work primarily in Go across our detection engines, pipelines, and the services around them, with Kafka, Temporal, Redis, ClickHouse, Elasticsearch, and Kubernetes across AWS and Azure. Some of our pipeline and application code is Ruby on Rails. Detection logic is written in Sigma.

We don't expect prior experience with all of it, and we're not screening on the list; Go is the one language we'll assess directly in interviews. You should be someone who likes being fluent across a broad stack rather than being specialized in one corner of it.

**What We Offer:**

* 100% remote work environment - since our founding in 2015
* Generous paid time off policy, including vacation, sick time, and paid holidays
* 12 weeks of paid parental leave
* Highly competitive and comprehensive medical, dental, and vision benefits plans
* 401(k) with a 5% contribution regardless of employee contribution
* Life and Disability insurance plans
* Stock options for **all** full-time employees
* One-time $500 reimbursement for building/upgrading home office
* Annual allowance for education and professional development assistance
* $75 USD/month digital reimbursement
* Access to the BetterUp platform for coaching, personal, and professional growth

*Huntress is committed to creating a culture of inclusivity where every single member of our team is valued, has a voice, and is empowered to come to work every day just as they are.*

*We do not discriminate based on race, ethnicity, color, ancestry, national origin, religion, sex, sexual orientation, gender identity, disability, veteran status, genetic information, marital status, or any other legally protected status.*

*We do discriminate against hackers who try to exploit businesses of all sizes.*

**Accommodations:**

*If you require reasonable accommodation to complete this application, interview, or pre-employment testing or participate in the employee selection process, please direct your inquiries to* [*redacted@example.com*](mailto:redacted@example.com)*. Please note that non-accommodation requests to this inbox will not receive a response.*

**Huntress uses artificial intelligence tools to assist in reviewing and evaluating job applications, including resume screening, skills assessment, and candidate matching and comparisons. These AI tools support our human recruiters in the initial review process, but do not make final hiring decisions without human involvement. By submitting your application, you acknowledge this use of AI in our recruitment process. Please review our [Candidate Privacy Notice](https://trust.huntress.com/?itemUid=47f0a941-b86f-4864-a0d0-a224a34cfd57&source=click) for more details on our practices and your data privacy rights.**

**#BI-Remote**
