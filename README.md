# SOC-Practical-Scenarios-Real-World-Experience
Practical SOC scenarios from Let's Defend, featuring real-world cybersecurity investigations. Includes web attacks, suspicious commands, and IDOR analysis, using tools like SIEM, EDR, and log analysis. Showcases skills in threat detection, incident response, and documentation
## 🛡️ **Overview**
This repository showcases:
- Detailed case studies from SOC labs, including:
  - **Detecting suspicious commands (e.g., whoami, ls, cat)**.
  - **Investigating IDOR (Insecure Direct Object References) attacks.**
  - **Analyzing web attack patterns (e.g., cross-site scripting, LFI attempts).**
- Insights into real-world SOC workflows: log analysis, incident reporting, and documentation.

---

## 🧰 **Tools and Techniques**
During these practical exercises, I utilized various tools and methodologies:
- **SIEM (Security Information and Event Management):** Log analysis, threat detection.
- **Firewall Logs:** Investigating suspicious network activities.
- **Endpoint Detection and Response (EDR):** Monitoring endpoint security.
- **HTTP and Web Traffic Analysis:** Understanding requests, responses, and headers.
- **Attack Simulations:** Hands-on testing for command injections, IDOR, and other web attacks.

---

## 📂 **Included Scenarios**
### **1. SOC168 - Whoami Command Detected**
- **Objective:** Detect and analyze suspicious use of the `whoami` command in HTTP request bodies.
- **Outcome:** Identified potential reconnaissance activity, analyzed device actions, and documented incident reports.

### **2. SOC169 - Possible IDOR Attack**
- **Objective:** Investigate consecutive HTTP requests attempting to exploit insecure direct object references.
- **Outcome:** Confirmed non-automated IDOR activity, examined POST parameters, and recommended mitigation steps.

### **3. SOC166 - Suspicious JavaScript Detected**
- **Objective:** Analyze HTTP requests containing potential malicious JavaScript payloads.
- **Outcome:** Evaluated firewall logs, identified abnormal patterns, and escalated findings for remediation.

---

## 🎓 **Key Learnings**
1. **Incident Response:** Efficiently investigating and documenting incidents for quick escalation and resolution.
2. **Threat Detection:** Identifying malicious patterns in logs and network activity.
3. **Documentation:** Maintaining accurate records and detailed analysis for SOC workflows.
4. **Security Best Practices:** Gained insights into protecting systems against common web and network attacks.
