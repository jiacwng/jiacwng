## Jiacheng Wang

Final-year Digital Security engineering student at [EURECOM](https://www.eurecom.fr/).
I work on reverse engineering, malware analysis, and machine learning applied to
detection and triage. When I want to understand a technique, I build the tool for it
myself.

### Working on now

**[eous](https://github.com/jiacwng/eous)** `WIP`

Code-similarity digests for PE and ELF binaries on x86 and x86-64. Two binaries
built from similar code get digests that agree in many places. Version 0.0.1, in
evaluation on a corpus of around 1600 packed and unpacked binaries.

`Python` `capstone` `LIEF` `NumPy` `PE` `ELF` `x86-64`

**[smudgeC](https://github.com/jiacwng/smudgeC)** `WIP`

C source-to-source obfuscator written in C, with a hand-built lexer and symbol table
and no external dependency. It renames identifiers, strips comments, and encodes
integer and string literals. V1 is tagged.

`C` `Make`

### Projects

**[meerkat](https://github.com/jiacwng/meerkat)**

SOC alert triage. Wazuh, Suricata and AMiner alerts become one ranked daily queue
with MITRE ATT&CK context. Ten cases a day reach **58 of 60** attack steps on the
AIT-ADS benchmark, against 19 for native detector severity.
[Technical report](https://github.com/jiacwng/meerkat/blob/main/docs/report/meerkat.pdf).

`Python` `scikit-learn` `Wazuh` `Suricata` `AMiner` `MITRE ATT&CK`

**[mnemocrypt-enhanced](https://github.com/jiacwng/mnemocrypt-enhanced)**

Cryptographic function detection. I fixed an IDA Pro plugin that misread compression
code as cryptography. False positives on held-out goodware went from **48 to 9**,
precision from **0.60 to 0.86**.

`Python` `IDA Pro` `x86-64` `scikit-learn`

**[ctf-writeups](https://github.com/jiacwng/ctf-writeups)**

25+ walkthroughs of binary exploitation, forensics, cryptography and web, from
[picoCTF](https://learn.cylabacademy.org/users/jiacwng),
[Root-Me](https://www.root-me.org/Jiach-841817?inc=info&lang=en) and TryHackMe.

`Assembly` `Python`

---

jiacheng.wang@eurecom.fr · Paris, France · Mandarin, French, English (TOEIC 930)

I am looking for a six-month cybersecurity internship outside France from September
2026, and EURECOM provides the internship agreement.
[Resume](https://github.com/jiacwng/jiacwng/blob/main/jiacheng-wang-resume.pdf) ·
[LinkedIn](https://www.linkedin.com/in/jiacheng-wang-a9b55a252/)
