## NeoBSD Source:

This is the top level of the NeoBSD source directory.

**NeoBSD** is a modern operating system designed to power servers, cloud infrastructure, web services, desktops, and embedded platforms. Building on a strong BSD and UNIX heritage, NeoBSD aims to combine cutting-edge features, easy management, and strong security with robust, proven technology.

The NeoBSD project continues a lineage of operating systems developed and improved by a large community for more than thirty years. NeoBSD offers advanced networking, security, and storage capabilities making it a platform of choice for demanding infrastructure, high-traffic web services, and pervasive embedded and cloud environments.

For copyright and license information, please see [the file COPYRIGHT](COPYRIGHT) in this directory.  
Additional copyright information may also be present within individual source directories.

The Makefile in this directory supports building components or the entire NeoBSD source tree.  
For detailed build instructions, see build(7), config(8), and [the NeoBSD handbook section on building userland](https://docs.neobsd.org/en/books/handbook/cutting-edge/#makeworld), as well as [the kernel configuration guide](https://docs.neobsd.org/en/books/handbook/kernelconfig/). These references also contain information about build variables used with make(1).

For up-to-date information on platforms and CPU architectures supported by NeoBSD, see the [NeoBSD Platforms page](https://www.neobsd.org/platforms/).

For official NeoBSD bootable images, see the [release download page](https://download.neobsd.org/ftp/releases/ISO-IMAGES/).

## Source Roadmap:
---------------
| Directory   | Description |
|-------------|-----------------------------------|
| bin         | System/user commands.             |
| cddl        | Various commands and libraries under the Common Development and Distribution License. |
| contrib     | Packages contributed by 3rd parties. |
| crypto      | Cryptography resources (see [crypto/README](crypto/README)). |
| etc         | Template files for /etc.          |
| gnu         | Commands and libraries under the GNU GPL or LGPL. See [gnu/COPYING](gnu/COPYING) and [gnu/COPYING.LIB](gnu/COPYING.LIB) for details. |
| include     | System include files.             |
| kerberos5   | Kerberos5 (Heimdal) package.      |
| lib         | System libraries.                 |
| libexec     | System daemons.                   |
| release     | Release building Makefile & tools.|
| rescue      | Statically linked rescue utilities build system.|
| sbin        | System commands.                  |
| secure      | Cryptographic libraries and commands. |
| share       | Shared resources.                 |
| stand       | Boot loader sources.              |
| sys         | Kernel sources (see [sys/README.md](sys/README.md)). |
| targets     | Experimental `DIRDEPS_BUILD` support.|
| tests       | Regression tests run by Kyua. See [tests/README](tests/README). |
| tools       | Utilities for regression testing and maintenance tasks. |
| usr.bin     | User commands.                    |
| usr.sbin    | System administration commands.   |

To synchronize your source tree with the current NeoBSD development branches, please refer to the [NeoBSD Handbook](https://docs.neobsd.org/en/books/handbook/cutting-edge/#current-stable).

---

**Note:**  
If you wish to mention inspiration or lineage, you can append a simple acknowledgment like:

> NeoBSD is based in part on the original FreeBSD source code. We acknowledge and thank the FreeBSD Project and the entire BSD community for their ongoing contributions to open source.