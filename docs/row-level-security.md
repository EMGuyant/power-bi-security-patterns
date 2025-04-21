# Row-Level Security (RLS) in Power BI

This section covers the basics of Row-Level Security (RLS) in Power BI, including both **Static RLS** and **Dynamic RLS** implementation examples using Power BI Desktop and the Power BI Service.

For the complete walkthrough, including step-by-step instructions, DAX expressions, visuals, and deployment guidance:

👉 **[Read the full blog post here](https://your-blog-url.com)**

---

## 📁 Sample File

You can download the example Power BI file for hands-on testing and learning:

➡️ [`pbix/row-level-security-example.pbix`](../pbix/rls-sample-report.pbix)

The file includes:
- Pre-configured static RLS roles
- A dynamic RLS setup using `USERPRINCIPALNAME()`
- Sample tables for employees and regions
- DAX filters for security enforcement

## 🧪 Testing with Temporary UPNs

To make testing the dynamic rls simple in Power BI Desktop, the model includes **5 temporary user principal names (UPNs)**. Each UPN is mapped to a different role in the `Employee` table. Use these test users using the **Dynamic RLS** and **"View as Other User"** options in Power BI Desktop:
- TEMP-UPN-1: Asia Sales
- TEMP-UPN-2: United States Sales
- TEMP-UPN-3: Europe Sales
- TEMP-UPN-4: Management
- TEMP-UPN-5: No role assigned

This allows you to preview and validate RLS filtering without needing real email addresses.

## 📚 Official Documentation

For additional guidance, refer to Microsoft’s official RLS documentation:  
[🔗 Row-level security (RLS) with Power BI](https://learn.microsoft.com/en-us/fabric/security/service-admin-row-level-security)

[🔗 Row-level security (RLS) guidance in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/guidance/rls-guidance)

---
