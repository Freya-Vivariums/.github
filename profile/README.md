![Edgeberry banner](https://raw.githubusercontent.com/Freya-Vivariums/.github/refs/heads/main/brand/Freya_banner.png)

<a href="https://www.youtube.com/watch?v=ab5jGg9vSNA" target="_blank" >
<img src="../documentation/Freya_vivarium.png" align="right" width="32%"/>
</a>

Whether you keep a living ecosystem in your home or manage vivariums professionally, the **Freya Vivarium Control System** takes care of orchestrating the climate variables allowing you to focus fully on the life inside. It monitors environmental conditions and translates sensor readings into actuator control commands through user-defined logic - as simple or complex as your methodology requires.

#### Key Features
- **Methodology-agnostic vivarium control** - Define your own environment simulation logic. Freya provides the measurements, the actuator outputs, and the framework; you provide the knowledge and methodology.
- **Co-creation platform** - Every layer of the system is modular and designed to facilitate independent evolution through collaborative creation. Freya is built to grow through its community.
- **Open in its foundations** - hardware, software, mechanical designs, and documentation are published under open source licenses and built with open source tools, on top of open source platforms.

Connect with the [Freya community on Reddit](https://www.reddit.com/r/FreyaVivariums/).

<br clear="right"/>

## How It Works

<img src="../documentation/Freya_control_loop.png" align="left" width="50%"/>

Freya's architecture is built around the **monitor and control loop** - the same approach used across climate control, agriculture, and industrial automation - applied to vivarium environments.

The [Freya Terra Sensor](https://github.com/Freya-Vivariums/Freya-Terra-Sensor) is positioned in the vivarium, and **measures the conditions** (temperature, humidity, ...).

In the controller, the [Freya Sense'n'Drive Hardware Cartridge](https://github.com/Freya-Vivariums/Freya-SenseAndDrive-Hardware-Cartridge) allows the sensor to connect to the controller and provides outputs for **controlling actuators** like misting pumps, lighting, ... .

The [Freya Node-RED Flow](https://github.com/Freya-Vivariums/Freya-NodeRED-flow) is where you define the **control logic** visually - creating rules and schedules that translate sensor readings into output commands, as simple or complex as your methodology requires.

<br clear="left"/>

## Support us

The **Freya Vivarium Control System is open source and free to use**. The organization behind Freya will never lock features behind a paywall. All hardware designs, software, and flows are open for anyone to use, modify, and share.
If you’d like to support its development and maintenance, you can contribute code — or make a donation through [GitHub Sponsors](https://github.com/sponsors/Freya-Vivariums)!

[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/Freya-Vivariums)
