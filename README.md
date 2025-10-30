# 🎥 Arma 3 CG-Operator-s-view-on-monitor-V2.1
## 📸 Preview / Anteprima

<img width="1870" height="935" alt="sc1" src="https://github.com/user-attachments/assets/13eda284-b0d7-4682-8175-ece237783497" />

<img width="1467" height="755" alt="sc2" src="https://github.com/user-attachments/assets/481edbb1-6b24-45f7-8274-9a868704fca5" />

<img width="1712" height="847" alt="sc3" src="https://github.com/user-attachments/assets/4b7b35ef-b2bd-4315-9b36-4b13c34e4144" />

<img width="637" height="358" alt="sc4" src="https://github.com/user-attachments/assets/4530ad3d-c757-4bbc-807f-2223122ffd58" />


---


### 🧩 Version
**FIX V2.1**

- Used element: **Vanilla**
- In case of undercover missions (CIVIL), the operator's name will be in 🟣 **PURPLE**, not 🔵 **BLUE**.
- **Fix:** Camera position adjustment  
- **Graphics requirement:** PiP (Picture-in-Picture) **at least on High**
- Fix for multiplayer

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

### 🎯 Trigger: [**BLUFORCE to CIVILIAN for Undercover**](https://steamcommunity.com/sharedfiles/filedetails/?id=3595437256)

If you want to easily switch your BLUFORCE unit to a **civilian identity** during undercover missions, you can use this trigger:

**Trigger Name:** `BLUFORCE to CIVILIAN for Undercover`  

This trigger allows operators to change side and appearance dynamically during missions, making covert operations more immersive and functional.  
It can be placed directly in the **Arma 3 Editor**, and combined with the helmet cam script for full tactical control.

---

### 💡 Inspired by
[Live Map (Whiteboard)](https://steamcommunity.com/sharedfiles/filedetails/?id=3018683365)

---

### 🔧 Camera Position Adjustment
Fine-tuned for better alignment and realism.

```sqf
private _adjustedPos = _eyePos vectorAdd ((_eyeDir vectorMultiply 0.08) vectorAdd [-0.162, -0.015, -0.01]);
