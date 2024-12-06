# Nutanix Dial Task Tracker Overview

When converting a Nutanix cluster from ESXi to AHV, thorough cluster and VM preparation is the cornerstone of success. Adhering to all recommended best practices is crucial, but each customer environment introduces unique challenges, including policy requirements and physical infrastructure constraints. These factors often necessitate additional preparation steps.

In environments with multiple employees or shifts involved in the conversion, it becomes even more critical to track and verify completion of these tasks for each cluster. Skipping or inconsistently executing steps can lead to unreliable results, lack of transparency during the conversion process, and potentially a cascade of operational issues.

To address these challenges, the **Nutanix Dial Task Tracker** provides a streamlined solution for project teams and operations personnel to effectively track all tasks across clusters. This tool ensures that every step required to complete the project is documented and monitored, enabling the team to work as efficiently and effectively as possible while minimizing risks and avoiding errors.

The Nutanix Dial Task Tracker is a web-based application designed to help project teams and operations personnel efficiently manage and track all tasks required during the conversion of Nutanix clusters from ESXi to AHV. By providing clear visibility into progress, this tool ensures each step is documented and completed, reducing errors and improving overall project transparency.

## Technical Details
- **Web Server**: Runs on a basic IIS Web Server with support for Classic ASP.
- **Database**:
  - Powered by Microsoft SQL Server Express Edition (MSDE) by default.
  - Alternatively, the database can be integrated into an existing Microsoft SQL Server instance for environments with established infrastructure.

This straightforward setup makes the Nutanix Dial Task Tracker both easy to deploy and scalable for diverse customer environments.

## Installation
- View the [Installation Guide](https://github.com/emcandrew/Nutanix-Dial-Task-Tracker/wiki)

---

### Screenshots

![2024-07-15_15-22-44](https://github.com/user-attachments/assets/29778ecc-9179-4040-a10d-6f630404c639)

![2024-07-15_15-24-49](https://github.com/user-attachments/assets/bbd0d5c9-3e9d-446f-bfb8-99a2b6306148)

![2024-07-15_15-25-22](https://github.com/user-attachments/assets/9cc1978c-f62a-4c05-be60-4a0b3889ecf4)
