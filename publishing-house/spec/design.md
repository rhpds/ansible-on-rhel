# Getting Started with Ansible on RHEL 10

## Overview

This lab introduces system administrators to Ansible by walking through the installation of `ansible-core` and `ansible-navigator` on Red Hat Enterprise Linux 10 using AppStream repositories. No prior Ansible experience is required. Participants will install both tools, then create and run a basic playbook using Ansible Navigator to confirm a working setup.

## Target Audience

- **Role:** System administrators
- **Experience level:** Beginner
- **What they already know:** Basic Linux command-line usage (navigating directories, running commands, editing files)
- **What they don't know:** Ansible concepts, playbook structure, or Ansible Navigator usage

## Prerequisites

- Basic familiarity with the Linux command line
- Cannot be automatically validated — trust-based

## Learning Objectives

1. Install `ansible-core` and `ansible-navigator` from RHEL 10 AppStream repositories
2. Create a basic Ansible playbook and verify it runs successfully using Ansible Navigator

## Content Type

Lab (hands-on)

## Products & Technologies

- Red Hat Enterprise Linux 10
- ansible-core (RHEL 10 AppStream)
- ansible-navigator (RHEL 10 AppStream)

## Module Map

| Module | Title | Duration |
|--------|-------|----------|
| 1 | Installing Ansible and Ansible Navigator | 15 min |
| 2 | Running Your First Playbook | 15 min |
| — | **Total hands-on** | **30 min** |
| — | Intro / presentation | ~5 min |
| — | **Total lab** | **~35 min** |

## Difficulty Level

Beginner

## Environment

**Learner view:** A RHEL 10 virtual machine with terminal access. The system has RHEL 10 AppStream repositories available. No Ansible packages are pre-installed — participants install everything themselves as part of the lab.

**Automation needed:** Yes — a RHEL 10 VM must be provisioned with AppStream repos configured and accessible.

## Infrastructure Requirements

- **Cloud provider:** TBD — confirmed in infrastructure phase
- **Cluster type:** TBD — confirmed in infrastructure phase
- **OCP version:** TBD — confirmed in infrastructure phase
- **Topology:** TBD — confirmed in infrastructure phase
- **Sizing:** TBD — confirmed in infrastructure phase
- **Automation approach:** TBD — confirmed in infrastructure phase
- **AI/MaaS:** TBD — confirmed in infrastructure phase
- **External services:** TBD — confirmed in infrastructure phase
- **AAP version:** TBD — confirmed in infrastructure phase
- **Non-GA products:** TBD — confirmed in infrastructure phase

## Assessment Strategy (Optional)

This is a Zero-Touch lab. Each module has a verify/validate button:

- **Module 1:** Automated check confirms `ansible` and `ansible-navigator` binaries are present and return expected version output
- **Module 2:** Automated check confirms the playbook ran and produced the expected output
