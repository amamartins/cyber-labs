Wazuh SIEM Setup Lab

Learning to install and configure a Wazuh SIEM stack on Ubuntu

What I did
Installed Ubuntu 22.04 on VirtualBox (8GB RAM, 4 CPU)
Installed Wazuh Manager, Indexer, and Dashboard
Troubleshot VM
Learned to configure agents (not fully implemented through VM constraints)

Installation
<img width="428" height="191" alt="ubuntu wazuh start" src="https://github.com/user-attachments/assets/7fd866c8-39ef-4f67-8b48-3433a72f624e" />
<img width="395" height="88" alt="ubuntu wazuh ignor" src="https://github.com/user-attachments/assets/32671705-c233-43bd-8719-d093c360036f" />

Ensuring Wazuh Manager and Dashboard are active
<img width="597" height="298" alt="wazuhmanager" src="https://github.com/user-attachments/assets/a42605b9-2b13-4ef8-bfed-a646fb69769c" />
<img width="596" height="185" alt="wazuhdashboard" src="https://github.com/user-attachments/assets/99ce3267-b8c3-4612-807e-9fb2c3f70838" />

Lab - typed random passwords to generate authentication failure logs
<img width="605" height="340" alt="wazuh main dashboard" src="https://github.com/user-attachments/assets/f276f3d6-15cc-4457-9c87-714fb9e93a70" />

Lessons Learned
While enterprise SIEM stacks can run locally, they may require high resources
Agent-manager communication is critical to view events
Proper VM configuration will prevent errors

Next steps
Add Wazuh agents on endpoints
Generate test alerts and analyze logs
