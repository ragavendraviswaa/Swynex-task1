# Swynex-task1
Cyber security task 1 posterswigerlab
# Swynex Cyber Security - Task 1
## Lab Assessment - Authorized Lab Environment

**Platform:** PortSwigger Web Security Academy
**Lab:** SQL injection vulnerability in WHERE clause allowing retrieval of hidden data
**Date:** 26 Sep 2026

### Vulnerability Details
- **Affected Component:** /filter?category= parameter
- **Severity:** High
- **Payload Used:** `' OR 1=1-- `
- **Impact:** Attacker can retrieve hidden/unreleased products. In real world, full database leak aagum.

### Evidence
Lab solved successfully in authorized PortSwigger lab. Screenshots added below.

![Lab Solved](lab-solved.png)

### Mitigation
1. Use Parameterized Queries / Prepared Statements
2. Implement strict input validation
3. Use least privilege for DB user

**Disclaimer:** This testing was performed ONLY on PortSwigger's intentionally vulnerable lab environment. No real or unauthorized website was tested.

---
By Ragavendra Viswaa
