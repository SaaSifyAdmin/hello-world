# Overview
The document explains the steps to set up a SaaS product in GCP marketplace.
## Prerequisite
Ensure SaaSify tenant is created with GCP as the Provider enabled, and Publisher Admin permission is given to the Publisher in SaaSify.This can be done with the support of SaaSify Engineering Team.
<br>
### Service account creation for GCP API access – SaaSify Team
A Service Account is required to communicate with GCP Marketplace APIs like Cloud Commerce Partner Procurement API and Service Control API to manage customer purchases, accounts, entitlements, and usage report management.
<ol>
<li>Open the Service Accounts page in the GCP Console (https://console.cloud.google.com/iam-admin/serviceaccounts) under IAM & Admin.</li>
<li>Click Create Service Account.</li>
<li>Enter a service account name (saasify-marketplace-service) and click on Create and Continue</li>
</ol>

4. Open the Service Accounts page in the GCP Console (https://console.cloud.google.com/iam-admin/serviceaccounts) under IAM & Admin.
5. Click Create Service Account.
6. Enter a service account name (saasify-marketplace-service) and click on Create and Continue
7. Click [here](https://spektrasystems.com) to know more about Spektra Systems. 

### Section 1
this is **really** important and I want this to *stand out* too
- [X] This is item 1
- [X] This is item 2
- [ ] ~~This is item 3~~
- [X] This is item 4
- [ ] This is item 5  
This is how you write a line of code for `console.log` in JavaScript

Code Changes

```Diff
-const a ='aaaa';
-console.log(a);
+const b ='bbbb';
+console.log(b);
return a;
```

### Discussion on Partner Advantage with Google Team 
> comment part 1

Following our discussion on Teams, I recommend we use option A.

> comment part 2

Following our discussion on Teams, I recommend we use option B.

**GCP – Integrating SaaS products with Cloud Marketplace – Product Setup**
| Version Number | Date | Remarks |
| :---: | --- | --- | 
| 1.0 | 2023-05-12 | GCP Product Setup |
