# Incident-Response Life Cycle Breakdown 

<h3> Incident Response Process </h3>
<p align="center">
Lifecycle: <br/>
<img src="https://github.com/gitahn11/Splunk-Project/blob/main/Uploads/Picture2.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
  </p>
<ol> 
  <li> Preparation: A strong plan must be in place to support your team. To successfully address security events, these features should be included in an incident response plan: </li>
  <ul>
    <li> Develop and Document IR Policies: Establish policies, procedures, and agreements for incident response management. </li>
    <li> Incorporate Threat Intelligence Feeds: Perform ongoing collection, analysis, and synchronization of your threat intelligence feeds. </li>
    <li> Assess Your Threat Detection Capability: Assess your current threat detection capability and update risk assessment and improvement programs. </li>
  </ul> 
 
  <b> <li> Detection & Analysis: The focus of this phase is to monitor security events in order to detect, alert, and report on potential security incidents. Resources should be utilized to collect data from tools and systems for further analysis and to identify indicators of compromise </li>
  <ul>
    <li> Monitor, Detect. and Alert: Monitor security events in your environment using firewalls, intrusion prevention systems, and data loss prevention. Detect potential security incidents by correlating alerts within a SIEM solution. Analysts create an incident ticket, document initial findings, and assign an initial incident classification. </li>
    <li> Endpoint Analysis: Determine what tracks may have been left behind by the threat actor. Gather the artifacts needed to build a timeline of activities. </li>
    <li> Binary Analysis: Investigate malicious binaries or tools leveraged by the attacker and document the functionalities of those programs. </li>
    <li> Enterprise Hunting: Analyze existing systems and event log technologies to determine the scope of compromise. </li>
  </ul>
      </b>
  
  <b> <li> Containment and Neutralization: This is one of the most critical stages of incident response. The strategy for containment and neutralization is based on the intelligence and indicators of compromise gathered during the analysis phase. After the system is restored and security is verified, normal operations can resume.
•	Coordinated Shutdown: Once you have identified all systems within the environment that have been compromised by a threat actor, perform a coordinated shutdown of these devices. </li>
  <ul>
    <li> Wipe and Rebuild: Wipe the infected devices and rebuild the operating system from the ground up. Change passwords of all compromised accounts. </li>
    <li> Coordinated Shutdown: Once you have identified all systems within the environment that have been compromised by a threat actor, perform a coordinated shutdown of these devices.  </li>
  </ul>
  </b>
  
  <b> <li> Post-Incident Activity: There is more work to be done after the incident is resolved. Be sure to properly document any information that can be used to prevent similar occurrences from happening again in the future. </li>
  </b>
</ol> 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
