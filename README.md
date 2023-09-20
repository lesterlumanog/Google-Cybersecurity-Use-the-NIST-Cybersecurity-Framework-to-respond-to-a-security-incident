<h1>Google Cybersecurity lab: Applying the NIST CSF to a security incident</h1>

<h2>Overview</h2>
In this lab, we'll be applying the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF) to respond to a security incident. The NIST CSF provides organizations with a way to manage cybersecurity risks, implement management strategies, and apply knowledge from previous mistakes. The core functions of the NIST CSF are to: identify, protect, detect, respond, and recover. We'll start with going over a fictional scenario, defining what each of functions of the NIST CSF are with some notes about them, and then apply those functions the scenario in the form of an incident report.
</br>
</br>
<h2>Scenario</h2>

- You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
- During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services.    
- The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 
</br>

<h2>NIST CSF core functions:</h2>
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


<h2><i>The following incident report analysis was created using a template from the Google Cybersecurity Certificate course material.</i></h2>

<h2>Incident Report Analysis</h2>

<p align="center">
<img src="https://i.ibb.co/zx10kz6/Incident-Report-Analysis-pt-1.jpg" alt="Incident-Report-Analysis-pt-1">
</p>

<p align="center">
<img src="https://i.ibb.co/Nnq4VcM/Incident-Report-Analysis-pt-2.jpg" alt="Incident-Report-Analysis-pt-2">
</p>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
