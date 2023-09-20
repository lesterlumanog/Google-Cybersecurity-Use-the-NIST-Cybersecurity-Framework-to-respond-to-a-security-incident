<h1>Google Cybersecurity Internal Audit Lab</h1>

<h2>Overview</h2>
In this lab, we'll be applying the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF) to respond to a security incident. The NIST CSF provides organizations with a way to manage cybersecurity risks, implement management strategies, and apply knowledge from previous mistakes. The core functions of the NIST CSF are to: identify, protect, detect, respond, and recover. We'll start with defining what each of those functions are, some notes about them, and then apply those functions to a fictional scenario in the form of an incident report.
</br>
</br>
</br>

NIST CSF core functions:
</br>

● Identify: Manage security risks through regular audits of internal networks,
systems, devices, and access privileges to identify potential gaps in security.

Identify what organizational systems, processes, assets, data, people and capabilities need to be secured to stop further damage.
</br>

● Protect: Develop a strategy to protect internal assets through the implementation
of policies, procedures, training and tools that help mitigate cybersecurity threats.

These are the safeguards needed to be implemented in order to protect the identified assets and ensure delivery of services.
</br>

● Detect: Scan for potential security incidents and improve monitoring capabilities to
increase the speed and efficiency of detections.

These are the tools needed for detecting threats and attacks.
</br>

● Respond: Ensure that the proper procedures are used to contain, neutralize and
analyze security incidents and implement improvements to the security process.

This is the needed execution of plans to respond to threats and attacks, notifications/communication with the organization, and after action steps including where the response procedures need to improve.
</br>

● Recover: Return affected systems back to normal operation and restore systems
data and assets that have been affected by an incident.

This is the plan for recovering and restoring affected systems and/or data. Improvements and communications/notifications procedures are also considered.
</br>

<h2>Scenario</h2>

- You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
- During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services.    
- The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 


<h2>Scope</h2>

<p align="center">
<img src="https://i.ibb.co/vm0KQs1/Internal-Audit-Scope.jpg" height="80%" width="80%" alt="Generic Description"/> 
</p>

<h2>Goals</h2>

<p align="center">
<img src="https://i.ibb.co/wMYVXVr/Internal-Audit-Goals.jpg" height="80%" width="80%" alt="Goals"/>
</p>

<h2>Risk Assessment Report</h2>

<p align="center">
<img src="https://i.ibb.co/0t2Wstc/Internal-Audit-Risk-Assessment.jpg" height="80%" width="80%" alt="Internal-Audit-Risk-Assessment">
</br>
<img src="https://i.ibb.co/SdSnqD4/Internal-Audit-Risk-Assessment-pg2.jpg" height="80%" width="80%" alt="Internal-Audit-Risk-Assessment-pg2">
</p>

<h2>Controls And Compliance Checklist</h2>

<p align="center">

<img src="https://i.ibb.co/gv3Kwc2/Internal-Audit-Controls-And-Compliance-Checklist-pg1.jpg" height="80%" width="80%" alt="Internal-Controls-And-Compliance-Checklist-Pg1">

</br>

<img src="https://i.ibb.co/cFYZrBz/Internal-Audit-Controls-And-Compliance-Checklist-pg2.jpg" height="80%" width="80%" alt="Internal-Controls-And-Compliance-Checklist-Pg2">

</p>

<h2>Additional Considerations and Recommendations</h2>

</br>

- All Botium Toys employees have access to internally stored data including access to cardholder data and customers’ PII/SPII. Not all employees need access to this information. Access to this information should be limited to employees who are authorized to. And then the time allotted to access this information should be limited. Establishing and implementing access controls pertaining to the principle of least privilege and separation of duties will remedy this.
- No disaster recovery plans are currently in place and Botium Toys does not have any backups of critical data. It’s important to have backups of data to restore and recover systems to minimize the negative impact on business continuity should an attack or other disasters occur. 
- Increase minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
- Separation of duties have not been established and implemented. To minimize negative impacts, no one individual should have control of critical processes (example: individual responsible for signing/authorizing paychecks should not also be the one creating them),
- No backups. See comment concerning disaster recovery plans.
- Establish a regular schedule for tasks and clarify intervention methods concerning the legacy systems in use. 
- Implementing encryption concerning customers' credit card information will help avoid protected data leaks and compliance violations. 
- Establish a password management system exists that enforces the minimum password policy’s minimum requirement.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
