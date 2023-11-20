---
title: 'Zero Trust '
theme: bitnate
layout: intro
colorSchema: 'light'
---

# Was ist eigentlich Zero Trust?
## Ein Einblick in moderne kryptographische Anwendungsfälle

Campus 02 - Fachhochschule der Wirtschaft

---
layout: about-me
presenterImage: 'https://media.licdn.com/dms/image/D4D03AQFjJWq1RnGnYA/profile-displayphoto-shrink_800_800/0/1699289513103?e=1706140800&v=beta&t=ynMeTnvtsfd-e9pWhS8re6_FbiPvOyla4_4rRLknwzQ'
---

# Christian Gubesch

- 📍 Graz, Austria 🇦🇹
- 🌐 Check out my [LinkedIn](https://www.linkedin.com/christian-gubesch)
- 📧 E-Mail me at [christian.gubesch@gmail.com](mailto:christian.gubesch@gmail.com)
- 💼 Working at @BearingPoint
- 🎓 Education in IT, Business, and Business Development

---
layout: default
---
# Agenda

<Toc/>

---
layout: section
---

# Einblick in die Kryptographie

Was haben wir alles kennen gelernt?

---
layout: two-cols
---
### Verschlüsselung

- Geschichte von Verschlüsselung
- Stream & Block Chiffren
- Moderne Blockchiffren
  - DES
  - 3DES
  - AES

### Hahsing

- Einwegfunktionen
- Kollisionen
- Moderne Algorithmen
  - SHA
  - BCRYPT (Passwort)
  - Argon2 (Passwort)

::right::
### Asymmetrische Krypto

- Dieffie Hellman (DH)
- Rivest Shamir Adelman (RSA)
- Elliptic Curve Cryptography (ECC)
- "Key Exchange Problem"

---
layout: center
---

Big Question?

# Wie wird das jetzt eigentlich Angewendet?

---
layout: default
---
### Verschlüsselung

- 🌐 **VPN-Verbindungen:** Implementierung von DES/3DES/AES für sichere Kommunikation.
- 🌐 **Cloud-Sicherheit:** Verwendung von AES zur sicheren Speicherung von Daten in der Cloud.
- 🚁 **Drohnenkommunikation:** AES für sichere Steuerung und Datenübertragung bei Drohnen.

### Hashing

- 🔑 **Passwortsicherheit:** BCRYPT für sicheres Hashen von Passwörtern.
- 📁 **Integritätsprüfung:** Verwendung von SHA zum Überprüfen der Dateiintegrität.
- 📱 **Digitale Signaturen:** Anwendung von Hashfunktionen in RSA für digitale Signaturen.

### Asymmetrische Kryptographie

- 🤝 **Sicherer Schlüsselaustausch:** DH in sicheren Kommunikationskanälen.
- 🌐 **SSL/TLS-Verschlüsselung:** Verwendung von RSA für sichere HTTPS-Verbindungen im Web.
- 🚀 **Blockchain:** ECC zur Sicherung von Transaktionen in Blockchain-Netzwerken.


---
layout: section
---
# Die Welt von Zero Trust
Eine Einführung

---
layout: content-picture
image: 'https://images.unsplash.com/photo-1559116284-9c57b7a01f7a?q=80&w=3570&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'
---

# 🚷 Zero Trust?

- **Traditionelle Ansätze überdenken:** Den Status quo aus Sicherheitssicht challengen!
- **Misstrauen als Basis:** Generell sollten wir keiner aktivität unserer IT-Systeme trauen.
- **Kontinuierliche Überprüfung:** Jede Aktivität und Identität wird kontinuierlich überprüft.

---
layout: content-picture
image: 'https://images.unsplash.com/photo-1572435555646-7ad9a149ad91?q=80&w=3570&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'
---
# 🔐 Zero Trust 🔁 Kryptographie

- **Verschlüsselung** 
- **Authentifizierung**
- **Schlüsselaustausch** 
- **Ende-zu-Ende-Verschlüsselung** 
- **Zertifikatsmanagement & Identitäten**
- **Datenintegrität**
- **Non-Repudiation**

---
layout: section
---

# Die Evolution der Sicherheitsmodelle

## 🏰 Kurzer Blick auf traditionelle Modelle


---
layout: content-picture
image: 'https://miro.medium.com/v2/resize:fit:1400/0*kHFo8yegI1q02pA3'
---
## Trust based Security (1)

- **Vertrauen, aber überprüfen:**
  - Statische Sicherheitszonen 🏰
  - Einmal gewährtes Vertrauen 🔍
  - Mangelnde kontinuierliche Überprüfung 🔄

---
layout: content-picture
image: 'https://miro.medium.com/v2/resize:fit:1400/0*kHFo8yegI1q02pA3'
---
## Trust based Security (2)

- **Feste Identitäten:**
  - Statische Identitäten 🤖
  - Feste Zugriffsrechte 🔒
  - Schwierigkeiten in dynamischer Umgebung 🌐
  - Langsame Anpassungsfähigkeit 🐌

---
layout: content-picture
image: 'https://cf-assets.www.cloudflare.com/slt3lc6tev37/5Q5gi9cihPVrNEVvlnA2TV/45fba984653ae2d54e30652b466da784/castle-and-moat_security_model-resized.png'
---
## Perimeter based Security

- **Perimeter-Sicherheit:**
  - Stark auf Perimetersicherheit gesetzt 🏰
  - Geschützter Bereich um das Netzwerk definiert 🌐
  - Alles innerhalb galt als vertrauenswürdig ✔️
  - Vernachlässigung externer Bedrohungen 🚫
  - Mangelnde Absicherung bei internen Angriffen 🤯

---
layout: center
---

Big Question?
# Wieso braucht es jetzt einen Wechsel der Denkweise?

---
layout: section
---

# Der Zero Trust Paradigmenwechsel

Was zeichnet Zero Trust aus?

---
layout: content-picture
image: 'https://www.nextlabs.com/wp-content/uploads/Principles-of-ZTA-1-1.jpg'
---

### Grundprinzipien

- **Never Trust, Always Verify** 🔍
  - Kontinuierliche Überprüfung
  - Misstrauen als Grundlage
- **Implement Least Privileged Access** 🔒
  - Geringstmögliche Berechtigungen
  - Begrenzung von Zugriffsrechten

---
layout: content-picture
image: 'https://www.nextlabs.com/wp-content/uploads/Principles-of-ZTA-1-1.jpg'
---

### Grundprinzipien

- **Assume Breach** 🚨
  - Annahme von Sicherheitsvorfällen
  - Fokus auf schnelle Erkennung


---
layout: content-picture
image: 'https://discover.strongdm.com/hubfs/618b007756edd86ecb738143_zero-trust.svg'
---
### Zero Trust Architecture

- **Infrastructure**
  - Micro-Segmentation 🧩
  - Encryption Everywhere 🔐
- **Identities**
  - Continuous Authentication 🔄
  - Least Privilege Access 🔒
- **Devices**
  - Least Privilege Access 🔒
  - Zero Trust for Devices and Users 💻👤
  - Zero Trust for Devices and Users 💻👤

---
layout: content-picture
image: 'https://discover.strongdm.com/hubfs/618b007756edd86ecb738143_zero-trust.svg'
---
### Zero Trust Architecture

- **Applications**
  - Least Privilege Access 🔒
  - Zero Trust for Devices and Users 💻👤
- **Networks**
  - Micro-Segmentation 🧩
  - Encryption Everywhere 🔐
- **Data**
  - Encryption Everywhere 🔐
  - Zero Trust for Devices and Users 💻👤
---
layout: center
---
Big Question?

# Was glaubt ihr? Wo wird hier Kryptographie verwendet?

---
layout: default
---
# Überblick vom Einsatz der Kryptographie
Eventuell mit Tabelle

---
layout: center
---
Big Question?

# Was muss sich an unserer Denkweise ändern?

---
layout: default
---

# Identitäten als zentrales Element
Wie können wir das machen?

---
layout: default
---

# Identity Management
+ zentrales identity management.
+ zentrale berechtigungsverwaltung.
+ bla bla bla

---
layout: section
---
Fallstudie: Zero Trust Umsetzung

🏢 Wie sichern wir Unternehmensnetzwerke ab?
📊 Erfahrungen und Verbesserungen

---
layout: default
---

challenge mit 3-4 anwendungsfälle
---
layout: end
---
Vielen Dank für eure Aufmerksamkeit!
