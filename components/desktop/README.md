# VANTA
### The Physics Desktop for Sorabbyngo OS.

**Your files are real objects. Throw them. Pile them. Pin them. No more folders.**

Vanta is the spatial desktop environment of **Sorabbyngo OS — OS ONE**. It reimagines the conventional desktop as a physical workspace where files, windows and applications become objects that users can arrange, manipulate and organize naturally.

Vanta is not a theme, launcher or file manager skin. **Vanta is the desktop.**

## Why Vanta?

Traditional desktops rely on folders, grids and menus. Vanta explores a more natural approach to digital organization through spatial interaction.

Instead of navigating endless directories, users can organize information by location, proximity and relationships.

## Core Experience

- **Throw:** Move objects with momentum, friction and collision.
- **Pile:** Group related files into spatial collections.
- **Fan Out:** Spread a pile to reveal its contents.
- **Pin to Wall:** Keep important documents and references visible.
- **Tidy:** Arrange scattered objects into an organized workspace.
- **Real Windows:** Integrate actual applications, not static screenshots.
- **AI-Native:** Enable future interaction through AION, Sorabbyngo's intelligent computing layer.

These describe Vanta's intended experience; availability depends on implementation and testing.

## Architecture

| Component | Technology / Role |
|---|---|
| Platform | Sorabbyngo OS — OS ONE |
| Foundation | Fedora Base |
| Display protocol | Wayland |
| Compositor | Native Rust compositor using Smithay |
| Spatial environment | Object and physics-based interaction |
| AI integration | AION (planned integration) |

Godot 4 may support isolated prototypes. The production compositor is developed natively using Rust and Smithay.

## Development Status

**Prototype — Active Development**

Existing engineering foundations include:
- Rust and Smithay compositor development.
- Wayland XDG shell support.
- Basic window movement and resizing.
- Floating window management.
- Initial compositor IPC.

The broader spatial desktop experience, including physics-based file interaction, piles, wall pinning and intelligent organization, is under development.

## Design Principles

1. Spatial memory over endless directory navigation.
2. Direct interaction over layers of menus.
3. Real applications over visual simulations.
4. User control over automation.
5. A desktop that can evolve with future computing.

## Future Direction

Vanta is designed for conventional laptop and desktop displays first. Future possibilities include multi-touch interaction, collaborative workspaces, AION integration and optional VR support.

## Engineering

Vanta is developed independently within the Sorabbyngo OS engineering organization.

**Source repository:** https://github.com/sorabbyngo-os/vanta

This page documents the component's identity and official release information. Source code and engineering history remain in the engineering repository.

## Releases

Vanta has an independent component version. Official releases require maintainer review and approval.

No production release is declared by this page.

## License

**GPL-3.0-only — current licensing direction.**

Sorabbyngo-developed Vanta components are intended to use GNU GPL version 3.0 only, subject to ownership, contribution and dependency review. Third-party software retains its respective licenses.

GPL v3 permits commercial use, modification and redistribution under its terms.

See https://www.gnu.org/licenses/gpl-3.0.html.

---

**Vanta — The Physics Desktop for Sorabbyngo OS.**
