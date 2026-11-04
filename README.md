### Currently

- Security engineer on a forensic and incident response team: alerts, malware, phishing, hunts
- B.Sc. in Network Cybersecurity, in progress
- 毎日日本語を勉強します

### Host security tooling

- [banken](https://github.com/conor-sometimes/banken): a host EDR for Linux in Go - Sigma + IOC detection over auditd and eBPF, OCSF/ECS/OTLP output, no kernel module
- [mimi](https://github.com/conor-sometimes/mimi): an eBPF process-telemetry sensor for banken - the ears, what a process did
- [hitomi](https://github.com/conor-sometimes/yara-sensor): a listener-only YARA content scanner for banken - the eyes, what a file is

### banken

A host EDR for Linux, open source under MIT: Sigma rules over audit and eBPF telemetry, YARA rules over files, findings as OCSF or ECS, and a separate least-privilege helper that kills, freezes and quarantines.

- [banken](https://github.com/conor-sometimes/banken): the detection engine and responder, one static Go binary
- [mimi](https://github.com/conor-sometimes/mimi): eBPF process-telemetry sensor in Rust, one probe binary across kernels 5.14 to 7.2
- [hitomi](https://github.com/conor-sometimes/yara-sensor): listener-only YARA content scanner in Rust, fanotify and yara-x

### Nix, mostly

I adore Nix. My servers run NixOS and every project here has a flake.

- [workbench](https://github.com/conor-sometimes/workbench): one declarative Nix environment per project (decomp toolchains, Python, Rust) as an FHS shell or an on-demand container
- [nixos-agent-containment](https://github.com/conor-sometimes/nixos-agent-containment): run AI coding agents behind an egress allow-list, resource limits, an audit trail and an ssh lockdown
- [nixos-hardening](https://github.com/conor-sometimes/nixos-hardening): a VM-tested host-hardening module with opt-in per-user impermanence

### Also

- [pktlib](https://github.com/conor-sometimes/pktlib): read, edit and write Cisco Packet Tracer files from Python. Build a network in code, save it, open it in Packet Tracer. Pure Python, no dependencies, on PyPI
- PS2 decompilation with AI coding agents, byte-matched against the retail game:
  [Lombyte](https://github.com/lombyte-project/Lombyte) (Ratchet & Clank) upstream and
  [Bokura no Kazoku](https://github.com/conor-sometimes/bokura-no-kazoku-decomp) on my own
