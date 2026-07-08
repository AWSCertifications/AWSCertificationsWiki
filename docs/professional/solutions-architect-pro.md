# AWS Certified Solutions Architect Professional

<div class="cert-header" markdown>

<div class="cert-badge" markdown>
![AWS Certified Solutions Architect Professional badge](../assets/images/certifications/solutions-architect-pro.png){ width="200" loading=lazy }
</div>

<div class="cert-badge-body" markdown>

**AWS Certified Solutions Architect Professional** <span class="cert-level cert-level-professional">Professional</span>

**SAP-C02**

A comprehensive resource guide for the AWS Solutions Architect Professional exam.

</div>

</div>

| Detail | Value |
|--------|-------|
| Exam Code | SAP-C02 |
| Duration | 180 minutes |
| Cost | $300 USD |
| Passing Score | 750 / 1000 |
| Questions | 75 (scored) |
| Recommended Experience | 2+ years hands-on AWS architecture |
| Official Page | [AWS Solutions Architect Professional](https://aws.amazon.com/certification/certified-solutions-architect-professional/) |

!!! tip "Last Updated"
    This guide was last updated on **18 April 2026**.

## tl;dr

1. Get **Associate-level knowledge** first — see the [Solutions Architect Associate guide](../associate/solutions-architect.md)
2. Get **one** video course:
    - **Exam-focused:** Stephane Maarek / Neil Davis on Udemy
3. Read **whitepapers** (especially WAF), review re:Invent announcements
4. Do **one** set of quality practice exams — TutorialsDojo or Stephane Maarek
5. Consider exam center vs home, and ESL+30 min extension
6. Take and pass the exam!

---

## Exam Details

- **Exam code:** SAP-C02
- **Official page:** [AWS Solutions Architect Professional](https://aws.amazon.com/certification/certified-solutions-architect-professional/)
- **Exam guide:** [SAP-C02 Exam Guide (PDF)](https://d1.awsstatic.com/training-and-certification/docs-sa-pro/AWS-Certified-Solutions-Architect-Professional_Exam-Guide.pdf)

!!! tip "Subreddit"
    Search past discussions: [r/AWSCertifications SAP-C02](https://www.reddit.com/r/AWSCertifications/search/?q=SAP-C02&restrict_sr=1)

---

## Video Courses

### Free

**AWS Skill Builder — Free Exam Prep**

Covers high-level domains but is **not** a comprehensive deep dive.

[Search Skill Builder for SAP](https://skillbuilder.aws/search?page=1&examCertificationName=AWS+Certified+Solutions+Architect+-+Professional&price=free&category=learning_plan)

!!! note
    Skill Builder courses alone are **not enough** to pass.

**Andrew Brown / FreeCodeCamp (YouTube)**

Approximately **70 hours** of free content.

[Watch on YouTube](https://youtu.be/hyEw7dQ9-JE)

### Paid

| Instructor | Description | Link |
|------------|-------------|------|
| **Stephane Maarek** | Frequently updated, exam-focused, recommended for most certification candidates. Best suited for preparing for the latest AWS certification exams. | [courses.datacumulus.com](https://courses.datacumulus.com/) |
| **Neil Davis** | Digital Cloud on Udemy | [Udemy Course](https://www.udemy.com/course/aws-certified-solutions-architect-professional/) |
| **QA Learning** | Enterprise training; includes a learning plan and practice exam | [QA SAP Course](https://platform.qa.com/learning-paths/aws-certified-solutions-architect-professional-sap-c02-certification-preparation/) |
| **AWS SkillBuilder Enhanced** | Subscription with labs and official practice exam | [Skill Builder](https://skillbuilder.aws/) |

!!! warning "Udemy Pricing"
    Never pay more than **USD 20** for any Udemy course. Prices fluctuate daily. Use the author's coupon site, open in incognito, or create a new account for the best price.

### Deep Learning Resources

| Instructor | Description | Link |
|------------|-------------|------|
| **Adrian Cantrill** | Excellent for learning AWS architecture and AWS fundamentals. Exceptional hands-on explanations and deep technical content. Some AWS certification courses are becoming outdated compared to more actively maintained providers. Course updates generally lag behind the latest AWS certification blueprints. Better suited for building long-term AWS knowledge than for preparing for the latest certification exams. | [learn.cantrill.io](https://learn.cantrill.io/) |

---

## Additional Material

**WAF — Well-Architected Framework**

- [AWS WAF Overview](https://aws.amazon.com/architecture/well-architected/)
- Deep-dive into each WAF pillar — SkillBuilder course and official docs
- Read the **Reliability**, **Cost Optimization**, and **Security** whitepapers from [AWS Whitepapers](https://aws.amazon.com/whitepapers/)

**Migration & Modernization**

- [AWS Migration Hub](https://aws.amazon.com/migration-hub/) — review migration approaches and strategies

**Advanced Networking (not essential but useful)**

- Review advanced networking concepts from the [AWS Networking & Content Delivery blog](https://aws.amazon.com/blogs/networking-and-content-delivery/)

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

- None worth it at this level.

### Paid

| Provider | Link | Notes |
|----------|------|-------|
| **AWS Official Practice Exam** | [Skill Builder](https://skillbuilder.aws/search?page=1&examCertificationName=AWS+Certified+Solutions+Architect+-+Professional&price=subscription_needed&searchText=%22official+practice+exam%22) | Subscription required |
| **TutorialsDojo** | [tutorialsdojo.com](https://tutorialsdojo.com) | Highly recommended. Use the **review mode** on their site |
| **Stephane Maarek (Udemy)** | [courses.datacumulus.com](https://courses.datacumulus.com/) | |
| **Neil Davis (Udemy)** | [Udemy Course](https://www.udemy.com/course/aws-certified-solutions-architect-professional/) | |
| **QA Learning** | [QA Platform](https://platform.qa.com/) | Includes learning plan + practice exam |

!!! danger "Avoid Dumps"
    If someone offers the exact list of AWS questions or guarantees the question bank matches the exam — that is a dump. Using dumps risks a ban. Stick to legitimate sources.

---

## Hands-on Practice

### AWS Free Tier

The AWS Free Tier covers services relevant to SAP scenarios: EC2 (750 hours/month), S3 (5 GB), Lambda (1 million requests), and CloudFormation. Build multi-account architectures, hybrid networking, and migration scenarios. Set up billing alerts and monitor usage to avoid unexpected charges.

[AWS Free Tier](https://aws.amazon.com/free/)

### Advanced Architecture Labs

At the Professional level, focus on production-style projects that demonstrate enterprise-scale design patterns:

- **Multi-account strategies** — Practice with AWS Organizations, SCPs, and delegated administration using a sandbox account.
- **Hybrid networking** — Configure VPN connections, Direct Connect gateways, and Transit Gateway with route tables.
- **Migration scenarios** — Use AWS Migration Hub, DMS, and MGN to simulate large-scale migrations.
- **Disaster recovery** — Implement cross-region replication, Route 53 failover, and Aurora Global Database.

### AWS Skill Builder Labs

Skill Builder offers advanced labs covering Organizations, Control Tower, migration, and hybrid architectures.

[Skill Builder Labs](https://skillbuilder.aws/labs)

### Third-Party Platforms

- **KodeKloud** — Advanced AWS architecture scenarios covering multi-region deployments and hybrid cloud.
- **Cloud Academy** — Enterprise-focused AWS architecture labs for Professional-level scenarios.

[Projects & Hands-on](../projects-hands-on.md) — more practice resources and comparison of platforms.

---

## Community Advice

- Hands-on practice matters. Cross-account and organization patterns are difficult to practice in sandboxes.
- Don't memorize dumps.
- Practice exams identify weak areas; review every wrong answer.
- Read AWS documentation for unfamiliar services.

---

## Exam Tips

- Sleep well before the exam.
- Read every question carefully.
- Eliminate wrong answers first.
- Flag difficult questions and come back to them.
- Consider exam center over home — you can move around during the 3-hour exam.

---

## FAQ

**Do I need all this material?**
No. One from each category is enough. Example: Stephane Maarek's course + TutorialsDojo.

**Do I need hands-on work?**
Yes — hands-on experience is strongly recommended at the Professional level. Cross-account and organization patterns are difficult to practice in sandboxes.

**Where can I find vouchers?**
See [Vouchers & Discounts](../vouchers-discounts.md).

**Home vs exam center?**
Exam center is recommended — you can move around during the 3-hour exam.

**Can I get ESL accommodation?**
ESL+30 minutes is available via the Certmetrics portal before booking.

**I skipped SA Associate — is that okay?**
You must learn the curriculum — courses at this level assume Associate-level knowledge.

**Can someone new to IT take this?**
No. Professional level requires IT/AWS background.

**Is it worth it?**
SA Pro is the gold standard but does not guarantee a job.

**Is coding required?**
Basic CLI/scripting is very helpful. Use AI tools like CoPilot.

**Can I use ChatGPT / Amazon Q to learn?**
Use them cautiously — they can give incorrect answers. Always double-check against official docs.

**Are there books for this exam?**
Books go out of date too quickly. Video courses are recommended instead.

**Should I buy TutorialsDojo via Udemy or direct?**
Buy direct from their site — the **review mode** lets you go question-by-question rather than taking full exams.

**Why are practice exams harder than the video course?**
That's normal — work through incorrect answers and learn from them.

**What score should I get on practice exams?**
There is no magic number. High 80s is good, but the **learning** from reviewing incorrect answers matters more than the score.

**Can I skip a topic if someone said it wasn't on their exam?**
No. Everyone gets a different exam from a large question pool. Study everything in the exam guide.

**How does renewal work?**
Passing SA Pro renews an active SA Associate and Cloud Practitioner certification.

---

## Related Pages

- [Solutions Architect Associate](../associate/solutions-architect.md)
- [DevOps Engineer Professional](devops-engineer-pro.md)
- [Certification Pathways](../certification-pathways.md)
- [Vouchers & Discounts](../vouchers-discounts.md)
- [Free Learning](../free-learning.md)
- [Exam Benefits](../exam-benefits.md)
- [Tutorials Dojo](../tutorialsdojo.md)
- [Projects & Hands-on](../projects-hands-on.md)
