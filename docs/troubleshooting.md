# LinuxCat Server Troubleshooting Guide

## 1. SSH troubleshooting

### Permission denied (publickey)

Check:

- Correct SSH username
- Correct private key
- authorized_keys configuration
- SSH file permissions

Commands:

```bash
chmod 700 ~/.ssh
chmod 600 ~/.ssh/authorized_keys
ssh -v linuxcat
