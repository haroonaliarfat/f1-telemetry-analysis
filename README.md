# F1 Telemetry Analysis :

A quick Python script (and for the lovers of it a Notebook variant) that asks to choose year, track and drivers to plot their qualifying telemetries (Speed, Throttle, Brake). Since the output uses the driver's team color, the script will account for the possibility of two drivers being in the same team, in which case it will adapt their color and line syle to make the output more easy to read.

An example of the generated output, comparing Lando Norris and Oscar Piastri during the 2025 Jeddah Qualifying, is:

<img width="1200" height="1000" alt="telemetries" src="https://github.com/user-attachments/assets/6f81abdc-1390-45ff-a814-0187c5a92be5" />

* *To run the script the essential tools are:*
    * **FastF1**: _downloads the data necessary for the comparison_
    * **Matplotlib**: _generates the plot used in the output_
    * **mplcursor**: _access data in the plot with cursor_

*If any of these are not installed, just type:*
    *pip install matplotlib fastf1 mplcursors*

Technical note: the script will create a new directory for the cache in the directory you're running it in
