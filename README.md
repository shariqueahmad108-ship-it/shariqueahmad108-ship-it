# Sharique Ahmad

Security-focused developer and student, building a track record of real open-source
contributions ahead of **Google Summer of Code 2027**.

I work mostly on security tooling: Kubernetes RBAC scanning, cloud posture (CSPM), threat
intel and IaC scanners. Before I touch a codebase I trace the actual code path, and every
fix ships with tests that fail without it.

## Security tools I built

- **[jwtpeek](https://github.com/shariqueahmad108-ship-it/jwtpeek)**: decode and
  security-inspect JSON Web Tokens without verifying them. Flags `alg=none`, `jku`/`jwk`
  key injection, risky `kid`, missing `exp`, and recognises JWE, nested and `b64:false` tokens.
  Works as a CI gate.
- **[secheaders](https://github.com/shariqueahmad108-ship-it/secheaders)**: offline HTTP
  security-header auditor for reviews and pentests. Pipe in `curl -sI` and get
  severity-ranked findings (CSP, HSTS, CORS, cookie prefixes, cross-origin isolation…),
  with no network requests.

## Open-source contributions (merged)

- **[kaaval](https://github.com/kaaval/kaaval)** (Kubernetes RBAC/CVE scanner): 8 commits
  on `main`. A new `ineffective_cluster_scope_grant` detection rule, `api_groups` scoping
  fixes that were silently disabling CRITICAL findings, tenant-aware risk scoring for
  combo-scan, a 413 body-size guard, and a runnable SARIF CI example.
- **[OWASP/openshield](https://github.com/OWASP/openshield)** (Azure CSPM): 3 detection rules.
  Trusted Launch (AZ-CMP-005), management ports without JIT access (AZ-CMP-007), and
  storage accounts without a private endpoint (AZ-STOR-010).
- **[IntelOwl](https://github.com/intelowlproject/IntelOwl)** (threat intel, Honeynet):
  fixed the Docker build silently upgrading Django (dependency pin), fixed the ExifTool
  analyzer download, and moved the security policy to GitHub private vulnerability reporting.
- **[NVIDIA/TensorRT-Model-Connect](https://github.com/NVIDIA/TensorRT-Model-Connect)**:
  replaced hand-written `MODEL.toml` parsers with `tomllib`/`tomli`.
- **[Internet Archive / Open Library](https://github.com/internetarchive/openlibrary)**:
  removed dead template globals.
- **[Thunderbird Accounts](https://github.com/thunderbird/thunderbird-accounts)**: 503 instead
  of 500 when the mail backend is down.
- **[octochains](https://github.com/ahmadvh/octochains)**: a breach-notification analyst
  preset and a security-incident-triage cookbook demo.
- **[mcp-pandoc](https://github.com/vivekVells/mcp-pandoc)**: Windows + Python 3.13 CI matrix.
- **[jobhunter](https://github.com/justinmclean/jobhunter)**: a `--verbose` run mode
  explaining what each source did.
- **[ankor-training-fe](https://github.com/coachklipstein-ui/ankor-training-fe)**: fixed
  inconsistent form fields between the add/edit flows.

**In review:** checkov (Argo Rollouts support, baseline and CKV_AWS_159 fixes), pwntools
(doctest line numbers, Sphinx 9, Coveralls CI), scapy, Thunderbird Accounts, and more kaaval.

## Other projects

- **[smart-timetable-scheduler](https://github.com/shariqueahmad108-ship-it/smart-timetable-scheduler)**:
  NP-hard timetable scheduling with three solvers (backtracking with MRV/forward checking,
  a genetic algorithm, simulated annealing) behind FastAPI + React, with 47 tests.
- **[network-switcher](https://github.com/shariqueahmad108-ship-it/network-switcher)**:
  macOS menu bar app that switches Wi-Fi between static IP and DHCP based on the network
  you join.
- **[billboard-shield](https://github.com/shariqueahmad108-ship-it/billboard-shield)**:
  transparent, rule-based insurance pricing engine (FastAPI).

## Stack

Python · TypeScript · Swift · FastAPI · React · Kubernetes · Azure · Docker · GitHub Actions
