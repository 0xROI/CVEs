# Server Status v.2.0 is vulnerable to RXSS

-------------------

Publish Date:7/27/2024

Affected Versions: 2.0

Vulnerable Component: Admin Password Change.

CWE-79: Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')

CVE: Pending


### Summary

The vulnerability allows an attacker to inject malicious scripts into certain fields, potentially leading to the execution of arbitrary code or unauthorized access to user-sensitive information.


### Fix
----

This patch includes the following fixes:

* Validation of user supplied data.

### Mitigation
-------------

If you are unable to apply the patch immediately, you can mitigate the risk by taking the following steps:

* Restrict access to the vulnerable component
* Implement additional security measures to detect and prevent attacks
* Monitor for signs of exploitation


