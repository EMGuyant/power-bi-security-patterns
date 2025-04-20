# Power BI Data Security Patterns

This repository contains hands-on examples and sample Power BI (.PBIX) files for implementing **Row-Level Security (RLS)**, **Partial Row-Level Security**, and **Object-Level Security (OLS)**. These design patterns help ensure that each Power BI user sees only the data they are authorized to view.

Whether you're securing reports by region, department, or data sensitivity, these samples provide a strong foundation for building secure and scalable Power BI solutions.

---

## 🔐 Security Topics Covered

| Topic                  | Description                                                                 | Link to Details |
|------------------------|-----------------------------------------------------------------------------|-----------------|
| **Row-Level Security** | Restrict data at the row level based on user identity or group membership.  | [View Details »](docs/row-level-security.md) |
| **Partial RLS**        | Secure specific data while preserving global context for calculations.      | [View Details »](docs/partial-rls.md) |
| **Object-Level Security** | Hide entire tables or columns from users based on their role.                | [View Details »](docs/object-level-security.md) |

Each example includes step-by-step guidance and downloadable `.pbix` files to test and extend on your own.

## 📩 Coming Soon

This guide is part of an RLS-focused series. Upcoming posts will explore:
- ✅ **Partial Row-Level Security** (for hybrid access control)
- 🛡 **Object-Level Security** (for hiding entire tables or columns)

---
## 🛠 How to Use  

1) Clone or download this repository to your local machine.
2) Open the security pattern file in Power BI Desktop.
3) Start exploring the different data security patterns within Power BI

## 🔑 Prerequisites

To optimize your learning experience, you should:

* Have a basic understanding of Power BI and DAX (Data Analysis Expressions)
* Install Power BI Desktop installed on your computer. You can download it for free from the [official Microsoft website](https://powerbi.microsoft.com/en-us/desktop/).


*⚠️ This repository is designed with the assumption that users have a basic familiarity with Power BI and DAX functions. If you're entirely new to these concepts, consider checking out the introductory materials available on the [Microsoft Learn for Power BI](https://learn.microsoft.com/en-us/training/powerplatform/power-bi?WT.mc_id=powerbi_landingpage-docs-link).*
