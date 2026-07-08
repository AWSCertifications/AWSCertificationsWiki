# AWS Certified Security Specialty

<div class="cert-header" markdown>

<div class="cert-badge" markdown>
![AWS Certified Security Specialty badge](../assets/images/certifications/security.png){ width="200" loading=lazy }
</div>

<div class="cert-badge-body" markdown>

**AWS Certified Security Specialty** <span class="cert-level cert-level-specialty">Specialty</span>

**SCS-C02**

A comprehensive resource guide for the AWS Security Specialty exam.

</div>

</div>

| Detail | Value |
|--------|-------|
| Exam Code | SCS-C02 |
| Duration | 170 minutes |
| Cost | $300 USD |
| Passing Score | 750 / 1000 |
| Questions | 65 (scored) |
| Recommended Experience | 2+ years security on AWS, SAA-level knowledge |
| Official Page | [AWS Security Specialty](https://aws.amazon.com/certification/certified-security-specialty/) |

!!! tip "Last Updated"
    This guide was last updated on **20 March 2025**. Content sourced from u/madrasi2021.

## tl;dr

1. Get **one** video course:
    - **Exam focus:** Stephane Maarek
2. Read **whitepapers** and review re:Invent announcements (security changes fast)
3. Do **one** set of quality practice exams — TutorialsDojo, Stephane Maarek, or Neil Davis

---

## Exam Details

- **Exam code:** SCS-C02
- **Official page:** [AWS Certified Security Specialty](https://aws.amazon.com/certification/certified-security-specialty/)
- **Exam guide:** [SCS-C02 Exam Guide (PDF)](https://d1.awsstatic.com/training-and-certification/docs-security-spec/AWS-Certified-Security-Specialty_Exam-Guide.pdf)

---

## Video Courses

### Free

**AWS Skill Builder — Exam Prep Course**

Free exam prep course covering the high-level domains.

[Search Skill Builder for SCS](https://skillbuilder.aws/search?page=1&examCertificationName=AWS+Certified+Security+-+Specialty&price=free&category=learning_plan)

### Paid

| Instructor | Description | Link |
|------------|-------------|------|
| **Stephane Maarek** | Frequently updated, exam-focused, recommended for most certification candidates. Best suited for preparing for the latest AWS certification exams. | [courses.datacumulus.com](https://courses.datacumulus.com/) |
| **Neil Davis** | Solid hands-on course on Udemy | [Udemy](https://www.udemy.com/course/aws-certified-security-specialty/) |
| **QA Learning (Cloud Academy)** | Enterprise training; includes learning plan and practice exam | [QA Platform](https://platform.qa.com/) |
| **SkillBuilder Enhanced** | Subscription — same course content as free plus labs | [Skill Builder](https://skillbuilder.aws/) |
| **ExamPro** | Partially complete — not yet recommended | [exampro.co](https://exampro.co) |

!!! warning "Udemy Pricing"
    Never pay more than **USD 20** for any Udemy course. Prices fluctuate daily. Use the author's coupon site, open in incognito, or create a new account for the best price.

### Deep Learning Resources

| Instructor | Description | Link |
|------------|-------------|------|
| **Adrian Cantrill** | Excellent for learning AWS architecture and AWS fundamentals. Exceptional hands-on explanations and deep technical content. Some AWS certification courses are becoming outdated compared to more actively maintained providers. Course updates generally lag behind the latest AWS certification blueprints. Better suited for building long-term AWS knowledge than for preparing for the latest certification exams. | [learn.cantrill.io](https://learn.cantrill.io/) |

---

## Additional Material

- [AWS Security Fundamentals](https://skillbuilder.aws/) on SkillBuilder
- [AWS Security Blog](https://aws.amazon.com/blogs/security/)
- [AWS Ramp-Up Guide: Security](https://d1.awsstatic.com/training-and-certification/ramp-up-guides/Ramp-Up_Guide_Security.pdf)
- [IAM Deep Dive from re:Inforce 2022](https://www.youtube.com/watch?v=y7sBfR_iXfU)
- [IAM Policy Ninja](https://www.youtube.com/watch?v=5e1gHjV9Vok) on YouTube

### AWS Skill Builder Microcredentials

Official AWS Skill Builder learning paths that include focused training, knowledge assessments, and digital badges. Useful for strengthening knowledge in specific AWS domains before or after certification preparation.

[Learn more](https://skillbuilder.aws/certification/microcredentials)

### AWS Customer Learning Programs

Official AWS service-specific learning programs that award Credly digital badges. These programs help learners deepen knowledge of individual AWS services, products, and solution areas beyond the certification blueprint.

[Explore programs](https://www.credly.com/organizations/amazon-web-services/collections/customer-learning-programs/badge_templates)

### AWS SimuLearn Learning Plan Badges

Official AWS interactive learning plans that validate practical cloud skills using simulated hands-on scenarios. Recommended for learners who want hands-on validation alongside certification preparation.

[Learn more](https://aws.amazon.com/blogs/training-and-certification/introducing-aws-simulearn-learning-plan-badges-verifiable-proof-of-hands-on-cloud-skills/)

---

## Practice Exams

### Free

None worth it.

### Paid

| Provider | Link | Notes |
|----------|------|-------|
| **AWS Official Practice Exam** | [Skill Builder](https://skillbuilder.aws/) | Updated February 10. Subscription required |
| **TutorialsDojo** | [tutorialsdojo.com](https://tutorialsdojo.com) | Highly recommended. AWS Authorized Training Partner |
| **Stephane Maarek** | [courses.datacumulus.com](https://courses.datacumulus.com/) | |
| **Neil Davis** | [Udemy](https://www.udemy.com/course/aws-certified-security-specialty/) | |
| **Whizlabs** | [whizlabs.com](https://www.whizlabs.com/aws-certified-security-specialty/) | |
| **QA Learning** | [QA Platform](https://platform.qa.com/) | Includes learning plan + practice exam |

!!! danger "Avoid Dumps"
    If someone offers the exact list of AWS questions or guarantees the question bank matches the exam — that is a dump. Using dumps risks a ban. Stick to legitimate sources.

---

## Hands-on Practice

### AWS Free Tier

The AWS Free Tier covers security services: IAM (free), KMS (20,000 requests/month), CloudTrail (free), and Config (free). Build identity policies, encrypt data, and set up detective controls. Set up billing alerts and monitor usage to avoid unexpected charges.

[AWS Free Tier](https://aws.amazon.com/free/)

### AWS Builder Labs

Builder Labs provide guided environments for security services including IAM, KMS, and CloudTrail with temporary AWS accounts.

[AWS Builder Labs](https://aws.amazon.com/training/digital/aws-builder-labs/)

### AWS Skill Builder Labs

Skill Builder offers additional security labs covering GuardDuty, Security Hub, Inspector, and advanced IAM policies.

[Skill Builder Labs](https://skillbuilder.aws/labs)

### Security Services to Practice

- **AWS IAM** — Write fine-grained policies, set up permission boundaries, and implement least-privilege access.
- **AWS KMS** — Create and manage keys, enable envelope encryption, and configure key rotation.
- **Amazon GuardDuty** — Set up threat detection and automate response with EventBridge and Lambda.
- **AWS Security Hub** — Aggregate findings from GuardDuty, Inspector, Config, and third-party tools.
- **Amazon Inspector** — Automate vulnerability assessments for EC2 and container workloads.
- **AWS Config** — Write Config rules for compliance monitoring and remediation.
- **AWS WAF** — Build web ACLs and rate-based rules to protect applications.

### Third-Party Platforms

- **KodeKloud** — Security-focused labs covering IAM policies, KMS, and security automation scenarios.
- **Whizlabs** — Sandbox for practicing AWS security configurations.
- **Cloud Academy** — Structured security learning paths with hands-on labs.

[Projects & Hands-on](../projects-hands-on.md) — more practice resources and comparison of platforms.

---

## Community Advice

- Hands-on practice matters. Set up security scenarios in your own account.
- Don't memorize dumps.
- Practice exams identify weak areas; review every wrong answer.
- Read AWS documentation for unfamiliar services.

---

## Exam Tips

- Sleep well before the exam.
- Read every question carefully.
- Eliminate wrong answers first.
- Flag difficult questions and come back to them.

---

## FAQ

**Do I need all this material?**
No. One from each category is enough.

**Do I need hands-on work?**
Yes — hands-on experience is strongly recommended.

**Where can I find vouchers?**
See [Vouchers & Discounts](../vouchers-discounts.md). Usually no discounts for Specialty exams. Passing SAA gives 50% off SCS.

**Can I cheat using dumps?**
You risk a ban. Not worth it.

**Can I pass with only free resources?**
Very few free resources exist for this exam. Spending on quality practice exams is strongly recommended.

**Can I take SCS as my first cert?**
No — you need Solutions Architect Associate level knowledge first.

**Are there books for this exam?**
Books go out of date quickly. A Sybex guide exists but video courses are recommended instead.

**Should I buy TutorialsDojo via Udemy?**
Not available for Security Specialty on Udemy. Buy direct from their site.

**I failed my practice exams — is that normal?**
Yes. Very normal. Work through incorrect answers and learn from them.

**What score should I get on practice exams?**
There is no magic number. The **learning** from reviewing incorrect answers matters more than the score.

**Can I skip a topic if someone said it wasn't on their exam?**
No. Everyone gets a different exam from a large question pool. Study everything in the exam guide.

---

## Related Pages

- [Solutions Architect Associate](../associate/solutions-architect.md)
- [Advanced Networking Specialty](advanced-networking.md)
- [Certification Pathways](../certification-pathways.md)
- [Vouchers & Discounts](../vouchers-discounts.md)
- [Free Learning](../free-learning.md)
- [Tutorials Dojo](../tutorialsdojo.md)
- [Projects & Hands-on](../projects-hands-on.md)
