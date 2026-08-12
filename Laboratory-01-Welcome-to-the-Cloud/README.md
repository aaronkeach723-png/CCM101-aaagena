# Laboratory Activity 01: Welcome to the Cloud

## Mission Overview
As a Junior Cloud Infrastructure Engineer Trainee at CloudNova Technologies, this onboarding mission focuses on gaining hands-on experience in a Linux cloud environment, executing foundational administration commands, structuring workspace directories, and establishing a professional, version-controlled portfolio repository on GitHub.

## Objectives
- Access and navigate a cloud-based Linux environment using KillerCoda.
- Create non-root user accounts with administrative (`sudo`) privileges.
- Gather core hardware and operating system metrics.
- Build a standardized workspace directory hierarchy.
- Document lab activities using structured Markdown and version control via Git/GitHub.

## Activities Performed
1. **User Management:** Created non-root user `aaagena` with home directory, set a password, and granted `sudo` permissions.
2. **Environment Verification:** Verified logged-in user, current working directory, and system hostname.
3. **System Inspection:** Collected system information (Linux distribution, kernel version, CPU architecture, total RAM, and available disk space) and saved it to `system-information.md`.
4. **Workspace Organization:** Created subdirectories (`Notes/`, `screenshots/`) and generated `about-me.md` containing engineer details.
5. **Portfolio Assembly:** Assembled mission evidence screenshots and published all structured files to the GitHub portfolio repository.

## Linux Commands Used
- `useradd` / `usermod` - Created user `aaagena` with bash shell, home directory, and `sudo` access.
- `passwd` - Set password for the user account.
- `su - aaagena` - Switched from `root` to `aaagena` user session.
- `whoami`, `pwd`, `hostname` - Confirmed current active user, current folder path, and host system name.
- `cat /etc/os-release` - Inspected Linux distribution version details.
- `uname -r` - Retrieved active Linux kernel version.
- `lscpu` - Inspected CPU model and architecture metrics.
- `free -h` - Checked total and available system memory.
- `df -h` - Inspected disk partition sizes and available storage space.
- `mkdir` - Created directory structures (`Notes/`, `screenshots/`).
- `cat` - Generated and displayed Markdown document contents.

## Skills Learned
- Linux CLI navigation and user account administration.
- System metrics extraction and interpretation.
- Professional Markdown documentation standards.
- Git repository organization and GitHub portfolio management.
