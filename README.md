# IoT Safety & Energy Systems — Digital Bangladesh Mela 2023

> 🏆 **Top 10 Innovator**, Digital Bangladesh Mela 2023
> 📰 Covered by **আজকের পত্রিকা** and **News24 TV**

Three connected hardware projects built as undergraduate research at **Bangladesh University of Business and Technology (BUBT)**, under the supervision of the Vice Chancellor, Prof. Dr. Muhammed Fayyaz Khan, with lecturer and researcher Md Reazul Islam.

Each device targets a problem that is common in Bangladeshi households and workplaces but has no affordable commercial solution locally.

---

## 1. Harassment Detection Smart Dress

**Problem:** When a woman is suddenly in danger, she often cannot reach her phone to call 999. The seconds spent unlocking a phone are the seconds that matter.

**Solution:** Clothing with embedded pressure sensors. When it detects unwanted grabbing pressure, it fires an alert without the user touching anything.

**How it works:**
- Pressure sensors woven into the garment detect an unwanted grip.
- GPS + GSM module resolves the wearer's location and sends SMS with a Google Maps link.
- The companion app lets the user pre-save relatives' phone numbers as alert recipients.
- The alert also goes to the nearest police station helpline for that location.
- Live location keeps updating so police and family can track movement, not just the first ping.
- A user-controlled on/off switch — the wearer decides when the system is armed.

**Hardware:** Pressure sensors · GPS module · GSM module · Companion mobile app

📄 [Read the আজকের পত্রিকা coverage](https://www.ajkerpatrika.com/255879/%E0%A6%AA%E0%A7%8B%E0%A6%B6%E0%A6%BE%E0%A6%95-%E0%A6%AC%E0%A6%BE%E0%A6%81%E0%A6%9A%E0%A6%BE%E0%A6%AC%E0%A7%87-%E0%A6%AF%E0%A7%8C%E0%A6%A8-%E0%A6%A8%E0%A6%BF%E0%A6%B0%E0%A7%8D%E0%A6%AF%E0%A6%BE%E0%A6%A4%E0%A6%A8%E0%A6%95%E0%A6%BE%E0%A6%B0%E0%A7%80-%E0%A6%93-%E0%A6%85%E0%A6%AA%E0%A6%B9%E0%A6%B0%E0%A6%A3-%E0%A6%A5%E0%A7%87%E0%A6%95%E0%A7%87)

---

## 2. Methane (CH4) Gas Leakage Alarm

**Problem:** Methane is the standard cooking gas in most Bangladeshi kitchens. It is flammable and explosive at high concentration, and a slow leak is invisible and odour-fatiguing — people stop noticing it.

**Solution:** A low-cost detector that raises a local alarm and a remote notification the moment concentration crosses the threshold.

**How it works:**
- A CH4 sensor continuously samples ambient air.
- On detection, a buzzer sounds immediately.
- Status LED: **green** = safe, **red** = gas detected — readable at a glance from across the room.
- The user receives a notification on their mobile phone, so an empty house still raises an alert.

**Hardware:** CH4 gas sensor · Buzzer · Status LEDs · Mobile notification link

---

## 3. Smart AC Light Dimmer

**Problem:** Lights and fans run at full power when nobody needs full power. In a country with load-shedding and rising tariffs, wasted watts are a real household cost.

**Solution:** A small AC dimmer module that gives remote, granular control over brightness and fan speed — and works with energy-efficient LED bulbs rather than requiring incandescents.

**How it works:**
- Compact module wired inline with the existing light or fan.
- Brightness and fan speed adjustable in steps, not just on/off.
- Controlled from a smartphone app or voice assistant over the home Wi-Fi network.
- Reports live on/off status back to the app.
- Controllable from anywhere with an internet connection.
- Dimming an LED to a low level turns a normal bulb into a night light — no second fixture needed.

**Hardware:** AC dimmer module · Wi-Fi gateway · Smartphone app / voice assistant integration

![AC Dimmer](ac%20dimmer.jpg)

---

## Repository contents

| File | What it is |
|---|---|
| [`Sexual Haragment Detection With Smart Dress`](Sexual%20Haragment%20Detection%20With%20Smart%20Dress) | Full project write-up (Bengali) for the smart safety dress |
| [`Gas Leakage Alarm`](Gas%20Leakage%20Alarm) | Methane detector design notes and feature spec |
| [`AC Light Dimmer`](AC%20Light%20Dimmer) | Dimmer module design notes and feature spec |
| [`Ajker Patrika Article link`](Ajker%20Patrika%20Article%20link) | Link to the newspaper coverage |
| `ac dimmer.jpg` | Photo of the assembled dimmer module |

---

## Team

| Role | Name |
|---|---|
| Research Assistant | **Md. Manzurul Islam** — [GitHub](https://github.com/AB69D) · [LinkedIn](https://www.linkedin.com/in/ab9d/) |
| Researcher / Lecturer | Md Reazul Islam, Dept. of CSE, BUBT |
| Supervisor | Prof. Dr. Muhammed Fayyaz Khan, Vice Chancellor, BUBT |

---

*Exhibited at Digital Bangladesh Mela 2023. This repository holds the design documentation and specifications; hardware schematics and firmware are available on request.*
