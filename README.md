# Jira-License-Request-System
Built a Jira license request workflow with an 8-level approval process and automated notifications using Flow Designer.

Overview:

I'm excited to share a solution I recently designed and implemented using ServiceNow Service Catalog and Flow Designer to streamline Jira license requests within our organization.

Challenge:

- Managing Jira license requests manually was time-consuming and lacked a structured approval workflow.
- Given the importance of governance and cost control, we needed a process where multiple stakeholders could review and approve requests before provisioning licenses.

Solution Implemented:

I developed a Service Catalog item for Jira license requests and configured an automated workflow using Flow Designer with the following capabilities:

- User-Friendly Request Form - Employees can easily raise a Jira license request through a standardized catalog item with required details.
- Multi-Level Approval Process - A robust approval workflow was implemented where 8 designated approvers must review and approve the request before it moves forward. This ensures proper validation, compliance, and accountability.

Automated Flow Execution

1. Using Flow Designer:
    - The request is triggered automatically upon submission.
    - Approval tasks are dynamically assigned to all 8 approvers.
    - The system ensures that all approvals are completed before proceeding.
    - Notifications and updates are sent throughout the process.

2. Improved Governance & Efficiency :
    - This solution eliminates manual follow-ups, reduces delays, and ensures that license allocation is controlled and auditable.

Outcome:

-  Faster turnaround time for requests.
-  Increased transparency in approvals.
-  Better control over license distribution.
-  Reduced manual effort for IT teams.

Key Learning:
  - Designing workflows with multiple approvers in Flow Designer helped me understand how to handle parallel approvals and approval aggregation logic effectively.
  - This implementation highlights how automation and proper workflow design can significantly improve operational efficiency and governance.

Demo Videos - Watch on LinkdIn:
[LinkdIn Post] - (https://www.linkedin.com/posts/sathish-s-132616264_servicenow-flowdesigner-automation-activity-7469368137327476736-8BhD?utm_source=share&utm_medium=member_android&rcm=ACoAAEDgAjYByl-9bH9C03fWczUpsuDQRM2BclY)
