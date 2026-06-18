# Exercise 4: Create a User and Assign an Azure RBAC Role

### Estimated Duration: 30 Minutes

## Lab Overview

Access to the new workload must follow least-privilege. As the Azure Administrator you must create an identity and grant it access through **Azure role-based access control (RBAC)** rather than handing out broad ownership.

This is an **assessment**: the task gives you the **symptom and the required outcome**, not the exact commands. Use Az PowerShell, the Azure CLI, or the portal. After the task, press **Validate** to score it.

> **Note:** Connect to the jump VM over RDP, sign in to the lab subscription / directory, and scope the role assignment to the lab resource group.

## Task 1: Create a user and assign it an RBAC role

**Symptom:** A team member needs scoped access to the lab resource group, but no user has been granted an Azure RBAC role there, so access is either missing or over-privileged.

**Required outcome:**

- A **user** is created in the lab's Microsoft Entra ID directory.
- That user is assigned an **Azure RBAC role** — **Reader** or **Contributor** — **scoped to the lab resource group**.

Create the user (if you reuse one from Exercise 3 that is fine), then create a role assignment granting it the **Reader** or **Contributor** role at the **lab resource group** scope. The validator looks for a role assignment in the lab resource group where the principal is a **user** and the role is **Reader** or **Contributor**.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task.
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at cloudlabs-support@spektrasystems.com. We are available 24/7 to help you out.

<validation step="0bb497d3-ae6e-4145-ae37-2f4fc45f3e24" />
