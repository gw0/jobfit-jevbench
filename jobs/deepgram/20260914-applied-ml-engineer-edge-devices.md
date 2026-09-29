---
company: Deepgram
title: Applied ML Engineer -  Edge Devices
location: USA | Remote
url: https://jobs.ashbyhq.com/Deepgram/94ae2781-a85f-493a-86c1-ff85a9289355
posted_at: 2026-09-14
---

**Company Overview**
====================

Deepgram is the leading platform underpinning the emerging trillion-dollar Voice AI economy, providing real-time APIs for speech-to-text (STT), text-to-speech (TTS), and building production-grade voice agents at scale. More than 200,000 developers and 1,300+ organizations build voice offerings that are ‘Powered by Deepgram’, including Twilio, Cloudflare, Sierra, Decagon, Vapi, Daily, Cresta, Granola, and Jack in the Box. Deepgram’s voice-native foundation models are accessed through cloud APIs or as self-hosted and on-premises software, with unmatched accuracy, low latency, and cost efficiency. Backed by a recent Series C led by leading global investors and strategic partners, Deepgram has processed over 50,000 years of audio and transcribed more than 1 trillion words. There is no organization in the world that understands voice better than Deepgram.

**Company Operating Rhythm**
============================

At Deepgram, we expect an AI-first mindset—AI use and comfort aren’t optional, they’re core to how we operate, innovate, and measure performance.

Every team member who works at Deepgram is expected to actively use and experiment with advanced AI tools, and even build your own into your everyday work. We measure how effectively AI is applied to deliver results, and consistent, creative use of the latest AI capabilities is key to success here. Candidates should be comfortable adopting new models and modes quickly, integrating AI into their workflows, and continuously pushing the boundaries of what these technologies can do.

Additionally, we move at the pace of AI. Change is rapid, and you can expect your day-to-day work to evolve just as quickly. This may not be the right role if you’re not excited to experiment, adapt, think on your feet, and learn constantly, or if you’re seeking something highly prescriptive with a traditional 9-to-5.

About the role
--------------

Deepgram's speech models are among the fastest and most accurate in the world, and today we run them at scale on NVIDIA GPUs. Our customers increasingly need those same models on hardware we don't control: non-NVIDIA accelerators, edge servers, and embedded platforms with their own inference runtimes, operator sets, and constraints. Getting Deepgram models onto those platforms, with as few changes to the model as possible and no changes to the hardware paradigm, is the job.

As an Applied ML Engineer on the Partner Platform Engineering team, you sit one layer above the metal. You take a Deepgram model as it exists today and adapt it to run correctly and efficiently within a target platform's existing kernel and runtime paradigm: swapping or reshaping operators, adjusting architecture parameters, choosing quantization and precision schemes, and validating accuracy and latency on the real device. Where a standard kernel isn't enough, you work with our Embedded AI Engineers, who write the custom kernels, and fit the model to what they build. You also own the deployment process that gets those adapted models onto edge targets repeatably.

This is not a research role and not a cloud-serving role. It is applied ML for edge deployment. It is a great fit for a senior engineer who has already shipped models to non-GPU or edge hardware and wants to do it across many platforms, or a staff-level engineer who wants to define how Deepgram ports speech models to new hardware. We'll set the level to your experience.

What you'll do
--------------

* Port Deepgram speech models to non-NVIDIA and edge platforms, adapting model structure and parameters so they run within the target's existing operator set, runtime, and kernels with minimal modification.
* Own serving-side model decisions for edge targets: quantization and precision choices, operator substitution, graph rewrites, and architecture tweaks that fit a model to a device's constraints while holding accuracy and latency.
* Validate every port on real hardware: build accuracy, latency, throughput, and memory benchmarks per platform, and catch regressions before a customer does.
* Build the deployment path for edge targets: model packaging, conversion pipelines, versioning, and automated delivery so shipping a model to a new device is repeatable rather than bespoke.
* Work with Embedded AI Engineers when a standard kernel isn't enough: specify what the model needs, then adapt the model to use the custom kernel they deliver.
* Partner with platform and silicon vendors on their runtimes and toolchains, and turn their expected model format and operator conventions into a working Deepgram deployment.
* Feed edge constraints back to Research and Impeller so future models are easier to port, without taking on research or core productionization work yourself.
* As the team grows, take on adjacent production concerns at the edge: automated deployment, model security and integrity on customer hardware, and fleet-level observability.

You'll love this role if you
----------------------------

* Have already fought to get a model running on hardware that wasn't built for it, and want to do that across many platforms.
* Prefer changing the model to fit the hardware over changing the hardware to fit the model, and know when each is the right call.
* Care about the numbers on the device, not the numbers in the notebook.
* Like being the bridge between the team writing kernels and the team training models.
* Want to ship to customers, not publish.

It's important to us that you have
----------------------------------

* Hands-on experience deploying ML models to edge or non-NVIDIA hardware in production. **This is required.** Cloud-only or GPU-only serving experience does not qualify on its own.
* Working knowledge of quantization and precision tradeoffs (INT8, FP16, mixed precision, calibration) and how they affect accuracy and latency on real targets.
* Experience with at least one edge or vendor inference runtime and its conversion toolchain (for example ONNX Runtime, TFLite, ExecuTorch, OpenVINO, Qualcomm AI Engine, or a vendor NPU SDK).
* Ability to modify a model to fit a platform: reading and rewriting model graphs, swapping unsupported operators, and adjusting architecture parameters without breaking accuracy.
* Strong Python and PyTorch, and production-quality engineering habits: tests, reproducibility, and benchmarks that others can rerun.
* Comfort building automation around model conversion and deployment.
* A builder mindset and clear communication: you can scope a port on an unfamiliar platform and drive it to a measured result.

It would be great if you had
----------------------------

* Experience with speech, audio, or streaming/real-time models specifically.
* Exposure to writing or reading low-level kernels (CUDA, Metal, NEON, or vendor DSP code), enough to collaborate closely with embedded engineers.
* Experience with model security or integrity on deployed devices: signing, encrypted model storage, safe updates.
* Familiarity with several accelerator families (Qualcomm, Apple, ARM, Intel, AMD, or custom NPUs) and their quirks.
* A track record of building internal tooling that made porting or deploying models measurably faster.

***Notice**: We're aware of individuals impersonating Deepgram recruiters. All legitimate Deepgram recruiting communication comes from an @*[*deepgram.com*](http://deepgram.com) *email address. If you've received a message claiming to be Deepgram, please forward it to redacted@example.com.*
