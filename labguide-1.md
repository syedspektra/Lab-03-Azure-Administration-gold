# Exercise 1: Configure a Virtual Network with Subnets

### Estimated Duration: 30 Minutes

## Lab Overview

A new workload needs its own network boundary in Azure. As the Azure Administrator you must stand up a **virtual network** in the lab resource group and carve it into **subnets** so that workload tiers can be isolated.

This is an **assessment**: each task gives you the **symptom and the required outcome** — not the steps. Decide the address space and subnetting yourself, then build it. After the task, press **Validate** to score it.

> **Note:** Connect to the jump VM over RDP, sign in to the lab subscription with `Connect-AzAccount` (or `az login`), and confirm you are in the lab resource group before you start.

## Task 1: Create a virtual network with at least two subnets

**Symptom:** The lab resource group has no virtual network the new workload can attach to, and there is nowhere to separate its tiers.

**Required outcome:** A **virtual network** exists in the lab resource group, and it contains **at least two subnets**.

Choose a non-overlapping address space (for example `10.10.0.0/16`) and divide it into two or more subnets (for example `10.10.1.0/24` and `10.10.2.0/24`). Create the virtual network in the **lab resource group** so the validator can find it. The subnet names are your choice; only the count and placement are checked.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task.
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at cloudlabs-support@spektrasystems.com. We are available 24/7 to help you out.

<validation step="b0913f32-5e37-4976-bb1b-2ca49b034697" />
