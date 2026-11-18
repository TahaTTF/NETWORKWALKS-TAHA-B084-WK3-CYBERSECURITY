# NetworkWalks — Week 3 Cybersecurity Internship

**Intern:** Taha Chebil  
**Batch:** B084  
**Program:** Cybersecurity & Ethical Hacking  
**Week:** 3 — Password Security & Authorized Password Recovery Labs  
**Status:** Both mandatory modules completed (W3-PM1 and W3-PM2).


## Completed modules

| Module | Focus | Outcome | Documentation |
|---|---|---|---|
| W3-PM1 | John the Ripper (JTR) and Johnny GUI | Training PDF password recovered; completion evidence captured | [PM1 README](W3-PM1/README.md) |
| W3-PM2 | NetworkWalks Hash Calculator and Password Cracker | Dictionary-based recovery successful; completion evidence captured | [PM2 README](W3-PM2/README.md) |

## Skills practiced

- Understanding PDF password protection and password-verification hashes
- Comparing a command-line password auditing tool with its graphical interface
- Using the Johnny GUI to load a PDF hash and review recovery results
- Extracting a `$pdf$`-formatted hash with the NetworkWalks Hash Calculator
- Running a dictionary-based candidate search with the NetworkWalks Password Cracker


## Repository structure

```text
NETWORKWALKS-TAHA-B084-WK3-CYBERSECURITY/
├── README.md
├── W3-PM1/
│   ├── README.md
│   └── images/
│       ├── pm1_flag_1.png
│       ├── pm1_flag_2.png
│       └── pm1_johnny_result.png
└── W3-PM2/
    ├── README.md
    └── images/
        ├── pm2_flag.png
        ├── pm2_dictionary_progress.png
        └── pm2_password_recovered.png
```

## Main outcomes

**PM1:** Recovered the training PDF password using John the Ripper / Johnny, reviewed the result in Johnny, and opened the protected training document. Captured completion evidence.

**PM2:** Extracted the PDF hash using NetworkWalks' browser-based Hash Calculator and recovered the training password using a dictionary-based candidate search. The screenshot shows a successful match after 3,456 of 3,556 candidate attempts (97% progress).

## Lessons learned

1. Password strength matters: a password included in a known wordlist can be discovered by a dictionary search.
2. A PDF password-verification hash is not the same as the original plaintext password.
3. A successful dictionary match depends on the candidate list and does not guarantee that every password can be recovered.

---
*Prepared by Taha Chebil — NetworkWalks Internship, Batch B084 (November 2026).*
