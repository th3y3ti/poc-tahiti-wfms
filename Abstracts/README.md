## Abstract Repo
This directory is for storing Threat Hunting abstracts. Threat Hunting abstracts are step by step recipes for conducting Threat Hunts.

### Instructions for creating a new abstract
Copy the abstract template below, make a new abstract in the Abstracts directory, paste the template into the new abstract and fill in the information.

**Note:** UUID's can be generated here (https://www.uuidgenerator.net/version4).

```
---
uuid: 00000000-0000-0000-0000-000000000000
created by: name
created date: xx/xx/20xx
last ran: xx/xx/20xx
classification: attack lifecycle phase
status: initial
priority: 1-5
---

## Hypothesis
Initial or refined hypothesis.

## Priority Explanation
Priority of this hunt.

## MITRE Reference(s)
Reference (links) to attack techniques from MITRE ATT&CK.
- https://attack.mitre.org/techniques/Txxxx/

## Possible Actors
Any actors that use these techniques?

## Actor Campaign(s)
Is there an active campaign in which these techniques are used?

## Analytic Approach
Separate each analytic approach with 3 hash marks and the words Analytic Approach 1, 2, 3, etc

### Analytic Approach 1

## Reference Information:
Links to internal or external information which might help guide this hunt.

## Hunters Notes:
As you iterate through this hunt, add any notes that might be helpful for the next time it is ran. Include a link to the report of your findings.
```
