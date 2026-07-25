## Jiacheng Wang

Final-year Digital Security engineering student at [EURECOM](https://www.eurecom.fr/).
Reverse engineering, malware analysis, and applying machine learning to detection
and triage.

> Seeking a six-month cybersecurity internship outside France from September 2026.
> EURECOM provides the *convention de stage*.

### Projects

**[meerkat](https://github.com/jiacwng/meerkat)** — SOC alert triage

Normalizes Wazuh, Suricata and AMiner into one ranked daily queue with MITRE
ATT&CK context. The queue is built to cover as much distinct attack activity as a
fixed daily budget allows. Ten cases a day reach **58 of 60** attack steps on the
AIT-ADS benchmark, against 19 for native detector severity.
[Technical report](https://github.com/jiacwng/meerkat/blob/main/docs/report/meerkat.pdf).

`Python` `scikit-learn` `Wazuh` `Suricata` `AMiner` `MITRE ATT&CK`

**[malfamily](https://github.com/jiacwng/malfamily)** — malware classification

Classifies malware into six behavioural families using assembly instruction
mnemonics as the sole feature source, across PE, ELF and Mach-O. **77.9%**
accuracy against a 25.3% baseline, 0.77 macro-F1 over 472 samples.

`Python` `Ghidra` `scikit-learn` `x86`

**[mnemocrypt-enhanced](https://github.com/jiacwng/mnemocrypt-enhanced)** — cryptographic function detection

Improved an IDA Pro plugin that misread compression code as cryptography.
Rebalanced its training data and added lane-aware SIMD instruction counting.
False positives on held-out goodware **48 → 9**, precision **0.60 → 0.86**.

`Python` `IDA Pro` `x86-64` `scikit-learn`

**[smudgeC](https://github.com/jiacwng/smudgeC)** — C source-to-source obfuscator

Written in pure C with a hand-built lexer and symbol table, no parser generator
or external dependency.

`C`

**[ctf-writeups](https://github.com/jiacwng/ctf-writeups)** — 25+ walkthroughs

Binary exploitation, forensics, cryptography and web, across picoCTF, Root-Me and
TryHackMe.

<p align="left">
  <a href="https://learn.cylabacademy.org/users/jiacwng" target="_blank">
    <img src="https://img.shields.io/badge/picoCTF-jiacwng-red?style=for-the-badge&logo=fortinet&logoColor=white" alt="picoCTF profile" height="28" />
  </a>
  <a href="https://www.root-me.org/Jiach-841817?inc=info&lang=en" target="_blank">
    <img src="https://img.shields.io/badge/Root--Me-Jiach-black?style=for-the-badge&logo=rootme&logoColor=white" alt="Root-Me profile" height="28" />
  </a>
</p>

### Toolkit

| | |
|---|---|
| **Reverse engineering** | Ghidra, IDA Pro, gdb, x86-64 / ARM / RISC-V assembly |
| **Defensive security** | Suricata, Wazuh, AMiner, MITRE ATT&CK, Wireshark, nmap |
| **ML and data** | scikit-learn, pandas, NumPy, matplotlib |
| **Languages** | C, Python, OCaml, Java, SQL |

jiacheng.wang@eurecom.fr · Paris, France · Mandarin, French, English (TOEIC 930)
