# PC-Tuning

[![Discord](https://discordapp.com/api/guilds/994887453599076422/widget.png?style=shield)](https://discord.com/invite/yrAnChXXZw)

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/amitxv)

## Rationale

Windows is notorious for its ever-growing bloatware, third-party telemetry, excessive context switching, interrupts and I/O. This repository was created in hope of standardizing systems for latency-sensitive tasks and minimizing unwanted outgoing traffic. Note that the OS-related sections aren't indented to be followed on existing Windows installations. On the contrary, the mentioned sections will guide you to customize an ISO using DISM then reinstall Windows properly.

This repository may contain information similar to those of the projects listed in the [Further Reading](#further-reading) section, however, it isn't my intention to directly copy from them.

The guidance is currently updated and has been tested on client and server editions of Windows 7 through to Windows 11 (x64). See a full list of [issues](https://github.com/amitxv/PC-Tuning/issues). Users are expected to follow the guidance in the order listed below starting with [Physical Setup](#physical-setup) through to [Post-Install Instructions](#post-install-instructions).

## Staying Informed

The contents and information included in this repository will inevitably change over time. To stay up to date, I would recommend reviewing what has changed once in a while. At the time of reviewing, take a note of the 7 digit SHA code in the [latest commit](https://github.com/amitxv/PC-Tuning/commit/main) (e.g. ``2428150``) then use the URL below as an example to compare what has changed since the noted commit.

<https://github.com/amitxv/PC-Tuning/compare/2428150..main>

## Requirements

- USB Storage Device (8 GB minimum)
- [Ventoy](https://github.com/ventoy/Ventoy/releases)
- Any live Linux distribution
- Familiarity with navigating directories in CLI

## 1. Physical Setup

- See [docs/physical-setup.md](/docs/physical-setup.md)

## 2. Pre-Install Instructions

- See [docs/pre-install.md](/docs/pre-install.md)

## 3. Post-Install Instructions

- See [docs/post-install.md](/docs/post-install.md)

## 4. Research

- See [docs/research.md](/docs/research.md)

## Further Reading

- [BoringBoredom/PC-Optimization-Hub](https://github.com/BoringBoredom/PC-Optimization-Hub)

- [Calypto's Latency Guide](https://docs.google.com/document/d/1c2-lUJq74wuYK1WrA_bIvgb89dUN0sj8-hO3vqmrau4)

- [djdallmann/GamingPCSetup](https://github.com/djdallmann/GamingPCSetup)

- [klasbo/GamePerfTesting](https://github.com/klasbo/GamePerfTesting)

- [sieger/handbook](https://github.com/sieger/handbook)

- Windows Internals, Part 1: System Architecture, Processes, Threads, Memory Management, and More

- Windows Internals, Part 2
