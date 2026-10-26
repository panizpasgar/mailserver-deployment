# Mail Server Installation

## Step 1: Install Postfix and Dovecot

In this step, install the Postfix and Dovecot packages on Rocky Linux / AlmaLinux using the DNF package manager.

### Command

```bash
dnf install postfix dovecot -y
```


![Postfix and Dovecot Package Installation](images/01-package-installation.png)


### Description

- `dnf`: Package manager for Rocky Linux and AlmaLinux.
- `install`: Installs the specified packages.
- `postfix`: Mail Transfer Agent (MTA) responsible for SMTP mail transport.
- `dovecot`: Provides IMAP and optional POP3 services for mailbox access.
- `-y`: Automatically confirms installation prompts.

### Verify Installation

Run the following command to verify that both packages are installed:

```bash
rpm -q postfix dovecot
```



