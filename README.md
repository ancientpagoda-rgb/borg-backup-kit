[Buy the kit ($27) on Gumroad](https://pagodawhisper.gumroad.com/l/swwapt)

# Borg Backup Kit (Linux / systemd)

A small, opinionated kit to set up **encrypted**, **automated** backups using **Borg** over **SSH**, including:

- daily scheduled backups (systemd user timer)
- retention policy (daily/weekly/monthly)
- desktop notification on failure (notify-send)
- a restore drill script to prove restores work

## Quick start

```bash
./install.sh
```

## Run a backup now

```bash
systemctl --user start borg-kit-backup.service
```

## Restore drill

```bash
./restore-drill.sh
```

GitHub repo: https://github.com/ancientpagoda-rgb/borg-backup-kit
