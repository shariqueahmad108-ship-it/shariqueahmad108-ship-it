# Sharique Ahmad

Security-focused developer and student. Currently building a track record of
real open-source contributions ahead of a **Google Summer of Code 2027**
application.

## Focus

- Offensive security / pentesting — recon, vulnerability hunting, RBAC and
  cloud misconfiguration analysis
- Full-stack development — Python, TypeScript, Swift
- Reading real codebases end to end before touching them: every contribution
  below started with tracing the actual code path, not guessing

## Own projects

- **[smart-timetable-scheduler](https://github.com/shariqueahmad108-ship-it/smart-timetable-scheduler)** —
  NP-hard timetable scheduling (reduces to graph coloring). Three solver
  algorithms — backtracking with MRV/forward-checking, a genetic algorithm,
  and simulated annealing — behind a FastAPI backend and React frontend,
  with a 47-test suite and a daily benchmark/health-check script.
- **[network-switcher](https://github.com/shariqueahmad108-ship-it/network-switcher)** —
  A macOS menu bar app that switches Wi-Fi network configs (static IP ↔
  DHCP) automatically based on which network you join. Single Swift file,
  no dependencies, CI-built on every push.

## Open-source contributions

- **[kaaval](https://github.com/kaaval/kaaval)** — self-hosted Kubernetes
  RBAC/CVE security scanner. Fixed a false-negative in the
  combination-escalation detection rules (missing `api_groups` handling
  silently disabled two CRITICAL findings), documented four undocumented
  detection rules, and added a runnable CI example for SARIF scanning.
- **[justinmclean/jobhunter](https://github.com/justinmclean/jobhunter)** —
  added a `--verbose` flag explaining per-source pipeline behavior.
- **[coachklipstein-ui/ankor-training-fe](https://github.com/coachklipstein-ui/ankor-training-fe)** —
  fixed inconsistent form fields between add/edit flows.

## Currently

Working through real, well-scoped issues as a daily habit, building toward
consistent contributions to a security-focused GSoC 2027 org.
