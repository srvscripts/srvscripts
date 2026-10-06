### srvScripts: tested scripts, guides and free tools for server admins

We run Linux and Windows servers, mail and VoIP for a living, and publish what we use: scripts we have run on real lab servers, step-by-step guides, and browser-based checkers you can point at your own domain or server.

**Where to start**

- 📜 [Script library](https://github.com/srvscripts/scripts): Bash, PowerShell and Python for cPanel, DirectAdmin, CloudLinux, Asterisk/FreePBX and Windows Server. MIT licence. Every script has a page on [srvscripts.com/scripts](https://srvscripts.com/scripts/) explaining what it does and how it was tested.
- 🧰 [Free tools](https://srvscripts.com/tools/): DNS, SPF/DKIM/DMARC, SSL/TLS, blacklist, SMTP, subnet and VoIP checkers. No sign-up.
- 📘 [Guides](https://srvscripts.com/guides/) and [cheat sheets](https://srvscripts.com/cheat-sheets/): Linux, Windows Server and Active Directory, email deliverability, control panels and VoIP.
- ⬇️ [scr.srvscripts.com](https://scr.srvscripts.com/): every free script as a plain file with its SHA-256 checksum.

**Verify before you run**

```bash
curl -fsSL -o script.sh https://scr.srvscripts.com/<slug>/<file> && curl -fsSL https://scr.srvscripts.com/<slug>/<file>.sha256 | sha256sum -c
```

Each script page also shows the Windows PowerShell version with the expected hash.

**Get involved**

- Found a bug or a script that misbehaves on your distro? [Open an issue](https://github.com/srvscripts/scripts/issues).
- Questions, ideas and requests: [Discussions](https://github.com/srvscripts/scripts/discussions).
- Need it done for you: [Get it fixed](https://srvscripts.com/get-it-fixed/).

<sub>Scripts are MIT licensed: if you copy, share or adapt one, keep its header and credit srvScripts.com.</sub>
