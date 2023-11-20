---
title: 'Zero Trust '
theme: bitnate
layout: intro
colorSchema: 'light'
hideInToc: true
---

# Was ist eigentlich Zero Trust?
## Ein Einblick in moderne kryptographische Anwendungsfälle

Campus 02 - Fachhochschule der Wirtschaft

---
layout: about-me
presenterImage: 'https://media.licdn.com/dms/image/D4D03AQFjJWq1RnGnYA/profile-displayphoto-shrink_800_800/0/1699289513103?e=1706140800&v=beta&t=ynMeTnvtsfd-e9pWhS8re6_FbiPvOyla4_4rRLknwzQ'
hideInToc: true
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
hideInToc: true

---
### Verschlüsselung

- Geschichte von Verschlüsselung
- Stream & Block Chiffren
- Moderne Blockchiffren
  - DES
  - 3DES
  - AES

<v-click>
### Hahsing

- Einwegfunktionen
- Kollisionen
- Moderne Algorithmen
  - SHA
  - BCRYPT (Passwort)
  - Argon2 (Passwort)
</v-click>

::right::
<v-click>
### Asymmetrische Krypto

- Dieffie Hellman (DH)
- Rivest Shamir Adelman (RSA)
- Elliptic Curve Cryptography (ECC)
- "Key Exchange Problem"
</v-click>

---
layout: center
hideInToc: true

---

Big Question?

# Wie wird das jetzt eigentlich Angewendet?

---
layout: default
hideInToc: true

---

<v-click>

### Verschlüsselung

- 🌐 **VPN-Verbindungen:** Implementierung von DES/3DES/AES für sichere Kommunikation.
- 🌐 **Cloud-Sicherheit:** Verwendung von AES zur sicheren Speicherung von Daten in der Cloud.
- 🚁 **Drohnenkommunikation:** AES für sichere Steuerung und Datenübertragung bei Drohnen.

</v-click>

<v-click>

### Hashing

- 🔑 **Passwortsicherheit:** BCRYPT für sicheres Hashen von Passwörtern.
- 📁 **Integritätsprüfung:** Verwendung von SHA zum Überprüfen der Dateiintegrität.
- 📱 **Digitale Signaturen:** Anwendung von Hashfunktionen in RSA für digitale Signaturen.

</v-click>


<v-click>

### Asymmetrische Kryptographie

- 🤝 **Sicherer Schlüsselaustausch:** DH in sicheren Kommunikationskanälen.
- 🌐 **SSL/TLS-Verschlüsselung:** Verwendung von RSA für sichere HTTPS-Verbindungen im Web.
- 🚀 **Blockchain:** ECC zur Sicherung von Transaktionen in Blockchain-Netzwerken.

</v-click>

---
layout: section
---
# Die Welt von Zero Trust
Eine Einführung

---
layout: content-picture
image: 'https://images.unsplash.com/photo-1559116284-9c57b7a01f7a?q=80&w=3570&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'
hideInToc: true

---

# 🚷 Zero Trust?

- **Traditionelle Ansätze überdenken:** Den Status quo aus Sicherheitssicht challengen!
- **Misstrauen als Basis:** Generell sollten wir keiner aktivität unserer IT-Systeme trauen.
- **Kontinuierliche Überprüfung:** Jede Aktivität und Identität wird kontinuierlich überprüft.

---
layout: content-picture
image: 'https://images.unsplash.com/photo-1572435555646-7ad9a149ad91?q=80&w=3570&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'
hideInToc: true

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
hideInToc: true

---
## Trust based Security

- **Vertrauen, aber überprüfen:**
  - Statische Sicherheitszonen 🏰
  - Einmal gewährtes Vertrauen 🔍
  - Mangelnde kontinuierliche Überprüfung 🔄

---
layout: content-picture
image: 'https://miro.medium.com/v2/resize:fit:1400/0*kHFo8yegI1q02pA3'
hideInToc: true

---
## Trust based Security

- **Feste Identitäten:**
  - Statische Identitäten 🤖
  - Feste Zugriffsrechte 🔒
  - Schwierigkeiten in dynamischer Umgebung 🌐
  - Langsame Anpassungsfähigkeit 🐌

---
layout: content-picture
image: 'https://cf-assets.www.cloudflare.com/slt3lc6tev37/5Q5gi9cihPVrNEVvlnA2TV/45fba984653ae2d54e30652b466da784/castle-and-moat_security_model-resized.png'
hideInToc: true

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
hideInToc: true

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
hideInToc: true

---

## Grundprinzipien

- **Never Trust, Always Verify** 🔍
  - Kontinuierliche Überprüfung
  - Misstrauen als Grundlage
- **Implement Least Privileged Access** 🔒
  - Geringstmögliche Berechtigungen
  - Begrenzung von Zugriffsrechten

---
layout: content-picture
image: 'https://www.nextlabs.com/wp-content/uploads/Principles-of-ZTA-1-1.jpg'
hideInToc: true

---

## Grundprinzipien

- **Assume Breach** 🚨
  - Annahme von Sicherheitsvorfällen
  - Fokus auf schnelle Erkennung


---
layout: content-picture
image: 'https://discover.strongdm.com/hubfs/618b007756edd86ecb738143_zero-trust.svg'
hideInToc: true

---
## Zero Trust Architecture

- **Infrastructure**
  - Micro-Segmentation 🧩
  - Encryption Everywhere 🔐
- **Identities**
  - Continuous Authentication 🔄
  - Least Privilege Access 🔒
- **Devices**
  - Least Privilege Access 🔒
  - Zero Trust for Devices and Users 💻👤
---
layout: content-picture
image: 'https://discover.strongdm.com/hubfs/618b007756edd86ecb738143_zero-trust.svg'
hideInToc: true

---
## Zero Trust Architecture

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
hideInToc: true

---
Big Question?

# Was glaubt ihr? Wo wird hier Kryptographie verwendet?

---
layout: default
hideInToc: true

---
## Überblick vom Einsatz der Kryptographie

| **Komponente** | **Kryptographie** | **Use-Case** |
| --- | --- | --- |
| **Infrastructure** 🧩 | 🔐 Datenverkehrsverschlüsselung | 🌐 Sicherer Datenverkehr in die Cloud |
| **Infrastructure** 🔐 | 🔐 Ganzheitliche Datenverschlüsselung | 🏰 Umfassende Infrastruktursicherheit |
| **Identities** 🔄 | 🔐 Kryptografische Identitätsprüfung | 🚨 Kontinuierliche Authentifizierung |
| **Identities** 🔒 | 🔐 Sichere Zugriffsrechte | 💻 Minimaler Zugriff auf Identitäten |
| **Devices** 🔒 | 🔐 Kryptografische Sicherheit | 📱 Sichere Gerätezugriffsrechte |
| **Devices** 💻👤 | 🔐 Authentifizierung und Autorisierung | 🔒 Zero Trust für Geräte und Benutzer |

---
layout: default
---
## Überblick vom Einsatz der Kryptographie

| **Komponente** | **Kryptographie** | **Use-Case** |
| --- | --- | --- |
| **Applications** 🔒 | 🔐 Zugriffsabsicherung | 💾 Zugriffskontrolle mit SAML & co. |
| **Applications** 💻 | 🔐 Kryptografische Identitätsprüfung | 🔒 Zero Trust für Anwendungen |
| **Networks** 🧩 | 🔐 Encryption in Transit | 🌐 Sicherer Netzwerkdatenverkehr |
| **Networks** 🔐 | 🔐 Inspection | 🏰 Sichere Netzwerkkommunikation |
| **Data** 🔐 | 🔐 Datenverschlüsselung | 🔄 Durchgängige Datenverschlüsselung |
| **Data** 💻👤 | 🔐 Kryptografische Sicherheit | 🔒 Zero Trust für sichere Daten |


---
layout: center
hideInToc: true

---
Big Question?

# Was muss sich an unserer Denkweise ändern?

---
layout: quote
author: Zero Trust Denkweise
hideInToc: true

---
In der Welt des Zero Trust wird die Denkweise revolutioniert, indem Identitäten zum zentralen Element werden. Diese Identitäten repräsentieren nicht nur Benutzer, sondern auch Netzwerke, Geräte, Anwendungen und die gesamte Infrastruktur.
---
layout: content-picture
image: 'https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/RWIwt2_tbmnl_en-us?scl=1'
hideInToc: true

---

## Identitäten als zentrales Element

- **Zentrale Verwaltung:** Alles als Identität betrachten für zentrale Ressourcenregulierung. 🌐
- **Effektive Regulierung:** Identitäten für Zugriffsregulierung und Sicherheitsrichtlinien. 🔐
- **Ganzheitliche Sicherheit:** Identitäten für umfassende Sicherheitsstrategie. 🛡️

---
layout: section
---
# Zero Trust Umsetzung

🏢 Wie sichern wir Unternehmensinfrastruktur ab?

---
layout: content-picture
image: 'https://venturebeat.com/wp-content/uploads/2022/12/Zscaler-zero-trust-wheel.jpg?fit=1210%2C633&strip=all'
hideInToc: true

---

# Anwendungsgebiete
Zero Trust Prinzipien sind mittlerweile weit verbreitet und überall im Einsatz!

- Remote Access
- Cloud Computing
- Critical Infrastrcuture
- Operational Technology
- Corporates
- Software Security
- Internet

---
layout: facts
heading: "Was sind typische Anwendungen?"
hideInToc: true

---

- Work from Anywhere?
- Cloud Infrastruktur?
- Absichern von Softwareentwicklung?
- Security at all Layers?

---
layout: statement
hideInToc: true

---
# Time to Recap!

---
layout: default
hideInToc: true

---
## Recap: Zero Trust Essentials 🚀

1. **Never Trust, Always Verify:** Kein Standardvertrauen, kontinuierliche Überprüfung.
2. **Identitäten im Fokus:** Alles als Identität betrachten für zentrale Ressourcenregulierung. 🌐
3. **Effektive Regulierung:** Identitäten für Zugriffsregulierung und Sicherheitsrichtlinien. 🔐
4. **Ganzheitliche Sicherheit:** Identitäten für umfassende Sicherheitsstrategie. 🛡️
5. **Paradigmenwechsel:** Von "Vertrauen, aber überprüfen" zu "Never Trust, Always Verify". 🔄
6. **Sicherheit in der Tiefe:** Micro-Segmentation und durchgängige Verschlüsselung. 🧩🔐
7. **Identitätsüberprüfung:** Kontinuierliche Authentifizierung und Least Privilege Access. 🔄🔒
8. **Veränderung der Denkweise:** Alles als Identität sehen, nicht nur Benutzer. 💭
9. **Zero Trust Architecture:** Schlüsselkomponenten in Infrastruktur, Identitäten, Devices, Applications, Networks und Data. 🏰💻📡💾
10. **Schlüsselaustausch:** Sicherer Austausch von Verschlüsselungsschlüsseln mit Protokollen wie Diffie-Hellman. 🔑

<a href="https://cloudsecurityalliance.org/education/cczt/">Erfahre mehr über Zero Trust und die Verschmelzung mit Kryptographie für eine sicherere digitale Welt! 🌐🔒</a>

---
layout: end
hideInToc: true

---
Vielen Dank für eure Aufmerksamkeit!
