Install dependencies
```bash
sudo apt install raspi-config
```

```bash
sudo nano /boot/firmware/config.txt
```
Add next to the end of file
```
dtoverlay=imx290
start_x=1
```
