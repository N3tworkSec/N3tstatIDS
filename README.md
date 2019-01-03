# N3tstat IDS
N3tstat IDS is a lightweight Endpoint Detection &amp; Response (EDR) framework specifically designed for real-time Advanced Persistent Threat (APT) detection. N3tstat IDS provides APT detection capabilities not present in legacy Intrusion Detection System (IDS) solutions and offers the visibility required by cyber security analysts and network defenders to perform proactive threat hunting. N3tstat IDS utilizes beacon detection and analysis as its primary detection mechanism. High fidelity, context-based beacon detection capabilities start at the endpoint through the continuous collection of process and associated network session information that is analyzed in order to identify anomalous endpoint behavior. With N3tstat IDS you can easily identify processes like powershell.exe running under SYSTEM and beaconing out to a foreign registered IP address. Determining what processes and users are accessing a remote system over time can lead to the initial detection of malware and associated IOAs such as code execution, privilege escalation, establishing persistence, process migration, lateral movement, and command & control (C&C).  

N3tstat IDS is comprised of 3 primary components: 1) an agent running on endpoint systems, 2) a server for collecting and recording agent results, and 3) a GUI analyzer for presenting a holistic view of endpoint activities. Endpoint system beacon information (which includes network sessions and associated Registry Internet Registry and DNS information, processes, and users) and relevant event log entries associated with APT Indicators of Attack (IoAs) such as lateral movement, establishing persistence, and detection evasion are continuously collected and analyzed at the agent and results are securely transmitted to the server. Results consist of flagged network sessions having characteristics resembling those of malware beacons employed by an APT and specific event log entries associated with APT IoAs.

Easily export all collected endpoint data to your SIEM solution of choice for further correlation and analysis with data collected from other security products. 

At this time, only Microsoft Windows platforms are supported.


# Resources
  * [N3tstat IDS Overview](https://drive.google.com/open?id=1KHjN51AvoFJiQ_Xz7guSLbs9BgeaZRTc)
  * [N3tstat IDS Introduction Demo](https://www.youtube.com/watch?v=14pTenY9ayQ)
  * [N3tstat IDS Demo - Detection of ACT PowerShell Tools](https://youtu.be/TKyIADfkEME)
  * [N3tstat IDS IoAs](https://drive.google.com/open?id=16__4C5h8PRBnNvWNxgCbh7ATfi5Qu5C_)
  * [N3tstat IDS Download](../../releases/tag/v0.93.7)
