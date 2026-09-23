### Hi, I'm Zain

I build detection and integrity tools for cloud security, in Python.

### Projects

**[trailsight](https://github.com/zainsplace/trailsight)**: self-hostable threat detection for AWS CloudTrail.
Six deterministic rules cover leaked access keys, privilege escalation, reconnaissance bursts,
disabled CloudTrail or GuardDuty, root account use and console logins without MFA.
It has a command line interface, a Flask dashboard and optional plain-English explanations
from a local language model. The model only explains findings, it never decides them.
55 tests run in CI.

**[file-integrity-monitor](https://github.com/zainsplace/file-integrity-monitor)**: builds an
HMAC-signed baseline of a set of files and reports exactly what changed: content, permissions,
owner, mtime or inode. Standard library only. Comes with a written
[threat model](https://github.com/zainsplace/file-integrity-monitor/blob/main/THREATMODEL.md)
covering the attacks it defends against and the ones it doesn't.

**[password-strength-analyser](https://github.com/zainsplace/password-strength-analyser)**:
estimates how many guesses a password needs by matching the patterns cracking tools try first,
such as common passwords, look-alike substitutions, keyboard walks and sequences. The README
measures why my first, entropy-based version got this wrong.

**[packet-analyser](https://github.com/zainsplace/packet-analyser)**: live packet capture and
protocol summaries with Scapy.

### Skills

- Python, including tooling, command line interfaces and test suites with pytest
- AWS CloudTrail and detection engineering
- Applied cryptography: HMAC signing and hashing in the file integrity monitor
- Threat modelling
- Network traffic analysis with Scapy
- GitHub Actions CI

### Security research

I've had valid vulnerability reports accepted through bug bounty programmes.

### Contact

I'm a student, looking for opportunities in cloud security.

[acmanzain@gmail.com](mailto:acmanzain@gmail.com) · [LinkedIn](https://linkedin.com/in/zain-acman/)
