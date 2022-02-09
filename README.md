# Installation

Step 1: Add `ngrok.service` to `/lib/systemd/system/`.

Step 2: Start ngrok service by typing:

```
    systemctl enable ngrok.service
    systemctl start ngrok.service
```

To check status

```
journalctl -u service-name.service -b
```