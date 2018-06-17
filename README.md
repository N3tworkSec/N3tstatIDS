# N3tstat IDS
N3tstat IDS is a lightweight Endpoint Detection &amp; Response (EDR) framework designed to better detect the presence of malware employed by an Advanced Cyber Threat (ACT). It provides ACT detection capabilities not present in legacy Intrusion Detection System (IDS) solutions and offers the visibility required by cyber security analysts and network defenders to perform proactive threat hunting.

N3tstat IDS is comprised of 3 primary components: 1) an agent running on endpoint systems, 2) a server for collecting and recording agent results, and 3) a GUI analyzer for presenting a holistic view of endpoint activities. Endpoint system information (for network sessions and associated Registry Internet Registry and DNS information, processes, and users) is continuously collected and analyzed at the agent and results are securely transmitted to the server. Results consist of flagged network sessions having characteristics resembling those of beacons employed by an ACT.

Determining what processes and users (i.e. process owners, logged in users) are accessing a remote system over time can lead to the detection of ACT tools (malware) and associated Indicators of Attack (IOAs) such as code execution, privilege escalation, establishing persistence, process migration, lateral movement, and command & control (C&C).

At this time, only Microsoft Windows platforms are supported.


# Resources
  * [N3tstat IDS Overview](https://drive.google.com/open?id=1nLFFCl35N7tzK0wRYXXNDYUFaqzsgQkI)
  * [N3tstat IDS Introduction Demo](https://www.youtube.com/watch?v=14pTenY9ayQ)
  * [N3tstat IDS Download](../../releases/tag/v0.93.1)
