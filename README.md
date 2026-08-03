## Jiacheng Wang

Final-year Digital Security engineering student at [EURECOM](https://www.eurecom.fr/).
I work on reverse engineering, malware analysis, and machine learning applied to
detection and triage.

### Working on now

**[eous](https://github.com/jiacwng/eous)** `WIP`

MinHash code-similarity digests for PE and ELF binaries on x86 and x86-64.
Built with LIEF and Capstone, the digest is computed over mnemonic-root 6-grams, 
with refusal gates for unanalyzable inputs. Evaluated on 2000+ versioned and packed 
binaries and a 472-sample malware corpus.

`Python` `capstone` `LIEF` `NumPy` `PE` `ELF` `x86-64`

**[smudgeC](https://github.com/jiacwng/smudgeC)** `WIP`

C source-to-source obfuscator written in C, with a hand-built lexer and symbol table
and no external dependency. It renames identifiers, strips comments, encodes integer
and string literals, and hides strings at runtime.

`C` `Make`

### Projects

**[meerkat](https://github.com/jiacwng/meerkat)**

ML-assisted SOC alert triage tool that normalizes alerts from Wazuh, 
Suricata and AMiner into one ranked daily queue with MITRE ATT&CK context.
Benchmarked on AIT-ADS simulated companies dataset. 

`Python` `scikit-learn` `Wazuh` `Suricata` `AMiner` `MITRE ATT&CK`

**[ctf-writeups](https://github.com/jiacwng/ctf-writeups)**

25+ walkthroughs of binary exploitation, forensics, cryptography, RE and web, from
[picoCTF](https://learn.cylabacademy.org/users/jiacwng).

`Assembly` `Python`

---

jiacheng.wang@eurecom.fr · Paris, France · Mandarin, French, English

I am looking for a six-month cybersecurity internship outside France from September
2026, and EURECOM provides the internship agreement.
[Resume](https://github.com/jiacwng/jiacwng/blob/main/jiacheng-wang-resume.pdf) ·
[LinkedIn](https://www.linkedin.com/in/jiacheng-wang-a9b55a252/)
