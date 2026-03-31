# ✈️ Boeing 737 Style MCDU-diy (Work in Progress)

Design, Modelling and 3D-Printing of a Multipurpose Control and Display Unit for Flight Simulations.

---

## 💡 Projekt-Hintergrund & Credits
In diesem Repository dokumentiere ich den Bau einer **FMC/CDU**, die maßgeblich auf der Entwicklung von **Shahada Abubakar** basiert. 

👉 **Original-Projekt:** [Shahada Abubakar's Blog](https://blog.shahada.abubakar.net/)

> **Wichtiger Hinweis:** Bitte habt Respekt vor Shahadas intensiver Arbeit. Erwähnt ihn unbedingt, wenn ihr von seinem Wissen profitiert oder dieses Projekt präsentieren wollt.
>
> <img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/d4d782d8-da67-484d-93dd-e8a3e1c65f99" />



Mein Ziel ist es, das Projekt genau zu analysieren und ein **eigenes Design** zu konstruieren, anstatt es nur 1:1 nachzubauen.

Eine weitere empfohlene Community-Seite für euch www.oshwlab.com 

---

## 🚧 Aktueller Status
- [x] Recherche & Quellenanalyse (Shahada Abubakar Blog)
- [x] Auswahl der Hardware-Basis (Raspberry Pi 3)
- [x] MCDU PCB-Board Hergestellt von https://jlcpcb.com/
- [x] Konstruktion der ersten Gehäuseteile (CAD)
- [ ] Prototyping der Tastenmechanik
- [ ] Erstellung der finalen Einkaufsliste

---

## 🛠 Voraussetzungen
Bevor du startest, solltest du folgendes einplanen:
*   **Hardware:** Zugang zu einem 3D-Drucker.
*   **Elektronik:** Regelbarer Lötkolben mit feiner Spitze.
*   **Software-Skills:** Grundverständnis für **Tinkercad** (oder andere CAD-Programme) sowie **Orca-Slicer**.
*   **Logistik:** Bereitschaft für Einkäufe aus dem Ausland (Tipp: Vorher auch ebay.de prüfen).

---

## 📦 Die Wichtigsten Komponenten in diesem Projekt!
*Die Liste wird laufend erweitert.*



| Bauteil | Status | Anmerkung, Risiken und Beschreibung |
| :--- | :--- | :--- |
| **Raspberry Pi 3** | ✅ Vorhanden | Das Herzstück für Display und Logik |
| **Display** | ✅ Empfohlen max 5 Zoll IPS | Details folgen. Dies ist eines der kritischen Teilen; es entscheidet maßgeblich über das 3D-Druck-Design. Beispiel: https://de.aliexpress.com/item/1005010562121937.html?spm=a2g0o.order_list.order_list_main.126.63c55c5fbFeYdC&gatewayAdapt=glo2deu
| **Tasten-Matrix** | ✅ Taktile Schalter mit LED | Auch kritisch, Button-Größe muss wahrscheinlich angepasst werden im CAD-Programm https://de.aliexpress.com/item/1005008121388807.html?spm=a2g0o.order_list.order_list_main.90.63c55c5fbFeYdC&gatewayAdapt=glo2deu | 
| STL-Datein | ✅ Unten unter Downloads | Die genaue Maße wird zurzeit entwickelt, im Ordner "STL-3MF" findet ihr die Vorgänger-Datein von Shahada |
| Gerber-Daten | ✅ Unten unter Downloads | Die PCB-Boards müssen von Leiterplattenherstellern produziert werden z.B. bei https://jlcpcb.com/ (max 5 Stück werden hergestellt, für einen Board machen sie keine Produktion) |

Für weitere mögliche Bauteile seht ihr im Ordner "Media".



---

## 📂 Ordnerstruktur (Geplant)
*   `/STL-3MF`: Enthält STL- und Design-Dateien.
*   `/Gerber`: PCB-BOARD.
*   `/Media`: Fotos von Baufortschritt und Baukomponenten.

---



---

## 🤝 Mitwirken
Da dies ein "Work in Progress" ist, freue ich mich über Austausch! Wenn du Tipps zu den 3D-Druck-Einstellungen oder der Matrix-Verkabelung hast, eröffne gerne ein **Issue**.
