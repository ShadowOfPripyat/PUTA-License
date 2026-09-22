
# PUTA License

> **Protected Use, Traceability, and Attribution License**

The **PUTA License** is a custom source-available copyleft license.

It is designed for software whose author wants derivatives to remain under the same license, keep their source available, preserve attribution, and follow specific rules for commercial use.

The full legal text is available in [`LICENSE`](./LICENSE).

> This README is only a plain-language summary. If anything here conflicts with the license text, the `LICENSE` file controls.

---

## What it allows

| Action | Allowed? |
|---|:---:|
| Use the software | ✅ |
| Study the source | ✅ |
| Modify it | ✅ |
| Fork it | ✅ |
| Redistribute it | ✅ |
| Distribute compiled builds | ✅ |
| Sell or monetize derivatives | ✅ |
| Make derivatives closed-source | ❌ |
| Remove attribution | ❌ |
| Relicense derivatives | ❌ |

---

## Core rules

### Same license

Any distributed derivative must use the **exact same version of the PUTA License**.

A fork cannot be relicensed under MIT, GPL, Apache, or another license.

---

### Source must stay available

If you distribute a modified binary, APK, executable, or other compiled version, you must also make the corresponding source code publicly available.

That source must be available free of charge.

---

### Attribution is mandatory

Distributed derivatives must preserve:

- the original creator's name;
- the original project name;
- the copyright notice;
- a link to the original repository;
- the PUTA License itself.

Modified versions must also clearly state that they are modified.

---

## Commercial use

Commercial use is allowed.

A commercial distributor must follow one of the commercial options defined in the license.

| Option | Requirement |
|---|---|
| **A — Revenue share** | Pay the Original Creator 50% of defined Commercial Earnings |
| **B — Commercial attribution** | Prominently credit the Original Creator and original repository |

The full license defines how Commercial Earnings are calculated and where commercial attribution must appear.

---

## Copyleft

PUTA is a **same-license copyleft** license.

The rule is simple:

```text
PUTA project
    ↓
fork
    ↓
modified fork
    ↓
fork of that fork
    ↓
derivative application

All remain under the same PUTA License version.
```

---

## Third-party code

Third-party components keep their own licenses.

They may be used only when their license can be followed without forcing PUTA-covered code to change licenses.

| License type | General compatibility |
|---|:---:|
| MIT | ✅ |
| BSD | ✅ |
| Apache-2.0 | ✅ |
| LGPL | ⚠️ Usually possible |
| GPL with a linking exception | ⚠️ Depends on the exception |
| Ordinary GPL code requiring the whole work to become GPL | ❌ |

If two licenses cannot legally be satisfied at the same time, that combination must not be distributed.

---

## GPL note

PUTA derivatives must remain under PUTA.

Because of that, ordinary GPL code cannot be incorporated when doing so would require the whole derivative to be distributed under the GPL.

LGPL libraries, separate GPL programs, or GPL code with an applicable linking exception may be usable depending on the exact terms.

---

## No warranty

Software covered by PUTA is provided **as is**, without warranty.

The license also limits the Original Creator's liability to the maximum extent permitted by applicable law.

---

## Is PUTA open source?

PUTA is best described as a **source-available copyleft license**.

It is not an OSI-approved open-source license because it contains custom commercial-use conditions.

---

## Using the license

Add the full license text to your repository as:

```text
LICENSE
```

Then reference it in your project README, for example:

```markdown
This project is licensed under the PUTA License 1.0.
See [LICENSE](./LICENSE) for the full terms.
```

---

## License text

Read the complete legal terms in [`LICENSE`](./LICENSE).
