Install dependencies
```bash
sudo apt install raspi-config
sudo apt install raspi-config
pip install opencv-python
sudo raspi-config
```
Inside interfaces enable legacy camera options.

```bash
sudo nano /boot/firmware/config.txt
```
Add next to the end of file
```
dtoverlay=imx290
start_x=1
```
