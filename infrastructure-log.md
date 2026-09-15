# Infrastructure Log

Physical changes to the cluster's hardware, racking, cabling, power, and cooling — kept separate from software/cluster-config changes (see [cluster-changelog.md](cluster-changelog.md) for those).

Most recent entries at the top.

## Format

| Date | Change | Why / Notes |
| ---- | ------ | ----------- |

---

## Log

| Date       | Change                                             | Why / Notes                                                                                      |
| ---------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| 2026-07-XX | Terminated Cat6 ethernet runs to a patch panel      | Replaced loose point-to-point ethernet runs with structured cabling for cleaner rack organization and easier troubleshooting |
| 2026-06-30 | Assembled Tecmojo 6U Network Rack, 10 inch Mini Server Rack | Main housing unit for nodes, storage, and wiring|
| 2026-06-29 | Purchased 2x Seagate SATA 2.5" SSD                  | Storage for backing up running applications                                                       |
| 2026-06-23 | Purchased 4x 10 inch 1U Mini PC Rack Mount Shelves | Proper housing unit for Kubernetes cluster nodes.
| 2026-06-23 | Purchased a Tecmojo 6U Network Rack, 10 inch Mini Server Rack | Main |
| 2026-04-04 | Purchased 3x HP EliteDesk 800 G3 Mini PCs (i5-6500T, 8GB RAM, no drive/OS) | Low-power (35W) mini PCs chosen for compact, energy-efficient worker nodes; added drives/OS separately |
| 2026-04-03 | Purchased a refurbished Lenovo ThinkCentre           | Added as a node so I could SSH in remotely from college and practice remote administration        |
| 2026-03-01 | Purchased a refurbished Lenovo ThinkPad T14 Gen 1    | Personal laptop for experimenting with Linux distributions outside of school use                  |
| 2026-03-29 | Purchased a Tecmojo 12U Open Frame Network Rack | Started as a general homelab project before the Kubernetes cluster idea existed. Bought the rack partly as a forcing function — having already invested money pushed me to actually start building rather than keep planning |

---

## Notes

- Add a new row at the top of the table each time something physical changes — new hardware, cabling, cooling, power, rack layout, etc.
- If a change was driven by a problem (e.g. thermal issues, a node dropping offline), note the symptom, not just the fix — that's the part that's useful in an interview.
