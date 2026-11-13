# Day-one admin checklist

Ten decisions to make before a company's first repository, in roughly this order. Written for **GitHub Enterprise Cloud**; most rows also apply to a single organization on **GitHub Team**.

| # | Decision | Do this | Where |
|---|---|---|---|
| 1 | **Two or more enterprise owners** | Never just one. Keep a break-glass owner (with managed users, the setup user) and store its recovery codes somewhere safe. | Enterprise → People → Administrators |
| 2 | **Identity: managed users or personal accounts** | Decide before the first repository, because switching later means a migration. With Enterprise Managed Users, your identity provider (such as Entra ID) creates and removes accounts and handles sign-in and MFA. With personal accounts, require SAML single sign-on and 2FA. | Enterprise → Settings → Authentication security |
| 3 | **Few organizations, predictable names** | Split organizations by ownership or compliance boundary, not by team. Use template repositories to give new projects the same structure. | Enterprise → Organizations |
| 4 | **Base permission and teams** | Set the organization's base permission to Read (or No permission), and grant Write through teams synced from identity provider groups. | Organization → Settings → Member privileges, and Teams |
| 5 | **Enterprise policies** | Decide repository creation and visibility, forking, Actions, Copilot, and security defaults. "No policy" leaves the choice to each organization's owners. | Enterprise → Policies |
| 6 | **Rulesets on main** | Require a pull request, a review, and passing checks, and block force pushes. Set rulesets once at the organization level (Team and Enterprise) or the enterprise level (Enterprise). On Enterprise, try new rulesets in evaluate mode first. | Organization → Settings → Repository → Rulesets |
| 7 | **Push protection everywhere** | Apply one security configuration to every repository and make it the default for new ones. Private repositories need GitHub Secret Protection. | Organization → Settings → Advanced Security → Configurations |
| 8 | **Audit log streaming** | Stream the audit log to your SIEM or storage (Azure Event Hubs or Blob Storage, Splunk, Datadog, Amazon S3, and others), so you keep events longer than GitHub's 180 days. | Enterprise → Settings → Audit log → Log streaming |
| 9 | **Network and Server links** | Turn on an IP allow list if your security team requires one. Use GitHub Connect if you also run GitHub Enterprise Server. | Enterprise → Settings → Authentication security, and GitHub Connect |
| 10 | **Licenses and budgets** | Know who uses a seat. Set budgets for Copilot AI credits (overage is on unless you cap it), Actions, and Codespaces. | Enterprise → Billing & Licensing |

## Official docs

- [About enterprise accounts](https://docs.github.com/en/enterprise-cloud@latest/admin/overview/about-enterprise-accounts)
- [About Enterprise Managed Users](https://docs.github.com/en/enterprise-cloud@latest/admin/managing-iam/understanding-iam-for-enterprises/about-enterprise-managed-users)
- [About rulesets](https://docs.github.com/en/enterprise-cloud@latest/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets)
- [GitHub Advanced Security billing](https://docs.github.com/en/billing/concepts/product-billing/github-advanced-security)
- [Streaming the audit log for your enterprise](https://docs.github.com/en/enterprise-cloud@latest/admin/monitoring-activity-in-your-enterprise/reviewing-audit-logs-for-your-enterprise/streaming-the-audit-log-for-your-enterprise)
- [Who consumes a license](https://docs.github.com/en/enterprise-cloud@latest/billing/reference/github-license-users)

GitHub moves settings around from time to time. If a path above has changed, search the docs for the decision's name.
