# 🎥 Arma 3 Helmet Camera Monitor Script — FIX V2.0

---

## 🇬🇧 English Version

### 🧩 Version
**FIX V2.0**

- Used element: **Vanilla**
- **Fix:** Camera position adjustment  
- **Graphics requirement:** PiP (Picture-in-Picture) **at least on High**

---

### 📝 Description
This **Arma 3 script** allows monitors to be connected to operators equipped with **helmet cameras**, showing their **real-time video feed** on in-game displays.

Ideal for immersive command centers or tactical operations where live visual feedback is required.

---

### ⚙️ Requirements

#### 🔹 Required Mods
- **[CBA_A3](https://steamcommunity.com/workshop/filedetails/?id=450814997)**  
- **[cTab](https://steamcommunity.com/sharedfiles/filedetails/?id=2511318948)**  

> ⚠️ **The script will NOT work without these two mods!**

---

### 💡 Inspired by
[Helmet Camera Script](https://steamcommunity.com/sharedfiles/filedetails/?id=3018683365)

---

### 🔧 Camera Position Adjustment
Fine-tuned for better alignment and realism.

```sqf
private _adjustedPos = _eyePos vectorAdd ((_eyeDir vectorMultiply 0.08) vectorAdd [-0.162, -0.015, -0.01]);
