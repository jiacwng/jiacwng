## Jiacheng Wang

Hello there! I'm Jiacheng, a final-year Digital Security engineering student at
[EURECOM](https://www.eurecom.fr/). I build security tools and measure them honestly:
reverse engineering, malware analysis, machine learning for detection, and LLM agents.
Open to collaborations, always happy to connect.

### Projects

**[deskclerk](https://github.com/jiacwng/deskclerk)**

An internal AI agent that works on a company's MCP servers with each employee's own
accounts. Company sign-in with OpenID Connect, per-employee OAuth tokens, MCP tool pinning,
spending limits, an audit log, and a prompt injection screen on every tool result. Tested on
Linear's hosted MCP server and benchmarked on WorkBench and AgentDojo.

`Python` `FastAPI` `LangChain` `MCP` `OpenID Connect` `Docker`

**[eous](https://github.com/jiacwng/eous)**

A fuzzy hashing tool for PE and ELF binaries, on PyPI. It hashes disassembled machine
instructions instead of raw bytes, so it still recognises a program rebuilt with different
compiler settings: AUC 0.726 against 0.570 for tlsh on Debug and Release builds. Packed and
.NET files are refused with a reason instead of a false match.

`Python` `Rust` `LIEF` `iced-x86` `MinHash` `PE` `ELF`

**[meerkat](https://github.com/jiacwng/meerkat)**

SOC alert triage. Wazuh, Suricata and AMiner alerts become one ranked daily review queue
with MITRE ATT&CK context. On networks unseen in training, it surfaces 57 of 60 attack
steps against 33 when sorted by the detectors' own severity.

`Python` `scikit-learn` `Wazuh` `Suricata` `MITRE ATT&CK`

**[mnemocrypt-enhanced](https://github.com/jiacwng/mnemocrypt-enhanced)**

Cryptographic function detection in x86 and x86-64 binaries, as an IDA Pro plugin. A
semester project extending published research: false positives on held-out goodware went
from 48 to 9, precision from 0.60 to 0.86.

`Python` `IDA Pro` `scikit-learn` `x86-64`

**[ctf-writeups](https://github.com/jiacwng/ctf-writeups)**

25 picoCTF writeups across binary exploitation, forensics, reverse engineering, web and
cryptography.

`Assembly` `Python`

---

jiacheng.wang@eurecom.fr · Paris, France · Mandarin, French, English

Looking for a six-month end-of-studies internship outside France in security or AI
engineering, available now. EURECOM provides the internship agreement.
[Resume](https://github.com/jiacwng/jiacwng/blob/main/jiacheng-wang-resume.pdf) ·
[LinkedIn](https://www.linkedin.com/in/jiacheng-wang-a9b55a252/)
