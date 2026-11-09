<h1 align="center">Hi, I'm Jaber 👋</h1>

<p align="center">
  <b>Final-year Electrical & Electronics Engineering student</b><br>
  Embedded Systems · Circuit Design · PCB Design · Control Systems
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Analog%20%26%20Digital%20Electronics-1f2328?style=flat-square" />
  <img src="https://img.shields.io/badge/PCB%20Design-learning-bf8700?style=flat-square" />
</p>

---

I like knowing what's really going on inside a circuit: why a pin goes high, where the current actually flows, and what fails first when things heat up.

Most of the projects here started on a breadboard. A 555 timer driving traffic lights, a shift register that turns 3 Arduino pins into 8 outputs, and a cooling system that switches fans through a MOSFET when a GPU enclosure gets too hot. A few of them I've rebuilt and properly documented for the first time. One is an unfinished experiment I kept on purpose, because figuring out why it didn't work taught me more than the parts that did.

These days I'm learning PCB design, so I can take these ideas off the breadboard and onto boards of my own.

## 🔧 Projects

Each project has its own repository with the circuit, the code, the design decisions behind it, and what I'd do differently next time.

| | Project | What it's really about |
|:-:|---|---|
| 🌡️ | **[GPU Thermal Management](https://github.com/JaberElectro/GPU-Thermal-Management)** | Closed-loop fan control with a DHT11 and a MOSFET low-side switch, using hysteresis so the fans don't chatter around one threshold |
| 🚦 | **[NE555 Traffic Light](https://github.com/JaberElectro/NE555-Traffic-Light)** | Pure hardware timing with no microcontroller: RC math, duty-cycle limits, and why one 555 can't make three phases on its own |
| 🔢 | **[74HC595 Sequential LED](https://github.com/JaberElectro/74HC595-Sequential-LED)** | Serial-to-parallel conversion: data, clock and latch, and why the latch matters |
| 🎚️ | **[Potentiometer Transistor Control](https://github.com/JaberElectro/Potentiometer-Transistor-Control)** | Analog in, PWM out: ADC resolution, transistor drive, and the flyback diode a motor needs |
| 📡 | **[IR Remote LED Control](https://github.com/JaberElectro/IR-Remote-LED-Control)** | Decoding NEC infrared frames and mapping them to outputs |
| 🗑️ | **[Smart Automatic Trash Bin](https://github.com/JaberElectro/Smart-Automatic-Trash-Bin)** | Ultrasonic ranging, a servo-driven lid, and a small state machine tying them together |
| ✈️ | **[Aircraft Detection Concept](https://github.com/JaberElectro/Aircraft-Detection-Concept)** | An unfinished experiment, documented honestly: what simple sensors can and can't tell you |

## 🧭 How I approach a project

1. **Start from the signal.** Before writing code, I trace where the signal comes from, what converts it, and what it ends up driving.
2. **Pick parts for a reason.** A MOSFET instead of a BJT, a 74HC595 instead of more GPIO, hysteresis instead of a single threshold: each one is a decision I can explain.
3. **Write down the limits.** Every README has a section on what the design can't do. Knowing that is part of the engineering.

## 📈 Currently

- 🟢 Learning PCB design from scratch: schematic capture, footprints, layout and routing
- 🟡 Turning these breadboard projects into proper schematics

## 📫 Get in touch

Open to internships and graduate roles in embedded systems and electronics.

<p>
  <a href="https://www.linkedin.com/in/jaber-alluhayb-9b62a6370"><img src="https://img.shields.io/badge/LinkedIn-Jaber%20Alluhayb-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:jaberalluhayb@gmail.com"><img src="https://img.shields.io/badge/Email-jaberalluhayb%40gmail.com-cf222e?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
