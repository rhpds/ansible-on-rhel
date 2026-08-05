# Module 02 — Running Your First Playbook

### Brief Overview

This module guides participants through creating a basic Ansible playbook and running it with Ansible Navigator. Building on the installations completed in Module 1, participants write a simple playbook, execute it, and confirm the environment is fully functional. Completing this module satisfies the second lab-level learning objective.

### Audience and Time

- **Target persona:** System administrators new to Ansible
- **Prerequisites for this module:** Completion of Module 1 (both `ansible-core` and `ansible-navigator` installed and verified); basic Linux command-line usage
- **Estimated duration:** 15 minutes

### Learning Objectives

- Create a basic Ansible playbook
- Run the playbook using `ansible-navigator`
- Verify the playbook executed successfully and produced the expected output

### Lab Structure

| Section | Title | Duration |
|---------|-------|----------|
| 1 | Understand basic playbook structure | 3 min |
| 2 | Create the playbook file | 5 min |
| 3 | Run the playbook with Ansible Navigator | 4 min |
| 4 | Verify the output | 3 min |

### Detailed Steps

1. Review the basic structure of an Ansible playbook: a YAML file containing one or more plays, each defining a set of hosts and tasks.
2. Create a new playbook file in the working directory on the learner VM.
3. Define a play that targets the local machine and includes at least one task.
4. Save the playbook file.
5. Run the playbook using the `ansible-navigator run` command.
6. Review the output produced by `ansible-navigator` to confirm the play completed without errors and produced the expected result.
7. Use the module verify button to run the automated check that confirms the playbook ran and produced the expected output.

### Key Takeaways

- Ansible playbooks are YAML files that describe the desired state of managed hosts.
- `ansible-navigator` provides a terminal-based interface for running playbooks and reviewing execution results.
- A successful playbook run confirms a fully working Ansible environment on RHEL 10.

### Infrastructure Notes

- The learner environment is the same RHEL 10 virtual machine used in Module 1, with `ansible-core` and `ansible-navigator` already installed.
- The Zero-Touch validate button confirms the playbook ran and produced the expected output.
