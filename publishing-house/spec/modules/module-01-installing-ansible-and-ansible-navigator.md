# Module 01 — Installing Ansible and Ansible Navigator

### Brief Overview

This module covers the installation of `ansible-core` and `ansible-navigator` on a RHEL 10 system using the AppStream repositories. Participants begin with a clean system that has no Ansible packages installed and complete the module with both tools present and verified. This sets the foundation for hands-on automation work in the modules that follow.

### Audience and Time

- **Target persona:** System administrators new to Ansible
- **Prerequisites for this module:** Basic Linux command-line usage (navigating directories, running commands, editing files); no prior Ansible experience required
- **Estimated duration:** 15 minutes

### Learning Objectives

- Install `ansible-core` from the RHEL 10 AppStream repository using `dnf`
- Install `ansible-navigator` from the RHEL 10 AppStream repository using `dnf`
- Verify both installations by confirming the `ansible` and `ansible-navigator` binaries are present and return expected version output

### Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Confirm AppStream repository availability | 3 min |
| 2 | Install ansible-core | 4 min |
| 3 | Install ansible-navigator | 4 min |
| 4 | Verify both installations | 4 min |

### Detailed Steps

1. Confirm the RHEL 10 AppStream repository is available and accessible on the learner VM.
2. Install `ansible-core` using `dnf` from the AppStream repository.
3. Verify the `ansible` binary is present by running `ansible --version` and reviewing the output.
4. Install `ansible-navigator` using `dnf` from the AppStream repository.
5. Verify the `ansible-navigator` binary is present by running `ansible-navigator --version` and reviewing the output.
6. Use the module verify button to run the automated check that confirms both binaries are present and return expected version output.

### Key Takeaways

- RHEL 10 ships `ansible-core` and `ansible-navigator` in the AppStream repository, requiring no external package sources.
- Both tools can be installed with standard `dnf` commands available to any system administrator.
- Verifying binary presence and version output confirms a functional Ansible installation before proceeding.

### Infrastructure Notes

- The learner environment is a RHEL 10 virtual machine with terminal access.
- RHEL 10 AppStream repositories are pre-configured and accessible on the VM; no Ansible packages are pre-installed.
- The Zero-Touch validate button checks for the presence of the `ansible` and `ansible-navigator` binaries and confirms they return expected version output.
