# Exercise 3: Create Microsoft Entra ID Users in Bulk

### Estimated Duration: 30 Minutes

## Lab Overview

The workload team is onboarding and needs a batch of identities provisioned at once. As the Azure Administrator you must create **Microsoft Entra ID (Azure AD) users in bulk**, following a consistent naming convention.

This is an **assessment**: the task gives you the **symptom and the required outcome**, not the exact commands. Script the bulk creation however you like (an Az PowerShell loop, the Azure CLI, or a portal CSV import). After the task, press **Validate** to score it.

> **Note:** Connect to the jump VM over RDP and sign in to the lab subscription / directory. Bulk user creation requires the lab identity to have the necessary Microsoft Entra ID (directory) permissions, which are granted in this environment.

## Task 1: Bulk-create at least five Entra ID users

**Symptom:** The onboarding batch has no identities in the lab's Microsoft Entra ID directory, so the new team members cannot sign in.

**Required outcome:** At least **five Microsoft Entra ID users** exist in the lab directory, all following a **naming convention** — use the prefix **`bulkuser`** (for example `bulkuser01` through `bulkuser05`).

Generate the users programmatically so the set is consistent: create accounts whose names / user principal names begin with `bulkuser` (such as `bulkuser01`, `bulkuser02`, … `bulkuser05`). The validator counts Entra ID users whose display name starts with `bulkuser` and requires at least five.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task.
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at cloudlabs-support@spektrasystems.com. We are available 24/7 to help you out.

<validation step="62773362-9ed0-4720-8cde-96edade230a6" />
