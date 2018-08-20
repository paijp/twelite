# twelite
- Dockerfile for mono-wireless TWELITE SDK.

https://mono-wireless.com/jp/products/TWE-NET/TWESDK.html

- `cd /opt/mono-wireless/MWSDK/Wks_TWELITE/Samp_PingPong/PingPong/Build&& sh BuildAll.sh` to build a project.
- `docker run -it --rm --device=/dev/bus/usb twelite bash` to use tweterm.py
- You may have to restart a container when you plug a USB writer.
