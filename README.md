# DoScriptPackage

Official package repository for **DoScript**.

DoScriptPackage is an open-source collection of installable `.do` package scripts built for the **DoScript** automation language.

It allows users to quickly install software, utilities, and bundled toolkits using simple DoScript commands.

---

# What is this?

This repository contains ready-to-use package installer scripts for Windows software.

Example:

```doscript
do https://raw.githubusercontent.com/TheServer-lab/DoScriptPackage/refs/heads/main/files/7zipbootstrap.do
```

That command downloads and runs the installer using DoScript.

---

# Repository Structure

```text
DoScriptPackage/
│── files/          # Individual package installer scripts
│── README.md       # Main repository information
│── Installers.md   # Direct install commands for packages
│── kits.md         # Bundled package collections
```

---

# Included Packages

Examples:

* 7zip
* Git
* Python
* Node.js
* VS Code
* Java
* VLC
* Discord
* Steam

(More packages added regularly)

---

# Quick Install Examples

Install 7zip:

```doscript
do https://raw.githubusercontent.com/TheServer-lab/DoScriptPackage/refs/heads/main/files/7zipbootstrap.do
```

Install Git:

```doscript
do https://raw.githubusercontent.com/TheServer-lab/DoScriptPackage/refs/heads/main/files/gitbootstrap.do
```

Install Python:

```doscript
do https://raw.githubusercontent.com/TheServer-lab/DoScriptPackage/refs/heads/main/files/pythonbootstrap.do
```

---

# Kits

Kits are grouped installs containing multiple packages.

Examples:

* **developer** → Git, Python, Node.js, VS Code
* **gamer** → Discord, Steam, OBS
* **freshpc** → 7zip, VLC, Utilities

See `kits.md` for full list.

---

# Why Use DoScriptPackage?

* Fast setup of new PCs
* Easy software installs
* Clean readable scripts
* GitHub hosted
* Easy updates
* Open source and community driven

---

# Safety

All package scripts are plain text and viewable in this repository before use.

Users can inspect every installer script before running it.

---

# Requirements

* Windows
* DoScript installed

---

# Contributions

Pull requests for new packages, fixes, and kits are welcome.

Suggested contributions:

* New software packages
* Better installers
* Updated download links
* New kit bundles

---

# Maintained By

**TheServer-lab**

---

# License

MIT License

Copyright (c) 2026 TheServer-lab

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
