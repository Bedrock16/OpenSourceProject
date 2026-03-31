# OSS Capstone Project: The Open Source Audit

**Repository:** [Bedrock16/OpenSourceProject](https://github.com/Bedrock16/OpenSourceProject)
**Course:** Open Source Software
**College:** VIT Bhopal University

---

## Software Chosen

**Linux (Bash / GNU Core Utilities)**

* Category: Operating System / Shell Scripting Environment
* License: GPL v2 / GPL v3
* Created by Linus Torvalds (1991)

I chose Linux and Bash scripting because they form the backbone of open-source computing. Through this project, I wanted to explore how shell scripts can automate system inspection, package auditing, log analysis, and more — all using the philosophy of FOSS tools chained together.

---

## Repository Contents

| File | Description |
| ---- | ----------- |
| `SystemIdentityReport.sh` | Displays system information such as kernel version, user, uptime, and OS details |
| `FOSSPackageInspector.sh` | Checks if a package is installed, shows its version, and prints a short description |
| `DirectoryAuditReport.sh` | Analyzes key directories and displays their size, owner, and permissions |
| `LogFileAnalyzer.sh` | Reads a log file and counts occurrences of a keyword |
| `OpenSourceManifestoGenerator.sh` | Generates a personalized open-source manifesto based on user input |

---

## Screenshots

### System Identity Report
![System Identity Report](https://raw.githubusercontent.com/Bedrock16/OpenSourceProject/main/images/SystemIdentityReport.png)

### FOSS Package Inspector
![FOSS Package Inspector](https://raw.githubusercontent.com/Bedrock16/OpenSourceProject/main/images/FOSSPackageInspector.png)

### Directory Audit Report
![Directory Audit Report](https://raw.githubusercontent.com/Bedrock16/OpenSourceProject/main/images/DirectoryAuditReport.png)

### Log File Analyzer
![Log File Analyzer](https://raw.githubusercontent.com/Bedrock16/OpenSourceProject/main/images/LogFileAnalyzer.png)

### Open Source Manifesto Generator
![Open Source Manifesto Generator](https://raw.githubusercontent.com/Bedrock16/OpenSourceProject/main/images/OpenSourceManifestoGenerator.png)

> **Note:** If images do not load, please check the `images/` folder in the repository for screenshots.

---

## How to Run the Scripts

### Step 1: Clone the repository

```bash
git clone https://github.com/Bedrock16/OpenSourceProject.git
cd OpenSourceProject
```

### Step 2: Make scripts executable

```bash
chmod +x *.sh
```

### Step 3: Run scripts

**Script 1 — System Identity Report**

```bash
./SystemIdentityReport.sh
```

Displays system information including kernel version, hostname, current user, uptime, and OS details.

---

**Script 2 — FOSS Package Inspector**

```bash
./FOSSPackageInspector.sh [package_name]
```

* If no package name is provided, it defaults to `git`
* Example: `./FOSSPackageInspector.sh curl`

---

**Script 3 — Directory Audit Report**

```bash
./DirectoryAuditReport.sh
```

Analyzes key system directories and displays their size, owner, and permission settings.

---

**Script 4 — Log File Analyzer**

```bash
./LogFileAnalyzer.sh <logfile> [keyword]
```

Example:

```bash
./LogFileAnalyzer.sh /var/log/syslog error
```

Reads the specified log file and counts how many times the keyword appears.

---

**Script 5 — Open Source Manifesto Generator**

```bash
./OpenSourceManifestoGenerator.sh
```

Interactively generates a personalized open-source manifesto based on your input.

---

## Requirements

* Linux system or macOS terminal
* Bash shell (pre-installed on most systems)
* Git installed

  * On Ubuntu/Debian: `sudo apt install git`
  * On macOS: `brew install git`
  * On Fedora: `sudo dnf install git`

---

## Notes

* All scripts were tested on a Linux (Ubuntu) environment.
* Each script includes inline comments explaining its functionality.
* The `images/` folder contains screenshots of each script's execution output.
* Scripts follow the UNIX philosophy: do one thing and do it well.

---

## References

* https://www.gnu.org/philosophy/free-sw.html
* https://opensource.org/osd
* https://www.kernel.org/
* https://www.gnu.org/software/bash/
* https://catb.org/~esr/writings/cathedral-bazaar/
* https://survey.stackoverflow.co/2023
* https://spdx.org/licenses/GPL-2.0-only.html
* https://github.com/Bedrock16/OpenSourceProject
