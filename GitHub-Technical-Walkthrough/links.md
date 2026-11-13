# Official links: GitHub Technical Walkthrough

Official GitHub and Microsoft links, plus git-scm.com (the Git project's own site). Checked on **2026-10-01**, with the Codespaces and rulesets entries rechecked on **2026-10-22**. GitHub reorganizes its docs from time to time, so if a link stops working, search for the page title on docs.github.com.

---

## Start here

- GitHub Skills — hands-on courses, now inside GitHub Learn — https://learn.github.com/skills *(skills.github.com redirects here)*
- GitHub certifications hub — register for exams — https://learn.github.com/credentials
- Microsoft Learn: GitHub Foundations Part 1 — https://learn.microsoft.com/en-us/training/paths/github-foundations/
- Microsoft Learn: GitHub Foundations Part 2 — https://learn.microsoft.com/en-us/training/paths/github-foundations-2
- GH-900 GitHub Foundations certification — https://learn.microsoft.com/en-us/credentials/certifications/github-foundations/
- GH-900 study guide — https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-900
- GitHub admin course GH-100 (for the admins in the room) — https://learn.microsoft.com/en-us/training/courses/gh-100t00
- Pro Git — the free book — https://git-scm.com/book
- Plans & pricing — https://github.com/pricing
- 30-day Enterprise Cloud trial — https://github.com/account/enterprises/new

---

## Where the facts in the class come from

### Git & scale
- git(1) manual — "the stupid content tracker" — https://git-scm.com/docs/git
- Pro Git, "A Short History of Git" (2005, Linus Torvalds, Linux kernel) — https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git
- Octoverse 2025 (180M+ devs · 630M repos · ~1B commits · 43.2M PRs/mo) — https://github.blog/news-insights/octoverse/octoverse-a-new-developer-joins-github-every-second-as-ai-leads-typescript-to-1/

### Plans & pricing
- Pricing page (Free / Team $4\* / Enterprise $21\* — "first 12 months", no published renewal price) — https://github.com/pricing
- GitHub's plans (Team/Enterprise feature lists, 99.9% SLA) — https://docs.github.com/en/get-started/learning-about-github/githubs-plans
- Enterprise product page (trial CTA, platform claims) — https://github.com/enterprise

### Copilot
- Plans (Free / Pro $10 / Pro+ $39 / Max $100 / Business $19 / Enterprise $39 + included credits) — https://docs.github.com/en/copilot/get-started/plans
- Billing for orgs & enterprises (credit pooling, $0.01/credit overage) — https://docs.github.com/en/copilot/concepts/billing/organizations-and-enterprises
- Usage-based billing (what consumes credits; completions unmetered; budgets) — https://docs.github.com/en/copilot/concepts/billing/usage-based-billing-for-organizations-and-enterprises
- "Copilot is moving to usage-based billing" (27 Apr 2026, effective 1 Jun 2026) — https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/
- Self-serve Business signups paused (22 Apr 2026) — https://github.blog/changelog/2026-04-22-pausing-new-self-serve-signups-for-github-copilot-business/
- Policies & billing changes (28 Aug 2026 — signups reopened 1 Sep, pay-before-access, unified policy from 28 Sep) — https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/
- "Copilot cloud agent" naming (1 Apr 2026) — https://github.blog/changelog/2026-04-01-research-plan-and-code-with-copilot-cloud-agent/
- What is GitHub Copilot (feature surfaces) — https://docs.github.com/en/enterprise-cloud@latest/copilot/get-started/what-is-github-copilot

### Secret Protection & Code Security
- Introducing the two SKUs ($19 / $30 per active committer, from 1 Apr 2025) — https://github.blog/changelog/2025-03-04-introducing-github-secret-protection-and-github-code-security/
- Advanced Security billing (active committer = 90 days, counted once; public repos free) — https://docs.github.com/en/billing/concepts/product-billing/github-advanced-security

### Actions
- Actions pricing update (hosted cut up to 39% from 1 Jan 2026; $0.002/min self-hosted charge **postponed** — page now titled "Update to GitHub Actions pricing") — https://github.blog/changelog/2025-12-16-coming-soon-simpler-pricing-and-a-better-experience-for-github-actions/
- Reduced hosted-runner pricing live (1 Jan 2026) — https://github.blog/changelog/2026-01-01-reduced-pricing-for-github-hosted-runners-usage/

### Codespaces
- Codespaces billing (120 core-hours free on personal accounts; $0.18/hr 2-core; $0.07/GB-mo) — https://docs.github.com/en/billing/concepts/product-billing/github-codespaces
- Who owns and pays for codespaces in an organization (Team or Enterprise; a Free organization can't pay) — https://docs.github.com/en/codespaces/managing-codespaces-for-your-organization/choosing-who-owns-and-pays-for-codespaces-in-your-organization

### Enterprise structure, identity & admin
- About enterprise accounts (hierarchy, policies) — https://docs.github.com/en/enterprise-cloud@latest/admin/overview/about-enterprise-accounts
- About Enterprise Managed Users (Entra/Okta/Ping, SCIM, restrictions, `_shortcode` usernames) — https://docs.github.com/en/enterprise-cloud@latest/admin/managing-iam/understanding-iam-for-enterprises/about-enterprise-managed-users
- Data residency on GHE.com (EU/US/AU/JP; EMU required) — https://docs.github.com/en/enterprise-cloud@latest/admin/data-residency/about-github-enterprise-cloud-with-data-residency
- Enterprise Server 3.21 GA (11 Jun 2026) — https://github.blog/changelog/2026-06-11-github-enterprise-server-3-21-is-now-generally-available/
- Who consumes a license — https://docs.github.com/en/enterprise-cloud@latest/billing/reference/github-license-users
- License consumption (one license per person; Cloud+Server sync) — https://docs.github.com/en/enterprise-cloud@latest/billing/concepts/license-consumption
- Enterprise Cloud trial (30 days, 50 seats) — https://docs.github.com/en/enterprise-cloud@latest/admin/overview/setting-up-a-trial-of-github-enterprise-cloud
- Audit log streaming (S3, Azure Blob/Event Hubs, Datadog, GCS, Splunk, Purview) — https://docs.github.com/en/enterprise-cloud@latest/admin/monitoring-activity-in-your-enterprise/reviewing-audit-logs-for-your-enterprise/streaming-the-audit-log-for-your-enterprise

### Rulesets
- About rulesets (layering, statuses, bypass; Evaluate = Enterprise) — https://docs.github.com/en/enterprise-cloud@latest/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets
- Organization rulesets on GitHub Team (16 Jun 2025) — https://github.blog/changelog/2025-06-16-organization-rulesets-now-available-for-github-team-plans/
- Enterprise rulesets GA (24 Mar 2025) — https://github.blog/changelog/2025-03-24-enterprise-custom-properties-enterprise-rulesets-and-pull-request-merge-method-rule-are-all-now-generally-available/

### How partners buy
- Creating an enterprise as a Microsoft CSP partner — https://docs.github.com/en/enterprise-cloud@latest/billing/how-tos/manage-for-client/create-as-csp-partner
- Creating & paying for a client's enterprise (reseller → billing manager) — https://docs.github.com/en/enterprise-cloud@latest/billing/how-tos/manage-for-client/create-client-enterprise
- Connecting an Azure subscription — https://docs.github.com/en/enterprise-cloud@latest/billing/how-tos/set-up-payment/connect-azure-sub
- Azure subscriptions concept (what can bill through Azure; unsupported offer types) — https://docs.github.com/en/billing/concepts/azure-subscriptions
- Metered billing for GHE + GHAS via Azure (1 Aug 2024; MACC eligibility) — https://github.blog/changelog/2024-08-01-introducing-metered-billing-for-github-enterprise-and-github-advanced-security/
