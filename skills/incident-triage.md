# Skill: incident triage (open-source Kortix)

How this company does error triage on the open-source Kortix platform:
1. Collect the day's errors and group by signature.
2. Reproduce the highest-frequency one on an isolated session.
3. Patch, add a regression test, run the suite.
4. Open a change request with the diff and the evidence.
