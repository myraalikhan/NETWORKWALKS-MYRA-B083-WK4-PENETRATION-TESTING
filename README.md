# NETWORKWALKS-MYRA-B083-WK4-PENETRATION-TESTING
Black-box penetration test of a training web app — Week 4, Networkwalks Cybersecurity Internship. SQL injection, PDF cracking, and data-exposure chain. Educational use, authorized target.

# Mediroza Hospital Pentest — Week 4

Networkwalks Cybersecurity Internship. **For educational use only** — authorized training target.

## What I did
Black-box pentest across 4 milestones:
- **SQL injection** login bypass → retrieved 3 encrypted patient PDFs.
- **Cracked** all 3 PDFs (one needed the rockyou wordlist).
- **Metadata clue** (`exiftool`) → exposed `/old/` backup with directory listing enabled.
- Documented 7 findings (3 Critical) in a full report.

> Sensitive data (salaries, shareholders, IDs) is kept in the private report only, with IDs redacted.

## Key takeaways
- Small weaknesses chained together led to full data exposure.
- Parameterised queries would have closed the whole chain.

See `report` and `screenshots` for full evidence.
