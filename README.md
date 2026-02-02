I set up Wazuh on my network to monitor my devices' health and take actions to mitigate the risk of being compromised.
The VirusTotal API has been integrated to monitor file integrity and legitimacy.
Discord and Slack webhooks were used to be notified of any suspicious activity across the network, which was fine-tuned as too many false positives were coming through.
Devices were patched as Wazuh notified me of vulnerabilities present on the devices, with CVE numbers. Some softwares were deleted to lower the attack surface, as those were not needed, and others were updated.
