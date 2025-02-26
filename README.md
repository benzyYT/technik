# **Rekonstruktion eines Symmetrischen Signals**

## **1. Einleitung**
In der Audiotechnik werden symmetrische Signale genutzt, um Störungen zu minimieren und die Signalqualität zu verbessern. Diese Technik ist besonders in professionellen Anwendungen wie Studiotechnik und Bühnenbeschallung wichtig.

---

## **2. Aufbau eines Symmetrischen Signals**
Ein symmetrisches Kabel besteht aus drei Leitungen:
- **Signal+ (Hot, nicht invertiert)**
- **Signal- (Cold, invertiert)**
- **Masse (Shield, Ground)**

Das Signal wird zweimal übertragen: einmal normal (**S+**) und einmal invertiert (**S-**). Dadurch können Störungen, die sich gleich auf beide Signale auswirken, effektiv entfernt werden.

---

## **3. Mathematische Rekonstruktion**
Um das eigentliche Signal aus dem symmetrischen Signal zurückzugewinnen, wird die Differenz der beiden Signale gebildet:

S_out = S+ - S-

Da Störungen N sich gleich auf beide Leitungen auswirken, gilt:

S+ = S + N
S- = -S + N

Durch die Differenzbildung ergibt sich:

S_out = (S + N) - (-S + N)
S_out = S + N + S - N
S_out = 2S

**Ergebnis:**
- Das eigentliche Signal S wird verstärkt.
- Die Störung N wird herausgefiltert (Gleichtaktunterdrückung).

---

## **4. Vorteile der Symmetrischen Signalübertragung**
✅ **Hohe Störsicherheit**: Externe Einstreuungen werden eliminiert.
✅ **Geeignet für lange Kabelwege**: Ideal für professionelle Audio-Setups.
✅ **Bessere Signalqualität**: Weniger Rauschen und Verzerrungen.
✅ **Vermeidung von Brummschleifen**: Masseprobleme haben weniger Einfluss.

---

## **5. Steckerbelegung für Symmetrische und Unsymmetrische Beschaltung**

### **XLR auf XLR (symmetrisch)**
- Pin 1: Masse (Shield)
- Pin 2: Signal + (Hot)
- Pin 3: Signal - (Cold)

### **Klinke auf Klinke (symmetrisch)**
- Spitze (Tip): Signal + (Hot)
- Ring: Signal - (Cold)
- Schaft (Sleeve): Masse (Shield)

### **XLR auf Klinke (symmetrisch)**
- XLR Pin 1 → Klinke Sleeve (Masse)
- XLR Pin 2 → Klinke Tip (Signal +)
- XLR Pin 3 → Klinke Ring (Signal -)

### **XLR auf Klinke (unsymmetrisch)**
- XLR Pin 1 → Klinke Sleeve (Masse)
- XLR Pin 2 → Klinke Tip (Signal)
- XLR Pin 3 → mit Pin 1 verbunden (kein invertiertes Signal)

Diese Belegungen sind wichtig, um die Signalqualität zu erhalten und Störungen zu vermeiden.

---

## **6. Fazit**
Die symmetrische Signalübertragung ist eine effektive Methode zur Störungsreduzierung und wird in der professionellen Audiotechnik bevorzugt. Durch die Differenzbildung wird das eigentliche Signal verstärkt und Störungen werden eliminiert, wodurch eine hohe Klangqualität gewährleistet wird.

**Anwendungsbereiche:**
- Studiotechnik (Mikrofone, Mischpulte, Audio-Interfaces)
- Bühnen- und PA-Technik
- Professionelle Verkabelung von Audiosystemen

---

**Danke für die Aufmerksamkeit!** 🎵

