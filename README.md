# Detection-as-Code SOC Lab

A purple-team lab built on real hardware (Linux + Windows endpoints, attacker box,
cloud SIEM) where detections are written as Sigma rules and tested through CI/CD.

## Status
- [ ] Week 1: Planning and repo setup
- [ ] Week 2: SIEM deployment and log collection
- [ ] Week 3: Attack simulation and baseline
- [ ] Week 4: Sigma rules mapped to MITRE ATT&CK
- [ ] Week 5: CI/CD pipeline for detections
- [ ] Week 6: SOAR automation
- [ ] Week 7: Coverage dashboard and metrics
- [ ] Week 8: Incident report and final write-up

## Architecture
_Diagram coming soon (see /diagrams)_

## Lab Safety
_Coming soon_

## Repository Structure
| Folder | Purpose |
|---|---|
| `detections/sigma/` | Sigma rules, each mapped to an ATT&CK technique |
| `attack-sims/` | Attack simulation scripts and expected results |
| `.github/workflows/` | CI pipeline for rule validation |
| `soar/` | Automation playbooks |
| `reports/` | Incident reports |
| `docs/` | Setup guides and lessons learned |

## Results
_Metrics will be added as the project progresses_
