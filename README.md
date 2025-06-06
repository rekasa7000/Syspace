# 🌌 Syspace

> A matcha-green and galaxy-themed local system & developer metrics dashboard built with Rust + GTK.

Syspace is a floating desktop widget for Fedora GNOME (and other Linux distros) that shows live system stats and development environment metrics — all wrapped in a calming matcha aesthetic with a cosmic UI twist.

---

## ✨ Features

- 🚀 Real-time CPU and memory usage (via `sysinfo`)
- 🌿 Minimal floating GTK window with matcha-green space-inspired theme
- 🛰️ Modular design for:
  - Git repository status (branches, commits, stashes)
  - Docker container status
  - Custom script output metrics
- 🌌 Themed with CSS: dark UI, glowing accents, and monospaced fonts

---

## 🧪 MVP Goals

- [x] Floating GTK window with dark matcha theme
- [x] Display CPU & memory usage live
- [ ] Add Git repository widget (via `git2`)
- [ ] Add Docker container status (via `bollard`)
- [ ] Add support for user-defined scripts (metrics, logs, etc.)

---

## 🧰 Built With

- [Rust](https://www.rust-lang.org/)
- [`gtk4`](https://gtk-rs.org/) – GUI library
- [`sysinfo`](https://docs.rs/sysinfo) – system metrics
- [`git2`](https://docs.rs/git2) – Git info
- [`bollard`](https://docs.rs/bollard) – Docker API (coming soon)

---

## 🐧 System Requirements

- **Fedora Linux** or any Linux distro with GTK 4 support
- Rust 1.75+
- GTK 4 dev libraries (`gtk4-devel` on Fedora)

### 🛠 Install GTK Dev Dependencies

```bash
# For Fedora
sudo dnf install gtk4-devel
```
