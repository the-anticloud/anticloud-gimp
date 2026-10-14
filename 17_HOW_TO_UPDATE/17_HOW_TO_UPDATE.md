# How to Update — GIMP

**Project:** `GIMP`
**Category:** DESIGN_TOOLS
**Domain:** design tools and creative software
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
GIMP --version
GIMP check-update
```

### Applying Updates
```bash
pip install --upgrade GIMP
```

### Rolling Back
```bash
pip install GIMP==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
