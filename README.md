# tempertray
Python script to show temperature readings from a Temper USB thermometer in the Windows system tray.

Required modules:

infini.systray https://github.com/Infinidat/infi.systray
temper-windows https://pypi.org/project/temper-windows/
pillow https://pillow.readthedocs.io/en/stable/

infini.systray is used to create the Windows system tray icon.
temper-windows is the module needed to read temperatures from the Temper USB device.
pillow is needed to dynamically generate the image for the system tray icon.


Install all needed modules with pip:

pip install infi.systray temper-windows pillow
