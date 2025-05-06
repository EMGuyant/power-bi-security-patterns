# Object-Level Security in Power BI

This sample Power BI report demonstrates how to implement Object-Level Security (OLS) to control access to specific tables and columns in a dataset based on user roles.

For the complete walkthrough:

👉 **[Read the full blog post here]()**

---

## 📁 Sample File

You can download the example Power BI file for hands-on testing and learning:

➡️ [`pbix/object-level-security-example.pbix`](../pbix/ols-sample-report.pbix)


🔐 What’s Included
This sample shows how to:

- Hide the Reviews table for users not in the SalesLeadership role
- Hide specific customer columns (Address, ContractInformation, and PreferredContactMethod) from users not in the CustomerDetail role
- Configure Object-Level Security using Tabular Editor
- Test and assign roles through the Power BI Service

| Role Name | Access Granted |
| :-------- | :------------- |
| Regional Sales Basic | Basic access to assigned region sales data | 
| Regional Sales Advanced | Regional sales data and full access to the `Customers` table | 
| Product Analyst | Regional sales data and full access to the `Reviews` table |
| Leadership | Full access to assigned regions |

## 📚 Official Documentation

For additional guidance, refer to Microsoft’s official RLS documentation:  
[🔗 Object-Level security (OLS) with Power BI](https://learn.microsoft.com/en-us/fabric/security/service-admin-object-level-security)

[🔗 Object-Level security (OLS) in Azure Analysis Services](https://learn.microsoft.com/en-us/analysis-services/tabular-models/object-level-security)
