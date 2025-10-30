Arma 3 Helmet Camera Monitor System / Sistema Monitor Telecamera Casco
🇮🇹 Italiano
📖 Descrizione
Questo script per Arma 3 permette di collegare monitor agli operatori equipaggiati con telecamere sul casco per visualizzare il loro feed video in tempo reale. Ideale per missioni di sorveglianza, operazioni tattiche e scenari di comando e controllo.

🚨 Requisiti
LO SCRIPT NON FUNZIONERÀ SENZA QUESTI DUE MOD:

Mod Obbligatorie:
CBA_A3 - Community Base Addons for Arma 3

cTab - Interface for Android Tactical Assault Kit

⚙️ Installazione
Assicurati di avere installati CBA_A3 e cTab

Posiziona lo script nella cartella appropriata della tua missione

Configura le unità secondo le necessità

🎮 Utilizzo
Assegna telecamere sul casco agli operatori

Collega i monitor agli operatori equipaggiati

Visualizza i feed video in tempo reale sui monitor collegati

⚡ Importante
Impostazioni Grafiche:
Per un funzionamento ottimale della Picture-in-Picture (PiP), impostare le grafiche almeno su "High"

Fix Inclusi (v2.0):
Utilizzo di elementi Vanilla

Correzione posizione camera

Sistema Picture-in-Picture ottimizzato

🔧 Configurazione Camera
sqf
// Aggiustamento posizione camera
private _adjustedPos = _eyePos vectorAdd ((_eyeDir vectorMultiply 0.08) vectorAdd [-0.162, -0.015, -0.01]);
🤝 Ispirazione
Ispirato da: Helmet Cam System

🛠️ Sviluppo Futuro
Sto cercando di implementare funzionalità simili per:

Torrette dei veicoli

Droni della fazione Blufor

Se conosci script o mod esistenti per queste funzionalità, per favore contattami! Sono sempre felice di testare nuovi miglioramenti.

📝 Note
Testato con Arma 3 versione stabile

Compatibile con la maggior parte dei modset

Performance ottimizzate per PiP

🇬🇧 English
📖 Description
This Arma 3 script allows monitors to be connected to operators equipped with helmet cameras to display their real-time video feed. Ideal for surveillance missions, tactical operations, and command and control scenarios.

🚨 Requirements
SCRIPT WILL NOT WORK WITHOUT THESE TWO MODS!

Required Mods:
CBA_A3 - Community Base Addons for Arma 3

cTab - Interface for Android Tactical Assault Kit

⚙️ Installation
Ensure you have CBA_A3 and cTab installed

Place the script in the appropriate folder of your mission

Configure units as needed

🎮 Usage
Assign helmet cameras to operators

Connect monitors to equipped operators

Display real-time video feeds on connected monitors

⚡ Important
Graphics Settings:
For optimal Picture-in-Picture (PiP) performance, set graphics to at least "High"

Included Fixes (v2.0):
Vanilla elements used

Camera position fixed

Optimized Picture-in-Picture system

🔧 Camera Configuration
sqf
// Camera position adjustment
private _adjustedPos = _eyePos vectorAdd ((_eyeDir vectorMultiply 0.08) vectorAdd [-0.162, -0.015, -0.01]);
🤝 Inspired By
Inspired by: Helmet Cam System

🛠️ Future Development
I'm trying to implement similar functionality for:

Vehicle turrets

Bluforce faction drones

If you know of existing scripts or mods for these features, please let me know! I'm always happy to test new improvements.

📝 Notes
Tested with stable Arma 3 version

Compatible with most modsets

Performance optimized for PiP

For issues or suggestions, check the comments section or contact the developer.
