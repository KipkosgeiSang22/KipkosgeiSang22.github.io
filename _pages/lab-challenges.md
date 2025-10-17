---
title: "Lab Challenges"
layout: single
permalink: /lab-challenges/
---

## 🔍 Challenge: obfuscate and create a stanadlone executable file 

## 🔍 Challenge: Obfuscate and Create a Standalone Executable File

### 🧩 Problem Statement
Securely distribute a Python-based SOC automation script as a standalone executable. The goals were:
- Prevent reverse engineering or casual inspection of source code.
- Ensure the executable runs independently on Windows systems without requiring Python installation.
- Maintain reproducibility, error resilience, and professional-grade polish for academic and client-facing deployment.

- ---

### 🔗 GitHub Repository

You can find the full implementation and source code here:  
[🔐 Obfuscating and Creating a Standalone Executable File](https://github.com/KipkosgeiSang22/obfuscating-and-creating-stanadalone-executable-file.git)

---

---

### 🛠️ Approach

#### 1. Obfuscation with Cython
- Converted `.py` files into `.c` extensions using Cython.
- Compiled them into platform-specific binaries to obscure logic and protect intellectual property.
- Validated compatibility with async functions and third-party libraries.

#### 2. Packaging with PyInstaller
- Used PyInstaller to bundle obfuscated binaries and dependencies into a single `.exe`.
- Tuned CLI flags like `--onefile`, `--noconsole`, and `--hidden-import` for clean execution.
- Iteratively resolved runtime errors, import path issues, and packaging quirks.

---

### ⚙️ Tools Used

| Tool         | Purpose                                                  |
|--------------|----------------------------------------------------------|
| **Cython**   | Converts Python code to C for obfuscation                |
| **PyInstaller** | Packages code and dependencies into a standalone executable |
| **Python 3.8+** | Core language for async scripting                     |
| **aiohttp + asyncio** | Async log fetching and orchestration           |
| **pandas + openpyxl** | Data transformation and Excel export           |
| **re + pytz** | Regex parsing and timezone conversion                   |
| **Windows Defender / Bitdefender** | Tested executable against false positives |

---

### 📚 Lessons Learned

- ✅ Obfuscation requires validation of async compatibility and third-party imports.
- ✅ PyInstaller flags must be carefully tuned to avoid broken imports or runtime crashes.
- ✅ Security software may block executables—test and document safe execution practices.
- ✅ Error resilience is essential—graceful fallbacks for API failures and empty results were built in.
- ✅ Workflow polish matters—iterated until the executable was clean, reproducible, and professional.
- ✅ Documentation is part of the solution—deployment notes and packaging instructions support future use.

---


