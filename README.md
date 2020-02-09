# songpal - mod
On some devices like sound bar "HT-MT500/501", volume decrease is not work out of the box.
This custom component workaround the issue.
Also try fix issue - HA infinity loop on restart.
## Example configuration.yaml
```yaml
media_player:
  - platform: songpal_m
    name: room1
    endpoint: http://<host_or_ip>:10000/sony
```
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)
