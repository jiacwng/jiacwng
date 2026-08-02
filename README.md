## Jiacheng Wang

Final-year Digital Security engineering student at [EURECOM](https://www.eurecom.fr/).
I work on reverse engineering, malware analysis, and machine learning applied to
detection and triage. When I want to understand a technique, I build the tool for it
myself.

### Working on now

**[eous](https://github.com/jiacwng/eous)** `WIP`

Code-similarity digests for PE and ELF binaries on x86 and x86-64. A digest
summarises the instruction sequences a program contains, so two binaries built from
similar code produce digests that agree in many places. The tool normalises
instruction mnemonics, takes 6-grams of them, and packs those into a 512-bit sketch.
`eous hash` prints one digest per file, `eous compare` scores two files or two
digests against each other and reports similarity and containment. Version 0.0.1.
It has no evaluation on a real corpus yet.

`Python` `capstone` `LIEF` `NumPy` `PE` `ELF` `x86-64`

**[smudgeC](https://github.com/jiacwng/smudgeC)** `WIP`

C source-to-source obfuscator written in C, with a hand-built lexer and symbol table
and no external dependency. It renames identifiers, strips comments, and encodes
integer and string literals, while keeping keywords, standard-library names and
preprocessor lines intact. The test pipeline compiles the original file and the
obfuscated file, runs both, and compares their output. V1 is tagged. The current
branch reorganises the code before the next set of passes. The scanner is lexical,
so it handles one file at a time and does not parse the full C grammar.

`C` `Make`

### Projects

**[meerkat](https://github.com/jiacwng/meerkat)**

SOC alert triage. Normalises Wazuh, Suricata and AMiner alerts into one ranked daily
queue with MITRE ATT&CK context. The queue covers as much distinct attack activity
as a fixed daily budget allows. Ten cases a day reach **58 of 60** attack steps on
the AIT-ADS benchmark, against 19 for native detector severity.
[Technical report](https://github.com/jiacwng/meerkat/blob/main/docs/report/meerkat.pdf).

`Python` `scikit-learn` `Wazuh` `Suricata` `AMiner` `MITRE ATT&CK`

**[mnemocrypt-enhanced](https://github.com/jiacwng/mnemocrypt-enhanced)**

Cryptographic function detection. I fixed an IDA Pro plugin that misread compression
code as cryptography, by rebalancing its training data and adding lane-aware SIMD
instruction counting. False positives on held-out goodware went from **48 to 9**,
precision from **0.60 to 0.86**.

`Python` `IDA Pro` `x86-64` `scikit-learn`

**[ctf-writeups](https://github.com/jiacwng/ctf-writeups)**

25+ walkthroughs of binary exploitation, forensics, cryptography and web challenges,
from [picoCTF](https://learn.cylabacademy.org/users/jiacwng),
[Root-Me](https://www.root-me.org/Jiach-841817?inc=info&lang=en) and TryHackMe.

`Assembly` `Python`

---

jiacheng.wang@eurecom.fr · Paris, France · Mandarin, French, English (TOEIC 930)

I am looking for a six-month cybersecurity internship outside France from September
2026, and EURECOM provides the convention de stage.
[Resume](https://github.com/jiacwng/jiacwng/blob/main/jiacheng-wang-resume.pdf) ·
[LinkedIn](https://www.linkedin.com/in/jiacheng-wang-a9b55a252/)
