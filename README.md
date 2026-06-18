[README.md](https://github.com/user-attachments/files/29103894/README.md)
# 🤖 IR-Controlled Robot Car

A 4-wheel Arduino robot car built from a Keyestudio smart car kit, currently driven by infrared remote control, with onboard sensors ready for future autonomous features.

<p align="center">
  <img src="images/robot-front-view.jpg" width="400" alt="Robot car front view" />
  <img src="images/ir-remote.jpg" width="400" alt="Keyestudio IR remote" />
</p>

## 🔧 What it is

This is a hands-on hardware build: assembling the chassis, wiring up the motor driver, sensors, and IR receiver, and getting it driving reliably via remote control. The kit comes equipped with an ultrasonic distance sensor and IR line-tracking sensors, which aren't in use yet but set the car up for autonomous modes down the line.

## 📦 Hardware

- Keyestudio 4WD smart robot car chassis
- Arduino-compatible control board + motor driver shield
- HC-SR04 ultrasonic distance sensor
- IR line-tracking sensor module
- Keyestudio IR receiver + remote control
- 4× AA battery pack

## 🎮 Current functionality

- Drive forward, backward, left, and right using the included IR remote
- Stock Keyestudio firmware/example sketch for IR control

## 🚧 Planned improvements

- [ ] Write custom Arduino code (replacing the stock sketch) for finer control
- [ ] Add obstacle-avoidance mode using the ultrasonic sensor
- [ ] Add line-following mode using the IR line-tracking sensors
- [ ] Document wiring diagram and pin mapping

## 📸 Build photos

<p align="center">
  <img src="images/robot-side-view.jpg" width="500" alt="Robot car side view" />
</p>

---

*A work-in-progress hardware project — more features coming as I dig into the Arduino code.*
