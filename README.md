# Trevor Renner

Infrastructure Security Engineer at [MoonPay](https://www.moonpay.com), based in Vancouver, BC.

I build the guardrails and paved roads that detection engineers and analysts depend on. That means secure cloud infrastructure, useful telemetry, and tooling that takes some of the friction out of doing security work.

I care about what happens after something ships. Can people understand it, troubleshoot it, and safely change it? If every deployment or investigation needs someone who knows the secret handshake, there’s more engineering to do. I look for recurring problems and build shared capabilities around them.

## Things I’ve Built

| Project | Why I built it |
| --- | --- |
| [JWT URL Decoder](https://github.com/trenner1/jwt-url-decoder) | Debugging authentication shouldn’t require pasting a live token into someone else’s website. Decode JWTs locally, directly in the browser. |
| [Cloud Honeypot](https://github.com/trenner1/cloud-honeypot) | Put DShield infrastructure in AWS CDK so deployment is repeatable and I can spend more time looking at what shows up. |
| [SuperNav](https://github.com/trenner1/supernav) | I wanted Pop!_OS-style keyboard navigation between workspaces and monitors on my Mac. So I built it. |

## Building the Foundation

I’m working through my **BACS at SANS Technology Institute**, connecting the infrastructure I build to the security work it supports.

- **GSEC — completed:** Broadened my security foundation and helped me see how decisions across systems, networks, and access controls affect each other.
- **GCIH — completed:** Brought the incident into view. How does an attacker get in, what happens next, and what will responders need from the systems I build?
- **GCSA — completed:** Connected that thinking to cloud delivery, turning identity, infrastructure as code, and CI/CD into places to build secure defaults.
- **GMON — completed:** Focused on whether controls and monitoring give defenders useful visibility once everything is running.
- **GCIA — in progress:** Taking me deeper into packets and protocols so I can question the assumptions underneath an alert.
- **GCDA — next:** Bringing that foundation toward analyzing security data and developing actionable detections.

The goal is to own more of the whole path—from secure deployment to dependable telemetry, useful detections, and an investigation someone can carry forward—and close the gaps between those steps.

## Following the Evidence

I completed the **SANS ISC DShield internship**, running honeypots and investigating the activity they collected. The interesting part was figuring out what the logs actually supported and where I was filling in the blanks.

One question kept pulling me further: could threat actors use agentic probing to spot a honeypot by testing where its fake shell stops behaving like a real one? Controlled experiments gave me a candidate shell-response fingerprint to investigate. Whether the observed attackers used agents or recognized the honeypot remains unresolved.

Some recent write-ups:

- [A file called sshd turned out to be Panchan](https://medium.com/@trevor.l.renner/a-file-called-sshd-turned-out-to-be-panchan-65edf3607db6)
- [An SSH download attempt with an HTTPS backup](https://medium.com/@trevor.l.renner/an-ssh-download-attempt-with-an-https-backup-93010d3cfcfc)
- [My honeypot visitors had a Telegram shopping list](https://medium.com/@trevor.l.renner/my-honeypot-visitors-had-a-telegram-shopping-list-cc82873fe1c8)
- [The Confused Deputy Problem in Secret Management (Vault), JWTs, and AI Workloads](https://www.linkedin.com/pulse/confused-deputy-problem-vault-jwts-ai-workloads-trevor-renner-gvhoc)

## Find Me

[LinkedIn](https://www.linkedin.com/in/tlrenner) · [Medium](https://medium.com/@trevor.l.renner)
