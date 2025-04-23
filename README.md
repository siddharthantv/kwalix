# Kwalix OS

Kwalix OS is a minimalist, privacy-focused Linux distribution built to provide a customizable and efficient environment for developers. Designed with simplicity and performance in mind, Kwalix aims to provide a user-friendly operating system that is both flexible and secure, using a custom Linux kernel, Bash as the shell, systemd for initialization, and Dracut for initramfs creation.

---

## Features

- **Customizable User Interface**: Kwalix offers a clean and modern desktop environment, with an emphasis on simplicity and ease of use.
- **Privacy-Focused**: Built with privacy in mind, Kwalix integrates tools and settings to help users protect their data.
- **Systemd Initialization**: Uses the systemd init system for efficient startup and service management.
- **Dracut Initramfs**: Kwalix uses Dracut to generate a minimal, flexible initramfs for fast booting.
- **Package Management**: Kwalix leverages the Nix package manager for a functional and transactional package management system.

---

## Getting Started

To get started with Kwalix OS, you will need to:

1. **Download the ISO**: 
    - Download the latest release of Kwalix OS from the [Releases](https://github.com/siddharthantv/kwalix/releases) section.
  
2. **Create a Bootable USB**:
    - Use a tool like `dd` or `Etcher` to create a bootable USB drive with the downloaded ISO.

3. **Install Kwalix OS**:
    - Boot your system from the USB drive.
    - Follow the installation guide (coming soon).

---

## Documentation

- **[Architecture](docs/architecture.md)**: An in-depth look at Kwalix OS architecture and design decisions.
- **[Build Process](docs/build-process.md)**: Step-by-step guide for building Kwalix OS from source.

---

## License

Kwalix OS is licensed under the [GNU General Public License v3.0](LICENSE).

---

## Contributing

We welcome contributions to Kwalix OS! If you have an idea, bug report, or want to contribute code, please open an issue or create a pull request.

**Steps to contribute:**
1. Fork the repository.
2. Clone your fork to your local machine.
3. Create a new branch: `git checkout -b feature-branch`.
4. Commit your changes: `git commit -m "Add feature"`.
5. Push to your fork: `git push origin feature-branch`.
6. Create a pull request.

---

## Contact

For any inquiries or support, feel free to reach out:

- **Email**: tvsiddharthan@gmail.com
- **GitHub**: [@siddharthantv](https://github.com/siddharthantv)

---

## Acknowledgements

- **Linux Kernel**: The foundation of Kwalix OS.
- **systemd**: For efficient service management.
- **Dracut**: For generating initramfs.
- **Nix Package Manager**: For functional, declarative package management.
- **GNOME**: For the desktop environment.

---

## Roadmap

- **Version 1.0 (Stable Release)**:
    - Finalize system installation process.
    - Improve desktop environment and user experience.
  
- **Version 2.0 (Future)**:
    - Add more privacy features.
    - Improve package management and documentation.

---

Thank you for checking out Kwalix OS!

