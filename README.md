# Hi there, I'm Ramin Farajpour Cami 👋

**Backend Engineer | Security Researcher | Fuzzing Enthusiast**

Iranian software engineer passionate about making open-source software more secure and reliable through fuzzing, vulnerability research, and code contributions.

Good at breaking things to make them stronger — finding crashes, memory bugs, and security flaws in widely-used software, then writing the patches to fix them.

Python, Rust, Go, and C are my daily tools. Come for the bugs, stay for the fixes.

---

### What I work on:

**[CPython](https://github.com/python/cpython):** Active contributor to CPython's security and robustness through fuzzing and bug fixing.
- Filed **9+ security-critical issues**: use-after-free, NULL dereferences, type confusion, race conditions, and undefined behavior in core modules (`_csv`, `_sqlite3`, `pyexpat`, `array`, `ssl`, `datetime`, lexer).
- Submitted **6+ PRs** with corresponding fixes for the bugs I found.
- Contributions focus on C-level memory safety bugs discovered through targeted fuzzing.

**[Django](https://github.com/django/django):** Contributed **6 PRs** to the main Django repository.
- Fixed OverflowError in SQLite queries, session handling bugs, authentication form improvements, and code quality issues.

**[OpenSSL](https://github.com/openssl/openssl):** Filed **3 issues** including memory leaks and NULL pointer dereferences in crypto subsystems.

**[HarfBuzz](https://github.com/harfbuzz/harfbuzz):** Submitted **2 PRs** fixing a memory leak in `get_glyph_from_name()` and a missing nullptr check in `glyf`.

**[LibVNC](https://github.com/LibVNC):** Fixed buffer overflow issues in both **libvncserver** and **x11vnc**.

**[OWASP DevSecOps Guideline](https://github.com/OWASP/DevSecOpsGuideline):** Contributed **4 PRs** improving container vulnerability scanning and SAST documentation.

**Security bug reports across the ecosystem:**
- **libass** — Integer overflow leading to OOB write in `ass_add_font()`
- **ppp-project** — Overflow in sockaddr struct
- **fluent-bit** — NULL dereference on memory allocation error
- **Flask** — Dev server open redirect via double slash
- **jQuery** — Location.hash XSS vulnerability
- **Rust lang** — `Option::unwrap()` panic issue
- **golang/go** — `os/exec` path handling issue
- **SQLAlchemy** — Thread parallelism connection crash
- **crash-utility**, **google/syzkaller**, **google/sanitizers** — Various kernel tooling issues and fixes

**Linux kernel security research:**
- Contributed **3 PRs** to [linux-kernel-exploitation](https://github.com/xairy/linux-kernel-exploitation): heap corruption exploits, stack clash PoCs, and large memory management exploits.
- Authored [linux-4.8.0-netfilter_icmp](https://github.com/raminfp/linux-4.8.0-netfilter_icmp) — Anatomy of Linux kernel netfilter development.
- Authored [understanding-linux-kernel-vulnerability](https://github.com/raminfp/understanding-linux-kernel-vulnerability).

---

### Principles and goals:

I believe in making the software we all depend on more secure. My approach is simple: fuzz it, break it, fix it, upstream it. Every crash report and patch makes the ecosystem a little safer for everyone. I focus on memory safety bugs because they have the highest real-world impact — use-after-free, NULL dereferences, buffer overflows, and type confusion are the vulnerabilities that attackers exploit.

Open source security is a public good. I contribute because reliable, safe infrastructure benefits everyone.
