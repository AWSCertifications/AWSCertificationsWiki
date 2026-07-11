# Hands-On Projects & Practice Labs

!!! tip "Why Hands-On?"
    Hands-on practice is essential for AWS certification success. Below are community-curated resources organized by category.

---

## Platform Comparison

| Provider | Official AWS | Free/Paid | Guided Learning | Hands-on | Digital Badge | Best For |
|----------|-------------|-----------|-----------------|----------|--------------|----------|
| **AWS Free Tier** | ✅ | ✅ Free | ❌ | ❌ | ❌ | Experimenting with real AWS services at no cost |
| **AWS Builder Center Sandbox** | ✅ | ✅ Free | ✅ | ✅ | ❌ | Official free sandbox — no account or billing required |
| **AWS Skill Builder Labs** | ✅ | ✅ 1 free/month | ✅ | ✅ | ❌ | Official guided labs aligned with exam objectives |
| **AWS Builder Labs** | ✅ | ✅ Free tier includes labs | ✅ | ✅ | ❌ | Browser-based step-by-step environments |
| **AWS Cloud Quest** | ✅ | ✅ 2 quests free | ✅ | ✅ | ✅ | Gamified learning for beginners |
| **AWS Skill Builder Microcredentials** | ✅ | ❌ Requires subscription | ✅ | ✅ | ✅ | Topic-focused skill validation with hands-on assessment |
| **AWS Customer Learning Programs** | ✅ | ✅ Free on Skill Builder | ✅ | ✅ | ✅ | Service-specific deep dives with digital badges |
| **AWS SimuLearn Learning Plan Badges** | ✅ | ✅ 2 free, 10 sub only | ✅ | ✅ | ✅ | Hands-on skill validation with customer simulations |
| **KodeKloud** | ❌ | ✅ Free labs available | ✅ | ✅ | ❌ | Hands-on AWS and DevOps scenarios |
| **Whizlabs** | ❌ | ❌ Paid | ❌ | ✅ Sandbox | ❌ | AWS sandbox with exam-focused practice |
| **Cloud Academy** | ❌ | ❌ Paid | ✅ | ✅ | ❌ | Structured learning paths with labs |
| **A Cloud Guru / Pluralsight** | ❌ | ❌ Paid | ✅ | ✅ | ❌ | AWS sandbox and video courses |

---

## Free AWS-Specific Resources

| Resource | Notes |
|----------|-------|
| [AWS Builder Center Sandbox](https://aws.amazon.com/about-aws/whats-new/2026/07/aws-builder-center-sandbox/) | Official free sandbox — temporary AWS environment, no account required |
| [AWS Builder Labs](https://skillbuilder.aws) | Free on Skill Builder; build various components step-by-step |
| [AWS Workshops](https://workshops.aws) | Free, but requires an AWS account |
| AWS Immersion Day Workshops | Covers core AWS services; often run by AWS teams |
| [Well-Architected Labs](https://www.wellarchitectedlabs.com) | Deep-dive into the Well-Architected Framework |
| AWS Documentation Tutorials | Search for **"tutorial"** in the [official docs](https://docs.aws.amazon.com) |
| [Cloud Resume Challenge](https://cloudresumechallenge.dev) | Popular project; nominal fee to host |
| **Andrew Brown** — [YouTube](https://youtube.com) / [ExamPro](https://exampro.co) | Very hands-on courses |
| **Andrew Brown** — FREE AWS Project Bootcamp | Full project-based bootcamp |
| [Cloud Quest](https://explore.skillbuilder.aws) | Cloud Practitioner and Generative AI quests are free on Skill Builder |
| [CardClash](https://skillbuilder.aws) | Architectural pattern game on Skill Builder |
| [TechWithLucy](https://youtube.com) | Hands-on lab walkthroughs on YouTube |

!!! warning "AWS Free Tier"
    AWS Free Tier now has a limited duration. Always monitor billing and set up budget alerts before launching resources.

---

## Paid Options

| Resource | Notes |
|----------|-------|
| [More Than Certified in Terraform](https://morethancertified.com) | Real-world AWS deployments with Terraform |
| [KodeKloud](https://kodekloud.com) | Junior sysadmin to advanced scenarios |
| [TutorialsDojo](https://tutorialsdojo.com) | Hands-on labs + AWS Sandbox |
| [Whizlabs](https://whizlabs.com) | Sandbox environment for practice |
| [A Cloud Guru](https://acloudguru.com) | Sandbox available if access is free through work |

!!! note "Free Trials"
    Some paid platforms offer free trials — check before committing.

---

## AWS Builder Center Sandbox

The [AWS Builder Center Sandbox](https://aws.amazon.com/about-aws/whats-new/2026/07/aws-builder-center-sandbox/) is an official, free, temporary AWS environment designed for hands-on learning and certification practice — **no AWS account or credit card required**.

### How It Works

- Access the sandbox through supported workshops on the [AWS Builder Center](https://aws.amazon.com/builder-center/)
- Each session provides a pre-configured, temporary AWS account
- Sessions currently last **up to 8 hours**
- All resources are **automatically cleaned up** when the session ends
- No risk of accidental AWS charges

### Comparison with Other Free Options

| Feature | Builder Center Sandbox | AWS Free Tier | Skill Builder Labs | SimuLearn |
|---------|----------------------|---------------|-------------------|-----------|
| AWS Account Required | ❌ No | ✅ Yes | ❌ No | ❌ No |
| Credit Card Required | ❌ No | ✅ Yes | ❌ No | ❌ No |
| Session Duration | Up to 8 hours | Ongoing (12-mo limit) | Varies by lab | Per scenario |
| Cleanup | Automatic | Manual | Automatic | N/A (simulated) |
| Real AWS Console | ✅ Yes | ✅ Yes | ✅ Yes | ❌ Simulated |
| Best For | Risk-free exploration | Ongoing projects | Guided labs | Skill validation |

### Recommended Use Cases for Certification Candidates

- **Foundational (CLF, AIF):** Explore core AWS services without account setup overhead
- **Associate:** Build architecture patterns and practice multi-service integrations safely
- **Professional:** Test complex multi-service scenarios without billing concerns
- **Specialty:** Experiment with security and networking configurations in a disposable environment

[Read more about the Builder Center Sandbox](builder-center-sandbox.md)

---

## AWS-Adjacent Learning

| Resource | Notes |
|----------|-------|
| [Linux Foundation — Intro to Linux](https://training.linuxfoundation.org) | Free intro course; foundational for AWS operations |
| [Google Cloud Shell](https://cloud.google.com/shell) | Free shell in browser; good for cross-cloud practice |
| [Docker Playground](https://labs.play-with-docker.com) | Free Docker environments |
| [James Spurin's DiveInto](https://diveinto.io) | DevOps / Ansible playgrounds |

---

!!! danger "Clean Up Resources"
    Always destroy resources after use to avoid unexpected charges. Use **CloudFormation** or **Terraform** for repeatable, teardown-friendly environments.
