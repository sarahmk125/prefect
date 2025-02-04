---
description: Monitor user access and activity with Audit Logs in Prefect Cloud.
tags:
    - UI
    - dashboard
    - Prefect Cloud
    - enterprise
    - teams
    - workspaces
    - organizations
    - audit logs
    - compliance
search:
  boost: 2
---

# Audit Log <span class="badge cloud"></span> <span class="pro"></span> <span class="badge enterprise"></span>

Prefect Cloud's [Pro and Enterprise plans](https://www.prefect.io/pricing) offer enhanced compliance and transparency tools with Audit Log.
Audit logs provide a chronological record of activities performed by members in your account, allowing you to monitor detailed Prefect Cloud actions for security and compliance purposes.

Audit logs enable you to identify who took what action, when, and using what resources within your Prefect Cloud account.
In conjunction with appropriate tools and procedures, audit logs can assist in detecting potential security violations and investigating application errors.  

Audit logs can be used to identify changes in:

- Access to workspaces
- User login activity
- User API key creation and removal
- Workspace creation and removal
- Account member invitations and removal
- Service account creation, API key rotation, and removal
- Billing payment method for self-serve pricing tiers

See the [Prefect Cloud plan information](https://www.prefect.io/pricing) to learn more about options for supporting audit logs.

## Viewing audit logs

From your Pro or Enterprise account settings page, select the **Audit Log** page to view audit logs.

![Viewing audit logs for an account in the Prefect Cloud UI.](/img/ui/audit-log.png)

Pro and Enterprise account tier admins can view audit logs for:

- Account-level events in Prefect Cloud, such as:
  - Member invites
  - Changing a member’s role
  - Member login and logout of Prefect Cloud
  - Creating or deleting a service account
- Workspace-level events in Prefect Cloud, such as:
  - Adding a member to a workspace
  - Changing a member’s workspace role
  - Creating or deleting a workspace

Admins can filter audit logs on multiple dimensions to restrict the results they see by workspace, user, or event type.
Available audit log events are displayed in the **Events** drop-down menu.

Audit logs may also be filtered by date range. Audit log retention period varies by [Prefect Cloud plan](https://www.prefect.io/pricing).
