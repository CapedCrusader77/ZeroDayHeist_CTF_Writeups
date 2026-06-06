# 🎭 ZeroDay Heist 2026 — CTF Writeups

> *Think fast. Hack smart. Keep learning.*

Complete writeups for the **ZeroDay Heist Community CTF** — a 6-hour online Capture The Flag challenge organized by [CyberHX](http://cyberhx.com/), hosted on June 6, 2026.

---

## 🏁 Event Details

| Field | Info |
|---|---|
| **Event** | ZeroDay Heist 2026 — Community CTF |
| **Organizer** | CyberHX |
| **Date** | June 6, 2026 |
| **Duration** | 6 Hours (12:00 PM – 6:00 PM) |
| **Mode** | Online · Individual |
| **CTFtime** | [ZerodayHeist](https://ctftime.org/ctf/1595) |
| **Unstop** | [Zero Day Heist 2026](https://unstop.com/hackathons/zero-day-heist-6-hour-ctf-challenge-cyber-hx-1683151) |

> **Note:** This was the Community CTF track — open to all participants who were not shortlisted for the Grand Finale. The Grand Finale (Top 70 teams from Round 1) ran separately with sponsor prizes.

---

## ✍️ Author

**KuantumKnight** · [GitHub](https://github.com/KuantumKnight) · [LinkedIn](https://linkedin.com/in/s4rv3sh-m/)

---

## 📊 Challenge Summary

| # | Challenge | Category | Points | Flag |
|---|---|---|---|---|
| 01 | [Sanity Check](writeups/01-sanity-check.md) | Sanity | 30 | `ZeroDayHeist{welcome_to_the_heist}` |
| 02 | [Double Encode](writeups/02-double-encode.md) | Cryptography | 250 | `0ddayhiest{crypt0_is_fun}` |
| 03 | [One Day...](writeups/03-one-day.md) | Steganography | 150 | `0dayheist{1_dAy_U_will_Be}` |
| 04 | [Greatest Poet of All Time (Veer)](writeups/04-veer.md) | Audio Forensics | 250 | `Zer0d4yh31st{s4vark4R_W4s_th3_gr34t3st}` |
| 05 | [The Hidden Library](writeups/05-hidden-library.md) | Steganography | 650 | `0dayhiest{the_key_is_human_intuition}` |
| 06 | [Security Camera #14](writeups/06-security-camera-14.md) | Forensics | 100 | `0Day-Heist{caught_on_camera}` |
| 07 | [Sierra's Evidence](writeups/07-sierras-evidence.md) | Forensics | 300 | `0Day-Heist{metadata_tells_all}` |
| 08 | [Mint Breach Logs](writeups/08-mint-breach-logs.md) | Forensics | 400 | `0Day-Heist{mint_logs_reveal_truth}` |
| 09 | [Last Radio Signal](writeups/09-last-radio-signal.md) | Memory Forensics | 800 | `0Day-Heist{transmission_intercepted}` |
| 10 | [NeuralRecon](writeups/10-neural-recon.md) | Miscellaneous | 250 | `CyberXoX{st1ll_s1ngl3_st1ll_h4ck1ng}` |
| 11 | [Shadow of the Panther](writeups/11-shadow-of-the-panther.md) | OSINT | 100 | `CTF{panther_trails_never_fade}` |
| 12 | [The Review Heist](writeups/12-review-heist.md) | OSINT | 250 | `Zer0d4yH31st{h0p3_y0u_will_W1n_h31st}` |
| 13 | [What Hashtag? (IxEdge Forge)](writeups/13-ixedge-forge-hashtag.md) | OSINT | 143 | `0day-Heist{#ixedgeforge}` |
| 14 | [Tokyo's Locker](writeups/14-tokyos-locker.md) | Reverse Engineering | 200 | `0Day-Heist{tokyo_opened_the_locker}` |
| 15 | [Professor's Equation](writeups/15-professors-equation.md) | Reverse Engineering | 300 | `0Day-Heist{professor_knows_the_math}` |
| 16 | [Lisbon's Backup Plan](writeups/16-lisbons-backup-plan.md) | Reverse Engineering | 400 | `0Day-Heist{lisbon_found_the_secrret}` |
| 17 | [Escape From The Mint](writeups/17-escape-from-the-mint.md) | Reverse Engineering | 500 | `0Day-Heist{perfect_escape_executed}` |

**Total Points Captured: 4,573**

---

## 🗂️ Category Breakdown

```
Reverse Engineering   4 challenges   1400 pts  ████████████████████
Forensics / Memory    4 challenges   1600 pts  ████████████████████████
Steganography         3 challenges   1050 pts  ████████████████
OSINT                 3 challenges    493 pts  ███████
Cryptography          1 challenge     250 pts  ████
Miscellaneous         1 challenge     250 pts  ████
Sanity                1 challenge      30 pts  █
```

---

## 🛠️ Tools Used

**Forensics & Steganography**
- `exiftool` — EXIF/metadata extraction
- `binwalk` — embedded file detection
- `strings` — printable string extraction
- `zsteg` — PNG LSB steganography
- `Audacity` / spectrogram viewer — audio analysis

**Reverse Engineering**
- `radare2` — disassembly, string extraction (`iz`, `afl`, `pdf`)
- `Ghidra` — decompilation
- `upx` — packer detection and unpacking
- `file`, `xxd` — binary identification
- `strings` — static string extraction

**OSINT**
- `exiftool` — image metadata
- Browser DevTools, Google Search
- GitHub (commit history, robots.txt, git log)
- Google Business / Google Reviews

**Cryptography / Encoding**
- `xxd` — hex encode/decode
- `base64` — Base64 decode
- CyberChef — multi-layer decode chains

**Memory Forensics**
- `strings` — fast dump triage
- `Volatility3` — process listing, OS detection

---

## 📁 Repository Structure

```
ZeroDay-Heist-2026-CTF-Writeups/
├── README.md
└── writeups/
    ├── 01-sanity-check.md
    ├── 02-double-encode.md
    ├── 03-one-day.md
    ├── 04-veer.md
    ├── 05-hidden-library.md
    ├── 06-security-camera-14.md
    ├── 07-sierras-evidence.md
    ├── 08-mint-breach-logs.md
    ├── 09-last-radio-signal.md
    ├── 10-neural-recon.md
    ├── 11-shadow-of-the-panther.md
    ├── 12-review-heist.md
    ├── 13-ixedge-forge-hashtag.md
    ├── 14-tokyos-locker.md
    ├── 15-professors-equation.md
    ├── 16-lisbons-backup-plan.md
    └── 17-escape-from-the-mint.md
```

---

## 💡 Key Takeaways

- **Always check metadata first** before attempting complex steganography techniques.
- **Polyglot files** (WAV+ZIP, PNG+ZIP) are a common CTF trick — use `file` and `binwalk` on everything.
- **Git history never lies** — deleted files in a public repo are recoverable via `git log` and `git show`.
- **robots.txt disallow paths** often lead somewhere interesting in OSINT challenges.
- **XOR 0x2A** appeared in multiple RE challenges — a recurring obfuscation pattern in this CTF.
- **Memory dumps don't always need Volatility** — `strings | grep` is often enough for the first pass.
- **Prompt injection** is the new SQL injection for AI-based challenges.

---

## ⚖️ Disclaimer

These writeups are written for educational purposes. All challenges were solved during the official competition window. Flags are shared post-event as part of the learning community.

---

*ZeroDay Heist 2026 · CyberHX · CTFtime [#1595](https://ctftime.org/ctf/1595)*
