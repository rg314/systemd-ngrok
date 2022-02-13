# Installation

Step 1: Add user name to line 7 and 8 in `ngrok.service`

Step 2: Add `ngrok.service` to `/lib/systemd/system/`.

Step 3: Start ngrok service by typing:

```
sudo systemctl stop ngrok.service
sudo systemctl enable ngrok.service
sudo systemctl start ngrok.service
sudo systemctl restart ngrok.service
```

To check status

```
journalctl -u ngrok.service -b
```