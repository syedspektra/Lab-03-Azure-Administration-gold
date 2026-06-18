# Exercise 2: Deploy an Azure SQL Database and Connect to It

### Estimated Duration: 30 Minutes

## Lab Overview

The new workload needs a managed relational database. As the Azure Administrator you must deploy an **Azure SQL Database** in the lab resource group and prove it is reachable from the jump VM.

This is an **assessment**: the task gives you the **symptom and the required outcome**, not the exact commands. Choose your own tooling (Az PowerShell, the Azure CLI, or the portal). After the task, press **Validate** to score it.

> **Note:** Connect to the jump VM over RDP, sign in to the lab subscription, and create everything in the lab resource group. `sqlcmd` is pre-installed for connecting to the database.

## Task 1: Deploy an Azure SQL Database and connect to it from the VM

**Symptom:** There is no Azure SQL logical server or database in the lab resource group, so the workload has nowhere to store its data and cannot be reached from the jump VM.

**Required outcome:**

- An **Azure SQL logical server** and a **database** (any database other than the built-in `master`) are deployed in the **lab resource group**.
- The server has a **firewall rule** that allows access (for example "Allow Azure services and resources" or a rule covering the VM's public IP), so the database is **reachable from the jump VM**.

Create the logical server (with an admin login and password), then a database on it. Add a server-level firewall rule so traffic is permitted, and confirm connectivity from the VM with `sqlcmd` (for example a `SELECT name FROM sys.databases` query). The validator checks that a non-`master` database exists in the lab resource group.

> **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
> - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task.
> - If not, carefully read the error message and retry the step, following the instructions in the lab guide.
> - If you need any assistance, please contact us at cloudlabs-support@spektrasystems.com. We are available 24/7 to help you out.

<validation step="9ef32378-8ea3-4fc0-a9fd-7350d22b48ca" />
