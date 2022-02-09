# Installation

Step 1: Add `ngrok.service` to `/lib/systemd/system/`.

Step 2: Start ngrok service by typing:

```
sudo systemctl enable ngrok.service
sudo systemctl start ngrok.service
```

To check status

```
journalctl -u ngrok.service -b
```