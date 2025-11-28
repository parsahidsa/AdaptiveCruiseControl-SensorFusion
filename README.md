# Adaptive Cruise Control with Sensor Fusion

## Projektbeschreibung
Ein vollständiges Beispiel für ein **Adaptives Tempomat-System (ACC)** unter Verwendung von **Radar–Kamera Sensorfusion**, **Autobahnszenarien** und **MPC/PID-basierter Längsregelung**.

### **Technologien**
- **MATLAB**  
- **Simulink**  
- **Automated Driving Toolbox**  
- **Sensor Fusion Toolbox**  
- **MPC (Model Predictive Control)**  
- **PID Control**

---

## **Projektstruktur**
AdaptiveCruiseControl-SensorFusion
│
├── src/ → Haupt-Simulink-Modelle & Skripte
│ ├── ACC_TestBenchExample.slx
│ ├── AdaptiveCruiseControlWithSensorFusionExample.m
│ ├── ACCTestBenchScenario.m
│ ├── helperACC*.m
│
├── images/ → Diagramme & Bilder
│ ├── dynamicsEqn.png
│ ├── mpcBirdsEyeScopeACC1.png
│ ├── plot.jpg
│
├── docs/ → Projektbericht (PDF)
│ └── Projektbericht.pdf
│
└── videos/ → Simulationsergebnisse
└── simulation.mp4


---

## **Installation**
1. **MATLAB installieren** (Version 2021a oder neuer empfohlen)  
2. **Simulink** und **Automated Driving Toolbox** installieren  
3. Klone dieses Repository auf deinen Computer oder lade die Dateien herunter.

---

## **Verwendung**
1. Öffne das Hauptmodell **ACC_TestBenchExample.slx** in **MATLAB/Simulink**.
2. Überprüfe die **Parametereinstellungen** für Sensorfusion und Fahrzeugdynamik.
3. Starte die Simulation, um das **Adaptive Cruise Control** zu testen und die Ergebnisse zu analysieren.
4. Die **Simulationsdaten** werden als Visualisierungen und **Energieverbrauch** angezeigt.

---

## **Beitrag**
Beiträge sind willkommen! Wenn du Verbesserungen oder neue Funktionen hinzufügen möchtest, erstelle bitte einen **Pull Request**.

---


## **Ziel des Projekts**
Das Hauptziel dieses Projekts ist es, ein funktionsfähiges Modell für ein autonomes **Adaptives Tempomat-System (ACC)** zu entwickeln, das die Verwendung von **Sensorfusionstechnologien** (Radar + Vision) kombiniert und zur **Energieoptimierung** in **Autobahnszenarien** beiträgt. Zusätzlich soll das System als Grundlage für weiterführende **Forschung in autonomer Mobilität** und **nachhaltiger Fahrzeugentwicklung** dienen.

---

### **Funktionen**
- **Dynamische Geschwindigkeitsregelung** basierend auf den Verkehrsbedingungen  
- **Integration von Radar- und Kameradaten** zur Objekterkennung  
- **Longitudinalregelung mit PID/MPC**  
- **Abstandserhaltung und Kollisionsvermeidung**  
- **Energieeffizienzbewertung** im Verkehrsfluss
- **Optimierung der Fahrstrategie** für nachhaltige Mobilität

---

## **Wichtige Ressourcen**
- [MATLAB Documentation](https://ch.mathworks.com/help/driving/ug/adaptive-cruise-control-with-sensorfusion.html)
