# Lab NN — <Title>

| | |
|---|---|
| **Date** | YYYY-MM-DD |
| **Certification** | CompTIA Network+ (N10-009) |
| **Exam objectives** | e.g. 1.4 Given a scenario, configure a subnet and use appropriate IP addressing schemes |
| **Tools** | Cisco Packet Tracer 9.0 · Wireshark · Nmap |
| **Time spent** | ~X h |

## 1. Objective
One or two sentences: what problem this lab solves and why it matters in a real network.

## 2. Environment & topology
![Topology](topology.png)

| Device | Interface | IP address / mask | Gateway | VLAN |
|---|---|---|---|---|
| PC0 | Fa0 | 192.168.1.10/24 | 192.168.1.1 | 10 |

## 3. Procedure
Numbered steps. Show the commands you ran, not just describe them.

```
Switch(config)# vlan 10
Switch(config-vlan)# name STUDENTS
```

## 4. Verification
How you proved it worked: command output, ping results, a Wireshark filter and what it showed.
Screenshot or output, with one line explaining what to look at.

## 5. Troubleshooting log
What broke and how you fixed it, using the CompTIA methodology:

| Step | Notes |
|---|---|
| Identify the problem | Symptom you saw |
| Theory of probable cause | What you suspected |
| Test the theory | What you checked, and the result |
| Plan & implement | The fix |
| Verify | How you confirmed it |
| Document | Lesson learned |

## 6. Security considerations
What could an attacker abuse here, and what hardening would you apply in production?

## 7. Key takeaways
- 3 bullets max, in your own words.

## Files
- `lab.pkt` — Packet Tracer file
- `topology.png` — diagram

> Sanitized: no real public IPs, MAC addresses, SSIDs, credentials, or raw captures of my home network.
