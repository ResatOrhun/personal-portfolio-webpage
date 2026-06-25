# Resat Orhun Konak — Network Engineering Portfolio

A single-page portfolio built around a Cisco router CLI: a boot sequence on
load, navigation rendered as a routing table, and three network engineering
projects presented as animated topology diagrams rather than static
screenshots.

**Live site:** https://resatorhun.github.io/personal-portfolio-webpage/

## Overview

Computer Engineering graduate (Politecnico di Torino) focused on
high-availability network design and Layer 3 switching, currently completing
CCNA certification. The portfolio is built around three projects from that
focus:

- A dual-homed eBGP internet edge with Multi-Area OSPF redistribution and a secured DMZ
- A fully redundant three-switch Layer 3 core with manual STP tuning and LACP EtherChannels
- A multi-site hub-and-spoke WAN built on 802.1Q trunking and VLSM addressing

## Features

- Cisco IOS–style boot sequence on page load
- Navigation styled as a `show ip route` routing table, with active-section highlighting
- Each project paired with an inline, animated SVG topology diagram matching its real configuration
- Skills presented as `show ip protocols` output
- CCNA status shown as a live interface status line
- A small interactive command-line section for visitors to explore

## Tech Stack

HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies.

## Getting Started

Clone the repository and open `index.html` in any browser:

```bash
git clone https://github.com/ResatOrhun/network-portfolio.git
cd network-portfolio
open index.html
```

## Contact

- Email: [konakresat@gmail.com](mailto:konakresat@gmail.com)
- LinkedIn: [linkedin.com/in/resatorhunkonak](https://www.linkedin.com/in/resatorhunkonak/)
- GitHub: [github.com/ResatOrhun](https://github.com/ResatOrhun)
