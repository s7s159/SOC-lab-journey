# link
https://tryhackme.com/room/socl1alertreporting

# TryHackMe | SOC L1 Alert Reporting
completed on: june 18, 2025

# key concepts learned
- learnt about SOC dashboard and familiarize myself with dashboard content
- when to assign an alert to TP or FP
- how to escalate the alert to L2 or L3 or higher analyst
- how to report an alert and how to comment on it
- use the 5 Ws always (who, what, when, where and most important one is why)
- always communicate with the higher analysts for help

# Questions summary
1. What is the process of passing suspicious alerts to an L2 analyst for review? (Alert Escalation)
2. What is the process of formally describing alert details and findings? (Alert Reporting)
3. According to the SOC dashboard, which user email leaked the sensitive document? (m.boslan@tryhackme.thm)
4. Looking at the new alerts, who is the "sender" of the suspicious, likely phishing email? (support@microsoft.com)
5. Open the phishing alert, read its details, and try to understand the activity.
   Using the Five Ws template, what flag did you receive after writing a good report? (THM{nice_attempt_faking_microsoft_support})
6. Who is your current L2 in the SOC dashboard that you can assign (escalate) the alerts to? (E.Fleming)
7. What flag did you receive after correctly escalating the alert from the previous task to L2?
   Note: If you correctly escalated the alert earlier, just edit the alert and click "Save" again (THM{good_job_escalating_your_first_alert})
8. Now, investigate the second new alert in the queue and provide a detailed alert comment.
   Then, decide if you need to escalate this alert and move on according to the process.
   After you finish your triage, you should receive a flag, which is your answer! (THM{looks_like_webshell_via_old_exchange})
9. Should you first try to contact your manager in case of a critical threat (Yea/Nay)? (nay)
10. Should you immediately contact your L2 if you think you missed the attack (Yea/Nay)? (yea)
